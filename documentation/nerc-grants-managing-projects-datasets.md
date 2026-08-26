# Managing projects and datasets

## 👀 Viewing active projects and datasets
Five views are available for viewing projects and datasets. Switch between views by clicking on their tabs. Each view displays projects, datasets, and their metadata differently depending on use case.

#### All projects & All datasets
Two kanban board views which show all active projects and datasets. These views are best for users who need an overview of things like activity, progress, and workload.

#### My projects & My datasets
Two kanban boards which show only the projects and datasets assigned to the viewing user. These views are best for users who need to focus on progressing their assigned projects and datasets. Multiple users can use these views at any one time. 

#### Reporting
A tabular view for managing metadata per field and tracking key metrics. This view is best for users who need to query all issues for management and reporting purposes.

## ℹ️ Customising views
Views are highly customisable and can be edited using the filter bar (underneath the view tabs) and `⚙️View` menu (to the right of the filter bar).

Feel free to apply new filters if you need to find something specific, but please don't save these changes as it will override the settings for all other users. The exception to this is the Reporting view which is expected to be updated depending on the needs of the reporting manager. 

If you think that a new permanent view would be useful, use the contact information below to discuss if this can be included in future iterations of the workflow.

## 📂 Creating a project
Projects are not created in GitHub directly. Instead, project creation is triggered from DataMad. 

Create a project by claiming a new grant in DataMad and clicking `Create GitHub issue`. This will create a `Project` issue auto-populated with the grant metadata stored in DataMad.

The project is now ready for tracking!

## 📊 Creating a dataset
Unlike projects, datasets are created in GitHub directly.

In GitHub terminology, `Dataset` issues are **sub-issues** which sit within corresponding `Project` **parent issues**. This simply means that one `Project` issue can be used to group multiple related `Dataset` issues.

Create a dataset by first opening the `Project` issue you need to add datasets to. Scroll down to the bottom of the issue body and click `Create sub-issue`. This button sits just before the issue's activity feed. In the `Create new sub-issue` dialog, click `Dataset (NERC grant)`, then add the following information when prompted:

- Title, formatted as 'NERC ID: Working dataset title'
- Any initial notes about the dataset (e.g. 'Model output, estimated volume ~30GB')

Then click `Create`. To create multiple sub-issues without leaving the dialog, check the `Create more sub-issues` checkbox before clicking `Create`. 

Once a sub-issue has been created, an automated script is triggered which adds all essential metadata by:

- Assigning the sub-issue to the user who created it
- Applying the `Dataset` project type
- Auto-populating the metadata fields with information from the parent project
- Setting the status to `Pre-delivery comms`

The dataset is now ready for tracking!

## 🔗 Integrations with other data management tools
The data management workflow takes place across multiple tools (e.g. a grant in DataMad relates to a DMP on Data Stewardship Wizard which relates one or more conversations in Help Scout, etc).

Links to this information are collected in the `Links` section at the top of `Project` issues. This section contains the following links: 

- Help Scout
- DataMad: auto-populated when a project issue is created
- DSW
- Dataset [add link]
- Instrument/Computation/Platform [add link]
- Project [add link/delete]
- Collection [add link /delete]

These are markdown links which require the URLs adding as they become available, e.g.:

```
# Link waiting for URL to be added
[Help Scout]()

# Link with URL added
[Help Scout](https://secure.helpscout.net/conversation/12345)
```

Manually update these links by clicking on the three dots at the top of the issue body and editing the markdown text.

Future development work aims to more closely integrate GitHub with the other tools used in the data management workflow. At the moment DataMad and Help Scout, next DSW and Arrivals.

### DataMad
Project issues are created in GitHub through the `Create GitHub issue` button in DataMad. At the moment this integration is one-way only: DataMad can send information to GitHub, but GitHub cannot currently send information back to DataMad. 

A two-way integration is planned for future development. This would remove the need to manually enter values in the fields which are duplicated across both platforms (e.g. `Date contacted PI`).

### Help Scout

### Data Stewardship Wizard

## MOLES

## ✅ Task checklists


## 📑 Metadata fields


## ⏰ Reminders


