# Jira

- Add the definitions of ready and done to shortlinks (pointing to github wiki pages of the project);
- Use 2 SCRUM dasboards: 1 for dailies and 1 for regural use

- Columns:
  - Todo: ready, ...
  - In Progress: in progress
  - Done: internal review, customer review, done, closed, waiting depl

- Estimation:
  - statistic: story points
  - time tracking: remaining estimate and time spent

- daily board quick filters:
  - for each developper: (assignee was devid AND status changed from "In Progress") or (assignee = devid)
  - To Do: statusCategory = "To Do" AND assignee is EMPTY
  - Initially planned for the sprint: labels in ("planned")
  - Not Planned initially: (labels not in ("planned") or labels = EMPTY) and type != Sub-task 
  - Urgent: summary ~ 'prod' or summary ~ 'nextprod'
