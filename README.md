# MyList

A cloud-backed Android task manager built with **Java, Firebase Firestore, RecyclerView, and View Binding**.

MyList supports creating, updating, completing, and deleting tasks through a compact mobile interface, with task data persisted in Firestore.

## Highlights

- Create and edit tasks
- Set task due dates
- Mark tasks as complete
- Persist task data with **Firebase Firestore**
- Display tasks using **RecyclerView**
- Swipe to edit or delete tasks
- Confirm destructive actions before deletion
- Add and edit tasks through a **BottomSheetDialogFragment**
- Keep the UI synchronized with stored task data
- First-launch / onboarding experience
- Splash screen and animated UI elements
- **View Binding** for view access

## Technology

- **Java**
- **Android SDK**
- **XML layouts**
- **Firebase Firestore**
- **AndroidX**
- **RecyclerView**
- **View Binding**
- **Material Components**
- **ItemTouchHelper**

## Task flow

Tasks are stored as Firestore documents containing the task text, due date, completion state, and creation timestamp.

The main task list is backed by a RecyclerView and custom adapter. Users can interact with individual tasks directly:

- check a task to update its completion state
- swipe one direction to edit it
- swipe the other direction to delete it
- use the floating action button to create a new task

## What this project demonstrates

MyList combines Android UI development with cloud persistence and interactive list behavior. It demonstrates CRUD workflows, Firestore integration, RecyclerView adapters, user-input handling, date selection, modal interfaces, and gesture-based interactions in a focused mobile application.

## Project history

Originally built in 2021. I’m revisiting the project to preserve the original work while improving its code quality, structure, and compatibility with modern Android tooling.
