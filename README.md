# ToDoApp
This is a React Native task list application that uses useState to manage state. The application displays a list of tasks that can be checked off as completed, edited, and deleted. The user can add a new task to the list and include a description for the task. The UI also includes a toggle switch to change between light and dark mode.

The application starts with a pre-defined set of tasks in the tasks state. When a user completes a task, it will be marked as completed by updating the completed property of the corresponding task in the tasks array. When a user deletes a task, it will be removed from the tasks array using the filter() method. When a user edits a task, the editingTask state will be set to the ID of the task being edited, and the new task information will be saved in the newTaskTitle and newTaskDescription states. Once the edit is complete, the task information will be updated in the tasks array.

The application renders a FlatList component that displays each task. Each task is represented by a ListItem component that includes a Checkbox to mark a task as completed, a FontAwesome component to edit a task, and another FontAwesome component to delete a task. The ListItem component also includes the title and description of the task.

The application also includes an Input component that allows the user to add a new task to the list, and a TouchableOpacity component that expands the input for the task description when clicked. Finally, the UI includes a Switch component to toggle between light and dark mode.

