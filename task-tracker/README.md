# Task Tracker

a command-line task manager, where you can add, update, delete, and list tasks right from your terminal with persistent JSON storage. also you can mark tasks as todo, in-progress or done.

## Installation
```
npm install -g
task-tracker help
```
now you can use `task-tracker` from anywhere in your terminal.

## Task Format

each task is saved in `tasks.json` with this structure:
```
{
    "id": 1,
    "description": "Important Task",
    "status": "todo",
    "createdAt": "2025-06-21T17:53:23.481Z",
    "updatedAt": "2025-06-21T17:53:23.481Z"
}
```

![task tracker preview](https://github.com/trenter39/cli-applications/blob/master/task-tracker/preview.png)