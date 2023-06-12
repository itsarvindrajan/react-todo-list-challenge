# Create a TODO List App

## User Stories

**01: Add/Create a new task**

If you click the add modal button, the add modal will pop up, where you will add a new task in input and select a priority (low, medium, high). Here’s what you should do while creating a new task:

1. After clicking add task button, the task will be added to the UI.
2. By default, the new task status will be "To Do," and progress will be 0 (empty).
3. Each task will have a unique "Id."
4. User can not add an empty task (or task with empty spaces), and If task input is empty, add or edit button will be disabled.
5. Newly added tasks will appear on top of all tasks.
6. Selected task priority button will look like below the "Add Task Form" image.

[![H4gnMrB.md.png](https://iili.io/H4gnMrB.md.png)](https://freeimage.host/i/H4gnMrB)

**02: Delete a task**

The delete modal will pop up when you click the delete icon. If you click the delete button, the particular task will be deleted from UI, and the modal will close. If you click the cancel button, only the modal will be closed.

[![H4gnG1V.md.png](https://iili.io/H4gnG1V.md.png)](https://freeimage.host/i/H4gnG1V)

**03: Edit/Update a Task**

1. When you click the edit icon, the modal will pop up, with that particular task information filled. Play with the demo app app for better clarity

2. When the user edits the task and presses the Edit button, it will replace that task with a newly added task

3. User can change the task status by clicking the status (To Do, In Progress, Done) button.

   a. If the task status is "Todo", progress will be 0 (empty circular progress).

   b. If the status is "In Progress," circular progress will be 50% (half-filled).

   c. If the status is "Done," the circular progress bar will be completely filled (100%).

[![H4gnEqQ.md.png](https://iili.io/H4gnEqQ.md.png)](https://freeimage.host/i/H4gnEqQ)

## Further Instructions

- Use the same form for add and edit tasks (handle add and edit feature conditionally).
- Write all typescript types.
- Make sure there isn't any error in the console.

## UI and Features Suggestions for TODO List Application (Bonus)

- Once you have completed the challenge, you can move ahead and make it better by adding below features:

  - [ ] Convert the project into a typescript project, if not already.

  - [ ] Build a Nodejs API for it and update it to MERN App

  - [ ] You can turn this one-page task list into a dashboard where users can filter tasks on the basis of status, priority, and tags

  - [ ] You can also add a tag for each task. Eg. project, freelance, grocery, office, etc
