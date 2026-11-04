---
layout: default
title: How to Add a Calendar Task
---

# The "Add Task" Option
The text below is from Lab 2 Section 3 as a placeholder. For Lab 4, we must express these requirements in a more "User Manual"-like wording.

A Task Management form for creating tasks will be displayed. 

The system shall provide the capability to specify the following properties for a new task:
- Task name
- Optional task description of up to 300 ASCII characters
- Task priority
- Task start time
- Task end time
- Task nonnegotiable status

The system shall validate each inputted task property for the following criteria before a task is added or edited:
- The task name contains valid text.
- The task description contains valid text or no text.
- The task priority matches a valid predefined priority level.
- The task start time is a valid time.
- The task end time is a valid time.
- The task start time comes before the task end time.
- The Scheduler specified a valid task nonnegotiable status

# Screenshots
May not be necessary, but listed here in case we need it.

# Navigation
[Return to Homepage](../) &nbsp; &nbsp; &nbsp; [Return to Table of Contents](../processes/task-management.html) &nbsp; &nbsp; &nbsp; [[<- Previous Page]](../interfaces/task-management-gui.html) &nbsp; &nbsp; &nbsp; [[-> Next Page]](edit-task.md)