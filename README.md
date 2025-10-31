# Jira

## Get started quickly with Jira
- Atlassian product
- Jira is project management software more like a TODO list for team Members

- A `Work item` is the fundamental building block of any Jira Project

- A `project` is a collection of related work items. In Jira, every work item belongs to a project.
    - `Project keys`are short versions of the project name that identify the work items in that project. 

- A `board` is a visualization of the work in a project.
    - The work moves through three statuses, ***To Do, In Progress, and Done***. 
    - Types of boards in Jira:
        - `Kanban boards` support a continuous flow of work.
        - `Scrum boards` track groups of work items that the team completes during a fixed period of time

| Feature         | **Kanban Board**| **Scrum Board**  |
| --------------- | --------------- | ---------------- |
| **Work Flow**   | Continuous – work items move in and out anytime | Time-boxed – work happens in fixed-length sprints    |
| **Focus**       | Continuous delivery and flow efficiency         | Delivering a set amount of work per sprint           |
| **Planning**    | Ongoing, as needed                              | Planned at the start of each sprint                  |
| **When to Use** | When priorities change frequently               | When you work in structured, sprint-based iterations |

---

<div style="text-align: center;"><img src="images/worktypes.png" width="1000" height="500" style="border-radius: 15px;"></div>

- Work Types
    - `Epic` **(Parent *work items*)** : An epic represents a large body of work that can break down into smaller chunks.
    - `Story` : a deliverable from the user's perspective, non-technical description of work item
    - `Task` : a detailed description of a work item
    - `Bug` : a problem or error. 
    - `SubTask`: the smallest piece of work


- Work Item fields:
    - Work item key (unique identifier auto gen): project key + sequential number
    - Summary & Description
    - Labels
    - Due Date
    - Assignee and Reporter: 
        - The **assignee** is the person assigned to work on the work item. The **reporter** is the person who created the work item. 
        - **Only one user** can be in each field; you can’t have multiple assignees or reporters for a single work item.
        
## Track your work effectively in Jira

- **Add attachments** to work items like png, link, etc..
- View work item **history**
- **Link** work items
- relationship between work items
    - Relates to
    - Depends on / is depended on by
    - Blocks / is blocked by
    - Clones / is cloned by
- Move work items
    - Change Work Item Type
    - Move SubTask to other parents
    - Move work to other project
- `List View`: edit items in place  
    - Also used for bulk actions

### Search to find information in Jira
- Types
    - Search Bar
    - Basic 
    - Advanced
- You can only use basic search to find work items, not projects or boards. If you want to find a project or board, the search bar can help

- Basic
    - Go to basic search
    - Enter a keyword
    - Set criteria
    - Sort your results
- Advanced JQL

### Schedule work with the Timeline and Calendar views in Jira
- provide two views
    - Timeline view (Manage Dependency)
    - Calendar view

## Personalize how you work in Jira

- A `dashboard `is a customized screen to give you a high-level snapshot of everything happening in Jira.
- Dashboards are made up of small, configurable blocks called `gadgets`.

- We can use shortcuts & Commands to navigate and edit work items 


## Jira Admin

### Roles:
- organization admin (Manage sites)
    - only individuals who can manage users, groups, and product access
    - An org admin performs their tasks within the Atlassian Admin Hub 
- Product admin == Jira admin   
    - Configure product settings
    - Create Project & Project Roles
    - Assign global permissions
- Project admin  (Depend on the type of the project)
    - company-managed: adding users and groups to project roles. These work with the project permission scheme
    -  team-managed: Create their own custom roles & adding users and groups to project roles & manage their own custom fields
- site administrator 
    - Manage billing & Manage products and app.

### Best Practice

- Best Practice:
    - Persist Project Key
    - Reuse other configurations: Use Schema 
    - Test in a sandbox
    - Create role-specific dashboards 
- Steps to implement Jira:
    - Discover and understand business requirements.
    - Map requirements to Jira configurations.
    - Implement in Jira.

### Project  
- `Project type`: (who can configure your project and if those configurations are shared)
    - ***Team-managed*** projects (Flexible & Less Restrictive )
    - ***Company-managed*** projects (Use Schema )

- `Project Template`: ( provides pre-configurations for your project, like work types and workflows.)
- four commonly Software project templates: 
    - kanban (work-in-progress limits)
    - scrum (work in sprints)
    - bug tracking ( reported bugs, suggested improvements)
    - top-level planning. (helps team or organization leads visualize and track large initiatives)


