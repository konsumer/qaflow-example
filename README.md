This is an exmaple project to setup workflows for QA. It's used to troubleshoot uissues with variaous actions:

- [Warning: There are no target projects.](https://github.com/technote-space/create-project-card-action/issues/121)

It should automate managing [the project-board](https://github.com/users/konsumer/projects/1)

Worklflow:

- Add a new issue, it will be added to `🆕 New` automatically, don't assign unless you are working on it
- Assign an issue, it will move to `🏗 In progress`
- When it's ready for QA, move to `👀 In review` (todo: automate closed issues go here, re-oppend issues go to `🏗 In progress`)
- When QA is complete, move it to `✅ Done`
