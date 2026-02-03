# ✅ Task Management

The Project Roadmap module extends Perfex CRM tasks with dependencies, subtasks, progress indicators, bookmarks, templates, and custom fields.

---

## 📊 Task Progress Indicators

Each task in the **List View** shows a **colored progress badge** next to the task name.

| Progress | Display | Color |
|----------|---------|-------|
| 0% | `0%` | Gray (not started) |
| 1–99% | `25%`, `75%`, etc. | Blue (in progress) |
| 100% | `100%` | Green (complete) |

The color reflects the task status for quick visual feedback. Progress is based on the task's `percent_complete` field in Perfex.

---

## 🔗 Task Dependencies

Define which tasks must complete before others can start. Dependencies use **finish-to-start** logic.

### ➕ Add a Dependency (Gantt View)

1. Open the project's **Gantt** view
2. Click **Manage Dependencies**
3. Select the task that *has* the dependency (the dependent task)
4. Choose the task it *depends on* (the predecessor)
5. Click **Add Dependency**

### ➖ Remove a Dependency

- In the Manage Dependencies modal, click **Remove** next to the dependency in the list

### 📌 Where Dependencies Appear

- **Gantt chart** – Dependency lines between tasks
- **Critical Path Analysis** – Dashboard section when dependencies exist (shows tasks in the chain that affect project end date)

---

## 🌳 Subtasks (Parent-Child)

Link tasks in a hierarchy. A parent task can have multiple child tasks.

### ➕ Add a Subtask (Gantt View)

1. Open the project's **Gantt** view
2. Click **Manage Subtasks**
3. Select the **parent task**
4. Choose the task to add as a **child**
5. Click **Add Subtask**

### ➖ Remove a Subtask

- In the Manage Subtasks modal, click **Remove Subtask** next to the child in the list

---

## ⭐ Task Bookmarks

Quick access to tasks you're following.

| Action | How |
|--------|-----|
| **Add bookmark** | Click the star icon next to a task in the task table |
| **View bookmarks** | Project Roadmap → Task Bookmarks |
| **Remove bookmark** | Click the star again (or from Task Bookmarks page) |

---

## 📝 Task Templates

Reusable task structures for common workflows.

### Create a Template

1. Go to **Project Roadmap → Task Templates**
2. Click **Add Template**
3. Enter name, description, and task data (name, description, estimated hours, etc.)
4. Save

### Use a Template

1. Go to **Project Roadmap → Task Templates**
2. Select a template and a project
3. Click **Use Template**
4. Tasks are created in the project based on the template

---

## 📎 Task Custom Fields

Store extra data per task (text, select, date, number).

### Define Custom Fields (Admin)

1. Go to **Project Roadmap → Custom Fields**
2. Add a field with type: text, textarea, select, number, date
3. Set as project or task field
4. Set required, display order, active/inactive

### Edit Task Custom Fields

- In the project dashboard **Tasks table**, click the **pencil icon** in the Custom Fields column
- A modal opens with all task custom fields for that task
- Edit and save

---

## 📋 Project Custom Fields

Project-level custom fields are displayed in the **Overview** section of the project dashboard. Define them in Project Roadmap → Custom Fields (admin) and set type to "project".
