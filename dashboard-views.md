# 📋 Dashboard & Views

The Project Roadmap module provides multiple ways to view and manage your projects. Use the **toolbar** at the top of any project to switch between views.

---

## 🏠 Main Dashboard Widget

The Project Roadmap widget appears on the **Perfex CRM main dashboard** (admin home).

- **Add** – Add project roadmaps to your dashboard from the dashboard customization
- **View** – Each widget shows a mini project roadmap (overview, charts, milestones, tasks)
- **Remove** – Click the remove icon to remove a project from your dashboard

---

## 🏠 Project Dashboard (List View)

The main project view is the **List View** – your central hub for project oversight.

### 📊 Overview Section

- **Project name** – With link to full project details
- **Client** – Linked to client profile
- **Status** – Current project status
- **Dates** – Start and deadline
- **Members** – Team size
- **Project custom fields** – Any custom fields you've defined (displayed in the overview table)
- **Project progress** – Circular progress indicator
- **Project health score** – Color-coded health metric
- **Budget vs Actual** – Estimated vs logged hours
- **Earned Value Management (EVM)** – PV, EV, AC, SV, CV, CPI, SPI, EAC, ETC (see [Budget & Invoicing](budget-invoicing.md))

### 📈 Charts

| Chart | Description |
|-------|-------------|
| **Milestone Status** | Variable pie chart – Not started, In process, Complete |
| **Task Status** | 3D pie chart – Task counts by status |
| **Task Priority** | Column chart – Tasks by priority level |
| **Estimate Hours** | Bar chart – Budget vs actual hours by member |

### 👥 Members Table

- **Name** – Click to filter tasks by that member
- **Total tasks assigned**
- **Completed tasks**
- **Late tasks**
- **Logged hours**

### 📌 Milestones Table

- **Name, progress, status**
- **Start/end dates**
- **Client approval** – Approve/Reject buttons for staff

### 📋 Tasks Table

- **Filterable** by milestone, assignee, status
- **Task progress badge** – Colored percentage (0%, 25%, 75%, 100%)
- **Custom fields column** – Click pencil icon to edit task custom fields
- **Bookmark** – Star icon to add to Task Bookmarks

---

## 🔀 View Switcher (Toolbar)

| View | Icon | URL | Description |
|------|------|-----|-------------|
| **List** | 📋 | `view_projectroadmap` | Table view with charts and filters |
| **Gantt** | 📊 | `gantt` | Timeline with dependencies |
| **Kanban** | 📌 | `kanban` | Drag-and-drop board |
| **Calendar** | 📅 | `calendar` | Month/week view |

### Additional Toolbar Actions

| Button | Description |
|--------|-------------|
| **Export PDF** | Download project report as PDF |
| **Export Excel** | Download as Excel (.xls) |
| **Activity Feed** | View project activity timeline |
| **Sprints** | Sprint planning and velocity |
| **Resource Allocation** | Hours per staff per project |
| **Team Communication Hub** | Discussions and comments |
| **Project** | Link to main Perfex project view |

---

## 📊 Gantt Chart View

- **Timeline** – Tasks and milestones on a horizontal timeline
- **Click tasks** – Opens task modal (Perfex native)
- **Manage Dependencies** – Add/remove task dependencies (finish-to-start)
- **Manage Subtasks** – Link parent/child tasks
- **AI Suggestions** – Get assignee and due date tips (when enabled in settings)

---

## 📌 Kanban Board View

- **Columns** – One per task status (Not started, In progress, etc.)
- **Drag & drop** – Move tasks between columns to update status
- **Click task** – Opens task modal

---

## 📅 Calendar View

- **Month / Week / List** – Switch view modes
- **Tasks & milestones** – Shown as events
- **Export iCal** – Download .ics file for one-time import
- **Subscribe to Calendar** – Get URL for Google Calendar, Outlook (see [Calendar Sync](calendar-sync.md))

---

## 📱 Mobile Responsive

All views are optimized for mobile and tablet. The module includes responsive CSS for optimal viewing on smaller screens.