- `Schemes`:
    - collections of configurations can be reusable 
    - Six schemes are always included in company-managed projects:
        - Work type scheme
        - Permission scheme
        - Notification scheme
        - Field configuration scheme
        - Workflow scheme
        - Work type screen scheme
        
<div style="text-align: center;"><img src="images/schema.png" width="600 " height="400" style="border-radius: 15px;"></div>

- `Project roles and permissions`:
    - Permissions add a layer of security
    - Control the content that users can access and the actions they can perform.

- `Global permissions` control system-wide functionality across all of Jira and Jira Service Management.
    - Jira system administrators
    - Jira administrators
    - Jira users
    - Browse users
    - Make bulk changes

- `Project permissions` control functionality in a project for users, groups, or project roles.
    - Company-managed project permissions (permission schemes)
        - Standalone permissions (control a single piece of functionality)
        - Interrelated permissions (will not have any effect unless combined with other permissions)
        - Permissions that need to meet global prerequisites in order to have an effect

- Configure internal project access
    - Permissions are different from internal project access. Internal project access determines how users outside of your project can interact with your project. 
    - Types:
        - Private (no external access or view )
        - Limited (no External access but view)
        - Open (External access & View)

NOTE: 
In order to make your permissions and roles really effective you have to set the Internal project access to one of two private or Omited





# APC
- Access, permissions, and security: 25%-30%
- Issue types, fields, and screens: 15%-20%
- Workflows and automation: 15%-20%
- General project configuration: 10%-15%
- Advanced user features: 10%-15%
- Notifications: 5%-10%
- System administration: 5%-10%

## Intro
- **Atlassian organization** is top level that **contain sites**
- each **site** represent a city associated with a **domain**
- Each site can have licenses for one or more **Atlassian product**. 


## Implement Jira
- three steps:
    - Discover and understand **business requirements**.
    - **Map** requirements to Jira configurations.
    - **Implement** in Jira.

### Roles:
- organization admin (Manage sites)
    - **only** individuals who can manage users, groups, and product access
    - An org admin performs their tasks within the **Atlassian Admin Hub** 
- Product admin == `Jira admin`   
    - Configure product settings
    - Create Project & Project Roles
    - Assign global permissions
- Project admin  (Depend on the type of the project)
    - **company-managed**: adding users and groups to project roles. These work with the project permission scheme
    -  **team-managed**: Create their own custom roles & adding users and groups to project roles & manage their own custom fields
- site administrator 
    - Manage billing & Manage products and app.

## Project in Jira
- `Project type`: (who can configure your project and if those configurations are shared)
    - ***Team-managed*** projects (Flexible & Less Restrictive )
    - ***Company-managed*** projects (Use Schema )

- `Project Template`: ( provides pre-configurations for your project, like work types and workflows.)
- four commonly Software project templates: 
    - kanban (work-in-progress limits)
    - scrum (work in sprints)
    - bug tracking ( reported bugs, suggested improvements)
    - top-level planning. (helps team or organization leads visualize and track large initiatives)


- `Schemes`:
    - collections of configurations can be reusable 
    - Six schemes are always included in company-managed projects:
        - Work type scheme
        - Permission scheme
        - Notification scheme
        - Field configuration scheme
        - Workflow scheme
        - Work type screen scheme

- Only Jira admins can create and modify schemes and associate them with projects.

<div style="text-align: center;"><img src="images/schema.png" width="600 " height="400" style="border-radius: 15px;"></div>


# Advanced Topics

## Connect to Data Center instances with application tunnels
<div style="text-align: center;"><img src="images/apptunnels.png" width="1000" height="500" style="border-radius: 15px;"></div>

- we can use app linking to link apps to each other, we need to create application tunnels
- `Application tunnels` provide a secure pathway between your Atlassian cloud organization and Data Center instances that live in your network. 
    - Tunnel server: You access it from admin.atlassian.com where you create a tunnel.
    - Tunnel client: Installed as a Marketplace app in your Data Center instance.
    - Application link (cloud): You create a tunneled application link in each of your Atlassian cloud apps and point it at an existing tunnel. You can link multiple cloud apps to a single tunnel. The application link must always be created on the cloud side.
    - Application link (self-managed): The reciprocal link will be automatically created in your Data Center instance. Only incoming connections to your network use the tunnel, the outgoing ones will reach your Atlassian cloud apps directly.


