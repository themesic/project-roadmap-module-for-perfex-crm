# ⚙️ Settings

Custom fields, AI suggestions, notifications, branded portal, automated workflows, and role-based permissions.

---

## 📎 Custom Fields (Admin)

- **Location** – Project Roadmap → Custom Fields
- **Access** – Admin only

### Add a Custom Field

1. Click **Add Field**
2. Set **Field label**
3. Choose **Type**: text, textarea, select, number, date
4. Set **Relation type**: project or task
5. Configure:
   - **Required** – Yes/No
   - **Display order**
   - **Active** – Show/hide

### Edit or Delete

- Use the options next to each field to edit or delete

---

## 🤖 AI Suggestions Settings (Admin)

- **Location** – Project Roadmap → AI Suggestions Settings
- **Access** – Admin only

### Options

| Setting | Description |
|---------|-------------|
| **Enable** | Turn AI suggestions on/off |
| **Provider** | Rule-based only, OpenAI (GPT), or Anthropic (Claude) |
| **API Key** | Your OpenAI or Anthropic API key (for LLM enhancement) |
| **Model** | e.g. `gpt-4o-mini`, `claude-3-5-haiku-20241022` |

See [AI Suggestions](ai-suggestions.md) for full usage.

---

## 🔔 Notification Settings

- **Location** – Project Roadmap → Notification Settings
- **Purpose** – Per-user preferences for task and project notifications

Configure which events trigger notifications for your account.

---

## 🎨 Branded Portal Settings (Admin)

- **Location** – Project Roadmap → Branded Portal Settings
- **Access** – Admin only
- **Purpose** – Customize client portal appearance

| Setting | Description |
|---------|-------------|
| **Primary color** | Main accent (e.g. borders, headings) |
| **Secondary color** | Secondary accent |

Colors are used in the project updates and milestone approval sections shown to clients.

---

## ⚡ Automated Workflows (Manage)

- **Location** – Project Roadmap → Automated Workflows
- **Access** – Manage permission or Admin

### Add a Workflow

1. Click **Add Workflow**
2. Enter **Workflow name**
3. Select **Trigger event**:
   - `task_completed`
   - `task_assigned`
   - `milestone_completed`
   - `project_updated`
4. Select **Action**:
   - `notify_client`
   - `notify_team`
   - `add_activity`
5. Save

### Delete a Workflow

- Click the delete button next to the workflow
- Confirm

---

## 🔐 Role-Based Permissions

Configure in **Setup → Staff → Roles** for the Project Roadmap module.

| Permission | Description |
|------------|-------------|
| **View** | Access project roadmap features, view data |
| **Edit** | Edit project roadmap data (tasks, milestones, etc.) |
| **Manage** | Manage workflows, custom fields, AI settings, portal settings |
