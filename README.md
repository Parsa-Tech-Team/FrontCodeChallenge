# Parsa frontend coding task
The goal is to implement an application to manage working tasks. See the __[user stories](#user-stories)__ for the application details to be implemented.

Send a zip file to us (https://parsa.tech.team@gmail.com) when you finished the task.

# User stories
* As a user I can create tasks, so that all tasks for a project can be tracked.
  * Acceptance Criteria:
  * A task must have a title
  * A task must have a long description
  * A task must have the status "ToDo"
* As a user I can change the status of a Task, so that the progress of the project can be tracked.
  * Acceptance Criteria:
  * Only the following status transitions are allowed, see __[state transitions](#state-transitions)__
* As a user I can change the title and long description of a task.

![Diagram](https://plantuml.gitlab-static.net/png/U9nLZi4AmZ0GHE_x5NiM2le31QKNRmhUn4E8YorDCc6J7lht9bLflGmx-vZPJTOuuSEUqZY4QDHuTaEGF4TXQEwn0Hu1jbTuuQoJ4Drt3swQbc_eG5ILYpk7Y-AbaXAj8pTJBEpaO4Tv_e6Qk1wfojhsSIrt249L5YFHOIxnRytc-0yjg_8NlG7BYaJz)

So for example:
- If a task is currently at "toDo" state in can only be changed to "InProgress"
- If a task is currently at "inQA" state in can only be both changed to "Done" or "ToDo"

## Tech Stack
* Implement the app using React.
  * [typescript](https://www.typescriptlang.org/) is required
* Please stick with React's internal APIs to handle state management (React Context API)
* Prefer function components and hooks over class components
* The application must be primary optimized for mobile devices and must have a optimized layout for desktop.

* It's mandatory to use SVG icons and not PNG images. Icons used in designs can be easily found on flaticon.com


## UI Designs
1. https://ibb.co/N3MWQds
2. https://ibb.co/cX7bp6J
3. https://ibb.co/YNfRbZc
4. https://ibb.co/fChqF46
