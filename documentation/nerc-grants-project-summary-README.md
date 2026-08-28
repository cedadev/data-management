---

📣 Welcome to the NERC grants data management tracking GitHub Project. Below is an introductory README only. [Read the docs](https://github.com/cedadev/data-management/blob/9f055838bbd1f95a35126b7bd2b35acd77140ecc/documentation/nerc-grants-documentation.md) for full support with getting started.

---

## 🔀 Track NERC grants and the datasets they generate through the whole data management lifecycle.

## 📂 High-level structure

### Projects
- Represent grants or other data-generating activities
- Act as **parent issues** to one or more dataset **sub-issues**

### Datasets
- Represent individual datasets produced by a project
- Created as **sub-issues** within a project **parent issue**

## 🔎 Views

Choose from five pre-configured views:

- **All projects**: All active projects by status
- **All datasets**: All active datasets by status
- **My projects**: Projects assigned to you
- **My datasets**: Datasets assigned to you
- **Reporting**: Table view of all metadata fields for reporting and export

> ⚠️ Feel free to filter views temporarily, but do not save changes unless updating the Reporting view.

---

## ✨ Creating items

### Create a project
Projects are created in DataMad by claiming a grant and selecting `Create GitHub Issue`.

### Create  a dataset
1. Open the parent project issue
2. Click `Create sub-issue`
3. Select `Dataset (NERC grant)`
4. Enter the dataset title and any notes
5. Create the issue

A built-in automation will then:
- Assign the creator
- Set the issue type to `Dataset`
- Copy key metadata from the parent project
- Set the status to `Pre-delivery comms`

---

## 🎯 Tracking progress

### Statuses

Projects and datasets move through the following lifecycle:

`No Status` → `DMP in progress` → `Pre-delivery comms` → `Data due` → `Archiving in progress` → `Archiving completed`

Additional statuses:
- `No archival data`
- `Escalate to NERC`

How to update statuses:

- Drag and drop the issue into a new column (kanban board view)
- Update the metadata field directly (table view)
- Via the issue's right-hand sidebar (when viewing an issue)

### Checklists

Each issue contains a checklist of tasks. Complete the tasks for the current stage before moving to the next status.

### Labels

Use labels to highlight blockers:

- `On hold`: Waiting for information or action
- `Unresponsive`: Progress blocked by a lack of response

Add a comment explaining the reason whenever a blocker is applied.

---

## Reminders

### Automated reminders

Labels and notifications are automatically triggered when:
- Annual check-ins are due
- 6-month check-ins are due
- Actual end dates have passed

### Manual reminders

Create reminders by commenting:

```text
/remind me to send the first DMP chase in 6 weeks
```

Reminders are posted back to the issue when due.

> ⚠️ Enable both GitHub and Email notifications in your GitHub notification settings.

---

## Useful metadata

Key fields include:

- NERC ID
- UKRI ID
- Data centre
- PI name
- Status
- Actual start date
- Actual end date
- DMP agreed
- Data delivery expected
- Data delivered

Most fields are populated automatically. Update workflow-specific fields as work progresses.

---

## Links and integrations

Project issues contain links to related resources such as:

- DataMad
- Help Scout
- DSW
- Dataset records
- Computation records
- Project records

The DataMad link is created automatically. Other links should be added by editing the issue body.

Help Scout conversations should be linked directly to project issues using the GitHub integration in Help Scout.

---

## 💬 Help and support
Contact Lucy Killoran at CEDA (lucy.killoran@stfc.ac.uk) with any issues, queries, feedback, or ideas for improvements.