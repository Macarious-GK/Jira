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

<div style="text-align: center;"><img src="images/worktypes.png" width="900 " height="500" style="border-radius: 15px;"></div>

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