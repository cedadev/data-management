# NERC grants data management tracking: Quick reference guide

## ⚠️ Essential set-up

- Add your GitHub username to your DataMad account details
- Turn on both `On Github` and `Email` notifications in [your notification settings](https://github.com/settings/notifications)
- To keep your inbox tidy, set up a rule which routes your reminders to a dedicated folder, e.g.:
    - 'For messages which contain '[organisation-name/repo-name]' in the subject line'
    - 'For all messages from notifications@github.com'.

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