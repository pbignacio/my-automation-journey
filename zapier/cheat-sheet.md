# 🧠 Zapier Automation Cheat Sheet

> A practical, big‑picture reference for building clean, scalable automations using Zapier.
>
> This document is designed for review purposes only.

---

## 🔹 Core Zap Structure

**Trigger → Logic → Actions**

**Overview:**
Every Zap follows this structure. Keeping these layers clear makes automations easier to understand, debug, and scale.

**Sample:**

```
Trigger: New Google Form response
Action: Add row to Google Sheets
```

**Use case:**
Automated data collection, lead intake, internal requests.

---

## 🔀 Paths by Zapier

**Purpose:** Conditional branching (if / else logic)

**Overview:**
Paths allow a single Zap to handle multiple scenarios by choosing which actions to run based on conditions.

**Sample:**

```
If Request Type = IT → Create ticket
If Request Type = HR → Send email
```

**Use case:**
Routing tickets, approvals, requests, or tasks to the correct department or workflow.

---

## 🚦 Filter by Zapier

**Purpose:** Allow or stop a Zap

**Overview:**
Filters act as gatekeepers. If conditions are not met, the Zap stops completely.

**Sample:**

```
Continue only if Status = Approved
```

**Use case:**
Preventing incomplete, unpaid, or invalid data from triggering actions.

---

## ⏱ Delay by Zapier

**Purpose:** Time‑based control

**Overview:**
Delays introduce timing into automation, allowing follow‑ups or scheduled actions.

**Sample:**

```
Wait 3 days → Send reminder email
```

**Use case:**
Invoice reminders, follow‑ups, cooling‑off periods, scheduled notifications.

---

## 🧮 Formatter by Zapier

**Purpose:** Data cleaning and transformation

**Overview:**
Formatter ensures data is compatible between apps by changing formats, text, numbers, or dates.

**Sample:**

```
Input: "John Doe"
Output: First Name = John, Last Name = Doe
```

**Use case:**
Fixing dates, splitting names, formatting currency, preparing CRM fields.

---

## 🔁 Looping by Zapier

**Purpose:** Repeat actions for multiple items

**Overview:**
Looping processes lists item‑by‑item instead of handling only one record.

**Sample:**

```
For each email → Send notification
```

**Use case:**
Bulk emails, processing multiple products, handling multiple form entries.

---

## 🧩 Utilities by Zapier

**Purpose:** Technical helper tools

**Overview:**
Utilities support advanced data handling where standard actions are insufficient.

**Sample:**

```
Create line items from text input
```

**Use case:**
Preparing structured data for CRMs, invoices, reports, or imports.

## 🧠 Quick Decision Guide

| Need           | Tool      |
| -------------- | --------- |
| Stop a Zap     | Filter    |
| Choose actions | Paths     |
| Wait           | Delay     |
| Clean data     | Formatter |
| Repeat actions | Looping   |


Add Zapier Cheat Sheet
