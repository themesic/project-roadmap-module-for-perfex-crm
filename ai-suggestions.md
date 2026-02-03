# 🤖 AI Suggestions

Get smart recommendations when creating tasks: suggested assignees and due dates.

---

## 📍 Where to Find It

| Location | How to Access |
|----------|---------------|
| **Project dashboard** | AI Suggestions panel (when enabled in settings) |
| **Gantt view** | AI Suggestions button in the toolbar |

---

## 🎯 Rule-Based Suggestions (No API Key)

Works **out of the box** – no configuration required:

| Suggestion | Logic |
|-------------|-------|
| **Suggested assignees** | Team members with the fewest tasks (workload balance) |
| **Suggested due date** | Based on average task duration in the project (or default 3 days) |

---

## 🔧 Optional LLM Enhancement

For AI-generated tips, configure an API key in **Project Roadmap → AI Suggestions Settings** (admin only).

### Settings

| Setting | Description |
|---------|-------------|
| **Provider** | Rule-based only, OpenAI (GPT), or Anthropic (Claude) |
| **API Key** | Your OpenAI or Anthropic API key |
| **Model** | e.g. `gpt-4o-mini`, `claude-3-5-haiku-20241022` |

### AI Insight

When configured, suggestions include an **AI Insight** – a brief practical tip for the new task based on project context, assignees, and due date.

---

## 📖 How to Use

1. Click **AI Suggestions** (on dashboard or in Gantt toolbar)
2. Review **Suggested assignees** and **Suggested due date**
3. Optionally read the **AI Insight** (if LLM is configured)
4. Use the suggestions when adding a task in Perfex (Projects → Add Task)

### API Endpoint (Optional)

For integrations: `projectroadmap/ai_suggestions/{project_id}`  
Optional query: `milestone_id` for milestone-specific suggestions.