## Audit
- we can audit from:
    - (Jira -> System -> Audit Logs)
    - (ِAdmin -> Security -> Audit Logs)

## Restore & system backup
- We create a backup and download it (option to include media)
- We then can restore by  import it in jira
- Only Org admin can import backup files.
- We can Import work using ` External System Import `   
    - You can import data from a CSV, JSON, or Trello file


# Secondary Topics
## Customize Jira Experience
- Change Default Dashboard
- Change App Logo & Name 
- Change User Default preference
- Change Color & fell

## Some important settings 
- Configure attachment settings
    - limit the attachment size and enable ZIP support
- Configure work linking
    - enable the feature
- Create application links
- Time tracking in Jira
- Audit Track
    - audit log tracks key activities and configuration changes not everything
    - actions that impact users and projects
    - doesn’t track work item updates or pages

## Integrate Jira with a repository





# ***`Access & Permissions & Security` 28%***
- There are 3 Levels of permissions in Jira
    - Product 
    - Project/Space 
    - Work Item (Issue)

## 0. Organization Level
- Manage Organizations at whole
- Manage User/Groups
- Manage Product access 

- There are three options for the organization admin to assign to a user 
    - User  (Normal User for App)
    - User access Admin (User but for Org Admin Atlassian)
    - Administrator (Admin for App)
    - site admin (Manage site users & )


## 1. Product Level 
- Jira admins Manage Global permissions
- Manage the instance permissions 

### Global Permissions
- `Global permissions` control system-wide functionality across all of Jira and Jira Service Management.
    - Administer Jira
    - Browse users and groups
    - Share dashboards and filters
    - Manage group filter subscriptions
    - Make bulk changes
    - Create team-managed projects

- Only Jira admins can modify global permissions.

#### Steps
- Navigate to (Settings -> Global Permissions)
- Edit permissions or Grant a permission to a Group

## 2. Project/Space Level
- Manage user access to project 
- Project-level functionality
- Project permissions are managed in two ways:
    - `Project admins` manage project permissions for ***team-managed projects*** through *custom roles*.
    - `Jira admins` manage project permissions for ***company-managed projects*** through *permission schemes*. 

### Team managed Project
- ***`NOTES on Team Managed Project Access & Permissions`***
- `Team-Managed project` is based on ***roles and access levels***
- Internal project access sets the visibility boundary of the project.
- Inside that boundary, roles (Administrator / Member / Viewer) define what each person can do.

#### Steps
> - ***Find Here:*** Project Settings -> Access
- We will have default three roles 
    - Administrator (Read, Write & Delete)
    - Member (Read & Write)
    - Viewer (Read)
- We can manage roles (Create, Delete, Modify)
- We can add people to this project and assign roles to them 
- First we need to define Internal Project access Mode:
    - Private (no external access or view )
    - Limited (no External access but view)
    - Open (External access & View)
- This mode give the user roles the actual effect.

### Company Manged Project
- ***`NOTES on Company Managed Project Access & Permissions`***
- Group/User assigned to a Project Role
- Project Role is grated certain permission according to permission scheme
- Project Use the custom permission scheme
- permission scheme contain:
    - Permissions 
    - Granted to (Group, Project Role, User, any Logged in)
- Jira admins manage project permissions for ***company-managed projects*** through permission schemes.
    - categorized :
        - Standalone permissions (control a single piece of functionality)
        - Interrelated permissions (will not have any effect unless combined with other permissions)
        - Permissions that need to meet global prerequisites in order to have an effect

#### Steps
- We need org admin to create users and groups
- For reusability and scalability we use **groups** 
- Step One: Create Groups (departments)
- Step Two: Create Project Roles (Admin, Dev, User)
- Step Three: Create Permission Scheme (By grant permission to Group/User/`Role`)
- Step Four: Change the Project Permission scheme to the created one
- Step Five: add People (Users/Groups) and assign to them Project Roles

## 3. Work item security permissions
### Team Managed Projects
- `Work restrictions` control which project roles can view newly created work items of that type

### Company Managed Projects
- `Work item-level` security specifies which users, groups, and project roles can see work
- We use this security level when we need to make some work items closed from some users or to some users
- it more like restricting view and access on the level of work items.

- It use `Work item security schemes` & `Security Level`
- Work item security scheme contain security levels which define who can view a work item

