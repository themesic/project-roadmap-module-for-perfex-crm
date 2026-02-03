# 📈 Reporting & Analytics

Export reports, custom report builder, resource allocation, analytics, and more.

---

## 📄 Export Reports

From the project view toolbar:

| Format | Button | Output |
|--------|--------|--------|
| **PDF** | Export PDF | Project report as PDF document |
| **Excel** | Export Excel | Project data as .xls spreadsheet |

Both exports include project overview, milestones, tasks, and key metrics.

---

## 🔧 Custom Report Builder

- **Location** – Project Roadmap → Custom Report Builder
- **Purpose** – Define saved report configurations with filters and columns for task data

### Create a Report Configuration

1. Go to **Project Roadmap → Custom Report Builder**
2. Click **Add Report Config**
3. Set **Name** (e.g., "Open Tasks by Status")
4. Configure **Filters** (JSON, e.g. `{"status":["1","2","5"]}` for task statuses)
5. Set **Columns** (JSON array, e.g. `["name","status","duedate"]` for task columns)
6. Save

### Filters & Columns Format

| Field | Format | Example |
|-------|--------|---------|
| **Filters** | JSON object | `{"status":["1","2","5"]}` |
| **Columns** | JSON array of task field names | `["name","status","duedate","priority"]` |

### Run a Report

1. Go to **Project Roadmap → Custom Report Builder**
2. Click **Run Report** next to a configuration
3. View results in a table (first 100 tasks shown)
4. Results are filtered by your report config and your project access

---

## 👥 Resource Allocation

- **Location** – Project Roadmap → Resource Allocation
- **Purpose** – View hours and task count per staff per project

### Global View

- Table of all staff with hours and tasks per project
- Select a project for a detailed view

### Project-Specific View

- **URL** – `projectroadmap/resource_allocation/{project_id}`
- Shows hours and tasks per team member for that project

---

## 📊 Resource Utilization Report

- **Location** – Project Roadmap → Resource Utilization Report
- **Purpose** – Hours logged per staff member across all projects
- Use to identify overall workload and availability

---

## 📉 Analytics Page

- **Location** – Project Roadmap → Analytics
- **Purpose** – Project health trends and team efficiency metrics

| Metric | Description |
|--------|-------------|
| **Project health** | Trends over time |
| **Team efficiency** | Completion rates, velocity |

---

## 📌 Project Baseline

Create snapshots of the project plan for variance tracking.

### Add a Baseline

1. On the project dashboard, find **Project Baseline**
2. Enter a **Baseline name** (e.g., "Q1 Plan")
3. Click **Add Baseline**

### View Baselines

- Listed with creation date
- Use for comparing current state to original plan

---

## 🐛 Issue/Bug Tracking

Track issues and bugs linked to projects.

### Report an Issue

1. On the project dashboard, find **Issue/Bug Tracking**
2. Click **Report Issue**
3. Fill in:
   - **Title** (required)
   - **Description**
   - **Task** (optional – link to a specific task)
   - **Priority** (low, medium, high)
4. Submit

### View Issues

- Table shows: Title, Status (open/closed), Reported by
- Filter by status as needed
