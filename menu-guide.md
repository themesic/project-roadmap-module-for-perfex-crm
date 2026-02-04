# 📍 Menu Guide – What Each Submenu Does

This guide explains **every item** under **Project Roadmap** in the sidebar. Use it to find what you need and what (if anything) you must configure first.

---

## How to Use This Guide

1. **Find the submenu** you’re interested in (they appear in the order below).
2. **Read what it does** and whether setup is required.
3. **Follow the configuration steps** if needed.
4. **Use the links** to jump to the full documentation.

---

## Submenu Items (in Sidebar Order)

### 1. Task Bookmarks

| | |
|---|---|
| **What it does** | Shows a list of tasks you’ve bookmarked for quick access. |
| **Where** | Project Roadmap → Task Bookmarks |
| **Configuration** | None. Just use it. |
| **How to add bookmarks** | In any project’s task table, click the star icon next to a task. |
| **Full docs** | [Task Management → Task Bookmarks](task-management.md#task-bookmarks) |

---

### 2. Timesheet Approvals

| | |
|---|---|
| **What it does** | Approve or reject time logged by staff via task timers. |
| **Where** | Project Roadmap → Timesheet Approvals |
| **Configuration** | None. Works as soon as staff use task timers. |
| **How it works** | When staff start a task timer in Perfex, a pending approval record is created. Use this page to approve or reject. |
| **Actions** | **Sync** – Pull in any missing records from task timers. **Approve** / **Reject** – Per record. |
| **Filters** | Pending, Approved, Rejected |
| **Full docs** | [Collaboration → Timesheet Approvals](collaboration.md#timesheet-approvals) |

---

### 3. Resource Allocation

| | |
|---|---|
| **What it does** | Shows hours and task count per staff member per project. |
| **Where** | Project Roadmap → Resource Allocation |
| **Configuration** | None. |
| **Use it for** | Seeing who is assigned to what and how many hours/tasks they have. |
| **Full docs** | [Reporting & Analytics → Resource Allocation](reporting-analytics.md#-resource-allocation) |

---

### 4. Resource Utilization Report

| | |
|---|---|
| **What it does** | Shows total hours logged per staff member across all projects. |
| **Where** | Project Roadmap → Resource Utilization Report |
| **Configuration** | None. |
| **Use it for** | Workload and availability overview. |
| **Full docs** | [Reporting & Analytics → Resource Utilization Report](reporting-analytics.md#-resource-utilization-report) |

---

### 5. Analytics

| | |
|---|---|
| **What it does** | Project health trends and team efficiency metrics. |
| **Where** | Project Roadmap → Analytics |
| **Configuration** | None. |
| **Use it for** | Trends over time, completion rates, velocity. |
| **Full docs** | [Reporting & Analytics → Analytics Page](reporting-analytics.md#-analytics-page) |

---

### 6. Custom Fields *(Admin only)*

| | |
|---|---|
| **What it does** | Add extra fields to projects and tasks (text, date, select, etc.). |
| **Where** | Project Roadmap → Custom Fields |
| **Configuration** | You define the fields here. |
| **Steps** | 1. Go to Custom Fields. 2. Add Field. 3. Set label, type, relation (project/task). 4. Save. |
| **Full docs** | [Settings → Custom Fields](settings.md#-custom-fields-admin) |

---

### 7. Notification Settings

| | |
|---|---|
| **What it does** | Choose which events send you notifications (task assigned, deadline, project updates, etc.). |
| **Where** | Project Roadmap → Notification Settings |
| **Configuration** | Per-user. Each staff member configures their own. |
| **Full docs** | [Collaboration → Real-Time Notifications](collaboration.md#real-time-notifications) |

---

### 8. Automated Workflows

| | |
|---|---|
| **What it does** | Automatically trigger actions when events happen (e.g. task completed → notify client). |
| **Where** | Project Roadmap → Automated Workflows |
| **Configuration** | Add workflows here. Requires **Manage** permission. |
| **Steps** | 1. Add Workflow. 2. Choose trigger (task_completed, task_assigned, milestone_completed, project_updated). 3. Choose action (notify_client, notify_team, add_activity). 4. Save. |
| **Full docs** | [Settings → Automated Workflows](settings.md#-automated-workflows-manage) |

---

### 9. Task Templates

| | |
|---|---|
| **What it does** | Reusable task structures. Create once, apply to any project. |
| **Where** | Project Roadmap → Task Templates |
| **Configuration** | Create templates here. |
| **Steps** | 1. Add Template. 2. Enter name, description, task data. 3. Save. 4. Use Template → select project → apply. |
| **Full docs** | [Task Management → Task Templates](task-management.md#task-templates) |

---

### 10. Centralized File Storage

| | |
|---|---|
| **What it does** | View all project files in one place across all projects. |
| **Where** | Project Roadmap → Centralized File Storage |
| **Configuration** | None. |
| **Use it for** | Download, view version history. |
| **Full docs** | [Collaboration → Centralized File Storage](collaboration.md#centralized-file-storage) |

---

### 11. Branded Portal Settings *(Admin only)*

| | |
|---|---|
| **What it does** | Customize colors of the client portal (project updates, milestone approvals). |
| **Where** | Project Roadmap → Branded Portal Settings |
| **Configuration** | Set Primary and Secondary colors. |
| **Full docs** | [Client Portal → Branded Portal](client-portal.md#branded-portal) |

---

### 12. Email Digest

| | |
|---|---|
| **What it does** | Receive daily or weekly project summary emails. |
| **Where** | Project Roadmap → Email Digest |
| **Configuration** | Per-user. Enable, choose frequency (daily/weekly). |
| **Important** | For automated sending, add a cron job. See below. |
| **Cron setup** | Add to crontab: `0 8 * * * php /path/to/perfex/index.php projectroadmap cron_email_digest` |
| **Full docs** | [Collaboration → Email Digest](collaboration.md#email-digest) |

---

### 13. Custom Report Builder

| | |
|---|---|
| **What it does** | Define saved report configurations (filters + columns) and run them on task data. |
| **Where** | Project Roadmap → Custom Report Builder |
| **Configuration** | Create report configs here. |
| **Steps** | 1. Add Report Config. 2. Set name, filters (JSON), columns (JSON). 3. Save. 4. Run Report. |
| **Full docs** | [Reporting & Analytics → Custom Report Builder](reporting-analytics.md#-custom-report-builder) |

---

### 14. AI Suggestions Settings *(Admin only)*

| | |
|---|---|
| **What it does** | Enable AI suggestions (assignee, due date) and optionally connect OpenAI/Anthropic. |
| **Where** | Project Roadmap → AI Suggestions Settings |
| **Configuration** | Enable, choose provider (rule-based only, OpenAI, Anthropic), add API key if using LLM. |
| **Note** | Rule-based suggestions work without any API key. |
| **Full docs** | [AI Suggestions](ai-suggestions.md) |

---

## Quick Reference: Configuration Checklist

| Feature | Needs setup? | Where to configure |
|---------|--------------|--------------------|
| Task Bookmarks | No | — |
| Timesheet Approvals | No | — |
| Resource Allocation | No | — |
| Resource Utilization | No | — |
| Analytics | No | — |
| Custom Fields | Yes | Project Roadmap → Custom Fields |
| Notification Settings | Yes (per user) | Project Roadmap → Notification Settings |
| Automated Workflows | Yes | Project Roadmap → Automated Workflows |
| Task Templates | Yes (create templates) | Project Roadmap → Task Templates |
| Centralized File Storage | No | — |
| Branded Portal | Yes | Project Roadmap → Branded Portal Settings |
| Email Digest | Yes (per user + cron) | Project Roadmap → Email Digest |
| Custom Report Builder | Yes (create configs) | Project Roadmap → Custom Report Builder |
| AI Suggestions | Yes (optional API) | Project Roadmap → AI Suggestions Settings |

---

## Permissions

Configure in **Setup → Staff → Roles**:

| Permission | What it allows |
|------------|----------------|
| **View** | Access all Project Roadmap features and view data |
| **Edit** | Edit tasks, milestones, and other project data |
| **Manage** | Manage workflows, custom fields, AI settings, portal settings |
