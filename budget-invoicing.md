# 💰 Budget & Invoicing

Earned Value Management (EVM), retainer burn tracking, and invoice integration.

---

## 📊 Earned Value Management (EVM)

Displayed in the **Overview** section of the project dashboard when project budget data is available.

### Metrics Explained

| Metric | Full Name | Description |
|--------|-----------|-------------|
| **PV** | Planned Value | Budgeted cost of work scheduled |
| **EV** | Earned Value | Budgeted cost of work performed |
| **AC** | Actual Cost | Actual cost of work performed |
| **SV** | Schedule Variance | EV − PV (positive = ahead of schedule) |
| **CV** | Cost Variance | EV − AC (positive = under budget) |
| **CPI** | Cost Performance Index | EV ÷ AC (≥1 = on/under budget) |
| **SPI** | Schedule Performance Index | EV ÷ PV (≥1 = on/ahead of schedule) |
| **EAC** | Estimate at Completion | Projected total cost at completion |
| **ETC** | Estimate to Complete | Remaining cost to complete |

### Color Coding

- **Green** – On track (SV/CV ≥ 0, CPI/SPI ≥ 1)
- **Red** – Behind/over (SV/CV < 0, CPI/SPI < 1)

---

## ⏱️ Retainer Burn Tracking

Track retainer hours for fixed-fee or prepaid projects.

### Add a Retainer

1. On the project dashboard, find **Retainer Burn Tracking**
2. Fill in:
   - **Total hours** – Hours purchased/allocated
   - **Start date** – Retainer period start
   - **End date** – Retainer period end
3. Click **Add Retainer**

### View Retainer Status

| Column | Description |
|--------|-------------|
| **Total hours** | Allocated hours |
| **Used hours** | Logged time against the project |
| **Remaining** | Total − Used |
| **Progress bar** | Visual burn rate |

Used hours are calculated from task timers (logged time) on the project.

---

## 🧾 Invoice Integration

Link invoices to projects (and optionally to milestones).

### Link an Invoice

1. On the project dashboard, find **Invoice Integration**
2. Select an **Invoice** from the dropdown (client's invoices)
3. Optionally select a **Milestone** to associate
4. Click **Link Invoice**

### View Linked Invoices

- Listed in the Invoice Integration section
- Each link shows invoice number and optional milestone
- Click to open the invoice in Perfex

---

## 📈 Budget vs Actual

Displayed in the Overview when project has estimated hours:

| Metric | Description |
|--------|-------------|
| **Estimate hour** | Total estimated hours (from tasks) |
| **Actual** | Total logged hours (from task timers) |

---

## 📌 Critical Path Analysis

When the project has **task dependencies**, a **Critical Path Analysis** section appears on the dashboard.

| Column | Description |
|--------|-------------|
| **Task** | Task name (links to task) |
| **Depends on** | Predecessor task |
| **Due date** | Task due date |

Tasks in the critical path affect the project end date. Delays here directly impact the deadline.
