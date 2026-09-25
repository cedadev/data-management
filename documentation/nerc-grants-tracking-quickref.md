# NERC grants data management tracking: Quick reference guide

## ⚠️ Essential set-up

### GitHub
In your [GitHub notification settings](https://github.com/settings/notifications):
1. Set your default notifications email
2. Turn on both 'On Github' and 'Email' notifications for Subscriptions
3. Select all events in 'Customize email updates'

### Outlook
1. Set up a new folder for your GitHub notifications
2. In the menu, click 'Tools', then 'Rules', then 'Add rule'
3. For a rule to catch **NERC grants notifications only**:
  - Title: For all messages whose subject contains "[NERC-EDS/data-management]"
  - Subject includes: [NERC-EDS/data-management]
  - Move to: `<YOUR-FOLDER-NAME>`
4. For a rule which will catch **all GitHub notifications** (if you use GitHub for other things, you may prefer the rule above)
  - Title: For all messages from notifications@github.com
  - From: notifications@github.com
  - Move to: `<YOUR-FOLDER-NAME>`

## 🔀 The core workflow
- Use `My projects` and `My datasets` as your workspaces
- Follow the task checklists
- Keep statuses up to date  
- Record blockers with labels and comments  
- Use reminders to stay on track

## 🪆 The two issue types

### Project
- Represents a grant or other data-generating activity
- Acts as a **parent issue**
- Can contain multiple datasets

### Dataset
- Represents an individual dataset
- Created as a **sub-issue** within a project
- Tracked separately but inherits information from its parent project

## 👀 Key views
Most users will spend most of their time in `My projects` and `My datasets`:

|View|Purpose|
|---|---|
|My projects|Projects assigned to you|
|My datasets|Datasets assigned to you|
|All projects|Team-wide project overview|
|All datasets|Team-wide dataset overview|
|Reporting|Metadata, reporting, and exports|

## 🎯 Workflow statuses

Progress issues through eight statuses:
1. `No Status`
2. `DMP in progress`
3. `Pre-delivery comms`
4. `Data due`
5. `Archiving in progress`
6. `Archiving completed`
7. `No archival data`
8. `Escalate to NERC`

### Update status by:
- Dragging cards between kanban columns
- Editing the Status field in a table view
- Updating Status from the issue sidebar

## ✅ Checklists
- Every issue contains a task checklist
- Tasks are grouped by workflow stage
- Complete all tasks before moving to the next status
- For migrated issues, check off tasks already completed

## ✍️ Fields you need to maintain

Most fields are automated. Fields requiring manual updates are:
- `Status`
- `Funding stream`
- `DMP agreed`
- `Data delivery expected`
- `Data delivered`
- `Labels`

## 🛑 Blockers and labels
- `On hold`: Use when progress is waiting for an action, decision, or dependency
- `Unresponsive`: Use when progress is blocked by a lack of response from contacts

Always add a comment explaining the reason for the label.

## ⏰ Reminders

### Automated reminders
These reminder labels are applied automatically:
- `Annual check-in due`
- `6-month check-in due`
- `End date passed`

When you receive an automated reminder:
- Complete the required task
- Remove the reminder label

### Manual reminders
- Add a comment using: ```/remind [who] [what] [when]```
- Keep the `Reminder` label applied so GitHub can find and post the reminder.

## 📶 Monitoring dataset progress

In Project issues, use the `Sub-issues progress` field to see:
- Number of datasets created
- Number archived/closed
- Percentage complete

## 🔗 Project issue links
Project issues contain links to:
- `DataMad`
- `Help Scout`
- `DSW` (Data Stewardship Wizard)
- `Catalogue records`

Keep these updated.

## ℹ️ Help and support

Report bugs, usability issues, or improvement requests through the **[Data management support GitHub Project](https://github.com/orgs/NERC-EDS/projects/7)**.