- Subtasks inherit their parent work item’s security level.
- Use Cases:
    - Only the user in a specific field (like Reporter) to be able see that work item.
    - Only a defined list of people to see certain work items.
    - Only certain users to see work items so other project members don’t see clutter.
    - Only certain users to see newly created work.

- Steps:
    - Create Work item security scheme
    - Create Security levels inside of the scheme
    - Assign user/groups/roles to each level
    - Add the Security Level field to work items
    - We then make our project use this work item security scheme `forgettable`

#### Troubleshoot Work Item security
- We Consider:
    - Work item scheme & its security level
    - which group/user/role assigned to which level
    - the visibility of issue security level field
    - the permission in permissions scheme grated to user/role/group (view issue/edit issue & issue security)
    - 
- Note on the `visibility` of Work item security scheme
    - Ensure the project’s screen schemes include the Security Level field for the necessary work types in the right place.
    - Ensure the project’s field configuration schemes show the Security Level field for the necessary screens and apply to the necessary work types.
    - Ensure the project’s layout for work items doesn’t hide the Security Level field when it’s empty.



## Notes on Permissions
- Avoid using Public with most global permissions. Instead, use project permissions to control the access of anonymous users.
- The Jira `Permission Helper` can help you understand a user's permissions. You can check a specific permission for a specific user, and even specify a work item key.

- Permissions is additive

- Project Role VS Groups
    - Solving a problem of choosing which to use project role or Groups to give certain permission
    - Project Roles are project based VS Groups are for the whole instance.
    - If Users need a permission by default in all projects attached to that permission scheme, then I would use groups
    - If the users/groups differ per project, then use project roles.
    - note that you can also add groups to a project role.

<div style="text-align: center;"><img src="images/Project Roles.jpeg" width="400" height="450" style="border-radius: 15px;"></div>

# ***`Workflows and Automation` 14%***

## Workflows
- In every project we have work items that go through status from to do to complete.
- The path that your work items take is called a `workflow`.
- Each Jira workflow components
    - ***Statuses***: represents the state of a work item at a particular point in the workflow
    - ***Transitions***: represents the state of a work item at a particular point in the workflow
        - one-way Transitions 
        - Global transitions: move a work item from any status to that status vice versa
    - ***Resolution***: provides more detail when users close a work item. (why this item closed)
        - The Resolution field is only available in company-managed projects.
- There are default workflows based on the project 
- There is `simplified workflow` (scrum/kanban) 
    - uses global transitions 
    - no transition screens, and has no conditions applied to its transitions
- `Custom workflows` used for complex requirements
    - use transitions, conditions, user input validation, or automated functions

### Complex Workflow 
#### Triggers
- `Triggers` automatically transition work when certain events occur in your ***development tools***
- `Notes`: When a transition triggers automatically, it ignores any transition rules, or permissions configured on 
the transition. However, they still apply when a user manually transitions the work item.

#### Rules
- Restrict transition (conditions):
    - Criteria that the workflow must meet before it can transition a work item.
    - If a user does not meet the condition, they won’t even see the button on the issue screen.

- Validate details
    - Check that any input given during the transition is valid before it transitions the work item.
    - Check that required conditions are true after the user clicks the transition, but before it executes.

- Perform action
    - perform actions after a transition executes

#### Properties
- are key-value pairs that can be used to further customize transitions.
- Use properties to configure more detailed behaviors for your workflows.
- Workflows commonly use properties to further restrict permissions beyond a company-managed project’s permission scheme.

### Configure company-managed workflows

- `Workflow scheme`:
    - act as container of work item types workflows
    - ex: workflow for tasks/epics, another workflow for story
- `Workflow` (where you define the workflow and rules)

- `STEPS`:
    - Create Workflow Scheme 
    - Create workflow 
    - In workflow create:
        - Status 
        - Transitions (flow between status)
        - Restrict, Validate, Perform action for Transition rules
        - Use Triggers/ Properties in status 
        - Publish the workflow
        - Use it in Project
        - assign it to work type 

- Best practice:
    - use a transition rule to set resolutions automatically
    - > Never rename a statues like `To Do` will change to all Jire product

### Configure team-managed workflows
- Team-managed projects support most of the same workflow configurations as company-managed projects. But, you can’t:
    - Use the same workflow for multiple work types
    - Use transition screens
    - Use resolutions

- Steps:
    - Space Settings -> Work Type -> chose any work type -> edit workflow

## Automation


