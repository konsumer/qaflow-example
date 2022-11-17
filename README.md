This is an exmaple project to setup workflows for QA.

It should automate managing [the project-board](https://github.com/users/konsumer/projects/1)

Worklflow:

- Add a new issue, it will be added to `🆕 New` automatically, don't assign unless you are working on it
- Assign an issue, it will move to `🏗 In progress`
- When it's ready for QA, move to `👀 In review` (todo: automate closed issues go here, re-oppend issues go to `🏗 In progress`)
- When QA is complete, move it to `✅ Done`