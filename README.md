# E-0923 React Lab Day 3 (Zustand)

Goal: Recreate the todo app from the demo video [here](https://drive.google.com/file/d/1Si4WeBPN6VkHaRy3HALL-YzBo6h3aRmz/view?usp=sharing)

## Instructions

1. Accept the assignment and create a `dev` branch.
2. Clone the repository and switch to the `dev` branch using `git switch dev`.
3. Create a new React project:
   - Run `npx create-vite@latest zustand-lab --template react`.
   - Navigate to the project directory with `cd zustand-lab`.
   - Install the node packages with `npm install`.
4. Install Zustand by running `npm install zustand`.
5. Recreate the provided demo video by creating a Zustand store which will manage these states:
   - `todos` (array): Each todo in the array is an object with `id` and `text` properties.
   - `addTodo` (function)
   - `editTodo` (function)
   - `deleteTodo` (function)
6. The design doesn't have to match the demo as long as the functionality is there.
7. When you're done, push your changes, create a PR from `dev` to `master` and merge.
