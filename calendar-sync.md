# 📅 Calendar Sync

Subscribe to project tasks and milestones in **Google Calendar**, **Outlook**, or any calendar app that supports iCal URLs.

---

## 🔗 How It Works

1. Open a project's **Calendar view**
2. Click **Subscribe to Calendar**
3. A **subscription URL** is generated (token-based, no login required)
4. Copy the URL and add it to your calendar app

---

## 📱 Adding to Google Calendar

1. Open [Google Calendar](https://calendar.google.com)
2. Go to **Settings** → **Add calendar** → **From URL**
3. Paste the subscription URL
4. Click **Add calendar**

---

## 📧 Adding to Outlook

1. Open Outlook Calendar
2. **Add calendar** → **Subscribe from web**
3. Paste the subscription URL
4. Save

---

## ⚠️ Important Notes

| Note | Description |
|------|-------------|
| **Project-specific** | Each URL is for one project only |
| **Secret token** | The URL includes a secret token for security |
| **Regeneration** | Each click on "Subscribe to Calendar" generates a new token – previous URLs stop working |
| **All-day events** | Tasks and milestones appear as all-day events |
| **Refresh** | The feed updates when your calendar app refreshes (typically every few hours) |
