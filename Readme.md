# Early Starter - Individual Project


## Project Description

Early Starter is an individual To-Do web application that helps students organize tasks, set priorities, and track progress.

## Problem Domain

Many students struggle with getting things done on time and keeping track of what work they need to complete. This project focuses on a simple, student-friendly task manager with reminders, due dates, and clear status tracking.

## Features and Requirements

### Features & Requirements

1. User can create tasks with a title, description, due date, and priority.
2. User can edit or delete existing tasks.
3. User can mark tasks as complete or incomplete.
4. User can filter tasks by status (all, active, completed) and priority.
5. User can sort tasks by due date or priority.
6. User can search tasks by keyword.

### Non-Functional Requirements

- Responsive web UI for desktop and mobile.
- Accessible forms and navigation (keyboard-friendly).
- Fast page load and snappy interactions for small to medium task lists.

## Data Model

Task:
- id (string/uuid)
- title (string)
- description (string)
- dueDate (date)
- priority (low/medium/high)
- status (active/completed)
- createdAt (date)
- updatedAt (date)

## Architecture

Single-page web app with a simple client-side data store. Optional persistence can be local storage or a lightweight backend API depending on implementation.

## Tests

### Acceptance Tests

- Create, update, and delete a task.
- Mark a task complete and verify it moves to completed view.
- Filter and search tasks.

  Link:

### Integration Tests

- Task form input validation.
- Data store updates after CRUD actions.

  Link:

### E2E Tests

- Complete user flow: add -> edit -> complete -> filter -> delete.

## Project Documentation

- [Project Plan Presentation (PPP)](link-to-ppp)
- [Individual Contributions](link-to-individual)

## Schedule & Milestones

### Sprint 1

- Define requirements and wireframes.
- Implement task CRUD and basic UI.

### Sprint 2

- Add filters, sorting, and search.
- Improve UI/UX and add tests.
