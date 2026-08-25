# Managing projects and datasets

## Viewing active projects and datasets
Five views are available for viewing projects and datasets. Switch between views by clicking on their tabs. Each view displays projects, datasets, and their metadata differently depending on use case.

#### All projects & All datasets
Two kanban board views which show all active projects and datasets. These views are best for users who need an overview of things like activity, progress, and workload.

#### My projects & My datasets
Two kanban boards which show only the projects and datasets assigned to the viewing user. These views are best for users who need to focus on progressing their assigned projects and datasets. Multiple users can use these views at any one time. 

#### Reporting
A tabular view for managing metadata per field and tracking key metrics. This view is best for users who need to query all issues for management and reporting purposes.

### Customising views
Views are highly customisable and can be edited using the filter bar (underneath the view tabs) and `⚙️View` menu (to the right of the filter bar).

Feel free to apply new filters if you need to find something specific, but please don't save these changes as it will override the settings for all other users. The exception to this is the Reporting view which is expected to be updated depending on the needs of the reporting manager. 

If you think that a new permanent view would be useful, use the contact information below to discuss if this can be included in future iterations of the workflow.

## Creating a project
Projects are not created in GitHub directly. Instead, project creation is triggered from DataMad. 

Create a project by claiming a new grant in DataMad and clicking `Create GitHub issue`. This will create a `Project` issue auto-populated with the grant metadata stored in DataMad.

## Creating a dataset
Unlike projects, datasets are created in GitHub directly.

In GitHub terminology, `Dataset` issues are **sub-issues** which sit within corresponding `Project` **parent issues**. This simply means that one `Project` issue can be used to group multiple related `Dataset` issues.

Create a dataset by first opening the `Project` issue you need to add datasets to. Scroll down to the bottom of the issue body and click `Create sub-issue`. This button sits just before the issue's activity feed. Click `Dataset (NERC grant)` and add the following information:

- Title, formatted as 'NERC ID: Working dataset title'
- Any initial notes about the dataset (e.g. 'Model output, estimated ~30GB volume')

Click `Create`.

Check the `Create more sub-issues` checkbox to create multiple sub-issues without leaving the dialog.

Once a sub-issue has been created, an automated script will run which: 

- Assigns the sub-issue creator
- Auto-populates the metadata fields with information from the parent `Project`
- Assigns the `Dataset` project type
- Sets the status to `Pre-delivery comms`

## Linking to other tools (e.g. DataMad, Help Scout, DSW, MOLES)


## Task checklists


## Metadata fields


## Reminders


