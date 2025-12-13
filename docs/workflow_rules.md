# Workflow Rules

These are the project workflow rules, designed to ensure smooth collaboration, clear task management, and accountability.

## 1. Repository Rules
- **Branch Protection:**  
  The `main` branch is protected.  
  All changes must be made via pull requests to the `dev` branch.

- **Commit History:**  
  All commits must have clear messages that describe the changes made.  
  No committing directly to `main` or `dev` without a pull request.

- **Branch Naming:**  
  Feature branches must be named according to the work being done (e.g., `feature/model-optimization`, `feature/data-cleaning`).

## 2. Task Rules
- **Task Creation:**  
  All tasks must be added to the **GitHub Project board** (Kanban format). Tasks will be categorized by type (e.g., `ML`, `Embedded`, `Docs`).

- **Task Assignment:**  
  Each task must be assigned to one person, and only **one person** at a time.  
  If the task is too big, it should be broken down into smaller tasks.

- **Task Status:**  
  Tasks must move across columns (e.g., from `Backlog` → `To Do` → `In Progress` → `Review` → `Done`) in the **GitHub Project board**.

- **Task Labels:**  
  Tasks will be labeled based on their category (e.g., `ML`, `Embedded`, `Docs`).  
  The `Blocked` label should be used if work cannot proceed until an issue is resolved.

## 3. Pull Request & Merge Rules
- **Pull Request Creation:**  
  A pull request (PR) must be created for any code or document changes that affect the project repository.  
  PRs must be linked to a task card in the project board.

- **Review Process:**  
  All PRs must be reviewed by the before merging.  
  The PR will not be merged until the review is complete and any requested changes are addressed.

- **Approval Requirement:**  
  PRs must have at least **1 approval** before being merged into `dev` or `main`.

## 4. Communication Rules
- **Meetings:**  
  Weekly progress meetings will be held to review task status, discuss blockers, and plan the next steps.  
  All team members are required to attend.

- **Blockers:**  
  If any team member is blocked from proceeding with their tasks, they must **immediately** notify via GitHub issues or WhatsApp.  
  No task should sit in “In Progress” for more than **1 week** without a solution.

- **Weekly Updates:**  
  Each team member must submit a weekly **status update** in the project repository to keep everyone informed of what has been completed and what will be worked on next.

- **Decisions:**  
  All major decisions regarding project direction, task allocation, and methodology must be discussed with the **Advisor** and logged in the repository for future reference.

## 5. Risk Management
- **Risk Identification:**  
  Risks must be identified early in the project, and solutions must be discussed in the weekly meetings.  
  Risks will be tracked in **GitHub Issues** under the `Risk` label.

## 6. Documentation Rules
- **Docs Location:**  
  All documentation will be stored in the `docs/` folder of the repository. This includes:
  - Project Charter
  - WBS
  - Communication Plan
  - Reports

- **Document Versioning:**  
  Documentation will be updated regularly and versioned through pull requests to ensure that only the most up-to-date version is available.

---

These rules will help us stay organized, manage tasks effectively, and ensure clear communication throughout the project.
