---
status: pending
title: Simple Todo App
---

1. Set up the base styling in /app/src/styles/global.css so it starts with the Tailwind import, and confirm it is imported once in /app/src/main.tsx.
   - Expected outcome: Tailwind styling is available across the app.

2. Create a shared type for a todo item in /app/src/types/todo.ts describing an id, the task text, and whether it is completed.
   - Expected outcome: A consistent shape for todo items used throughout the app.

3. Create a custom hook in /app/src/hooks/useTodos.ts that holds the list of todos and exposes actions to add a new todo, toggle a todo's completed state, and remove a todo. Persist the list in the browser so it survives page refreshes.
   - Expected outcome: Todo data and actions are managed in one place and remembered between visits.

4. Create an input component in /app/src/components/TodoInput.tsx with a text field and an add button that submits a new task and clears the field.
   - Expected outcome: Users can type a task and add it to the list.

5. Create a single todo row component in /app/src/components/TodoItem.tsx showing a checkbox to mark complete (with a strike-through style when done), the task text, and a delete button.
   - Expected outcome: Each task can be checked off or removed, with clear visual feedback.

6. Create a list component in /app/src/components/TodoList.tsx that renders all todo rows and shows a friendly empty-state message when there are no tasks.
   - Expected outcome: All tasks display neatly, and users see guidance when the list is empty.

7. Create the main page in /app/src/pages/HomePage.tsx that combines a title, a count of remaining tasks, the input, and the list into a centered, card-style layout.
   - Expected outcome: A polished, single-screen todo experience.

8. Wire the home page into the app entry in /app/src/App.tsx so it renders on load.
   - Expected outcome: The todo app appears immediately when the app opens.
