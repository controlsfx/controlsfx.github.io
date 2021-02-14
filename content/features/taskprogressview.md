---
title: TaskProgressView
---
# TaskProgressView

The task progress view is used to visualize the progress of long-running tasks.
These tasks are created via the [`Task`](https://openjfx.io/javadoc/11/javafx.graphics/javafx/concurrent/Task.html "class or interface in javafx.concurrent") class.
This view manages a list of such tasks and displays each one of them with their name, progress, and update messages.

An optional graphic factory can be set to place a graphic in each row. This allows the user to more easily distinguish between different types of tasks.

![task-monitor](/images/features/task-monitor.png "TaskProgressView")
