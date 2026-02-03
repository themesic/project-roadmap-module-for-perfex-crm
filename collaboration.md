# 💬 Collaboration

Team communication, activity feed, timesheet approvals, centralized files, and notifications.

---

## 💬 Team Communication Hub

- **Location** – Project Roadmap → [Project] → Team Communication Hub (or from toolbar)
- **URL** – `projectroadmap/communication_hub/{project_id}`

### Create a Discussion

1. Enter **Subject**
2. Enter **Content**
3. Optionally attach files
4. Submit

### Add Comments

- Reply to discussions with comments
- **@Mentions** – Type `@` followed by a staff name to mention them (sends notification)
- **File attachments** – Attach files to comments

### @Mentions

- Type `@` and start typing a staff name
- Select from the dropdown
- Mentioned staff receive a notification with a link to the comment

---

## 📜 Activity Feed

- **Location** – Project Roadmap → [Project] → Activity Feed (toolbar)
- **URL** – `projectroadmap/activity_feed/{project_id}`

### Automatic Activities

| Event | Activity Logged |
|-------|-----------------|
| Task added | "task_created" |
| Task updated | "task_updated" |
| Project added | "project_created" |
| Project updated | "project_updated" |

### Manual Activity

- Click **Add Activity** to log a custom event
- Enter description and save

---

## ⏱️ Timesheet Approvals

- **Location** – Project Roadmap → Timesheet Approvals

### How It Works

- When staff **start a task timer**, a timesheet approval record is created (pending)
- Approve or reject from the Timesheet Approvals page

### Actions

| Action | Description |
|--------|-------------|
| **Approve** | Mark time as approved |
| **Reject** | Reject with optional note |
| **Sync** | Populate from `tbltaskstimers` (adds any missing records) |

### Filters

- Filter by status: Pending, Approved, Rejected

---

## 📁 Centralized File Storage

- **Location** – Project Roadmap → Centralized File Storage
- **Purpose** – View all project files in one place across all projects

### Features

| Feature | Description |
|--------|-------------|
| **List view** | All files with project, name, upload date |
| **Download** | Click to download |
| **View versions** | See file version history |

---

## 📂 File Versioning

- **Automatic** – Versions are recorded when files are uploaded (via `after_project_file_added` hook)
- **View history** – Click "View versions" in Centralized File Storage or project files
- **URL** – `projectroadmap/file_versions/{project_id}/{file_id}`

---

## 🔔 Real-Time Notifications

- **Location** – Project Roadmap → Notification Settings
- **Purpose** – Per-user preferences for what to be notified about

### Notification Types

| Type | Description |
|------|-------------|
| Task assigned | When you're assigned to a task |
| Task deadline approaching | When a task due date is near |
| Project updates | When project is updated |
| Milestone completed | When a milestone is completed |

---

## 📧 Email Digest

- **Location** – Project Roadmap → Email Digest
- **Purpose** – Daily or weekly project summary emails

### Configuration

- **Enable/disable** – Toggle digest on or off
- **Frequency** – Daily or weekly
- **Cron** – Add `projectroadmap/cron_email_digest` to your server cron for automated sending

### Cron Setup

Add to your server crontab (example – daily at 8 AM):

```
0 8 * * * php /path/to/perfex/index.php projectroadmap cron_email_digest
```
