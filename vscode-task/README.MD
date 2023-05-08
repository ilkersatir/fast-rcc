# "create react component" task

## Description

This is a Visual Studio Code task that creates a React component file structure in the specified directory. It creates a directory with the given component name, and inside that directory it creates five files: `index.ts`, `[componentName].tsx`, `[componentName].styles.tsx`, `[componentName].styles.scss`, and `[componentName].test.tsx`.

The `[componentName].tsx` file includes the basic structure of a React functional component, and the `[componentName].styles.scss` file includes a basic CSS class for the component. The `[componentName].test.tsx` file includes a basic test using the `@testing-library/react` library. All files are created with initial content, and the `index.ts` file includes an export statement for the component.

## Usage

To use this task, open the Command Palette in Visual Studio Code (`Ctrl+Shift+P` or `Cmd+Shift+P`) and search for "Tasks: Manage Tasks". Choose "Configure Tasks" and select "create react component" from the list. The task can be run using the shortcut `Alt+N` or by selecting "Run Task" from the Command Palette.

## Inputs

- `componentName`: The name of the component to be created.
- `dirPath`: The path to the directory where the component should be created.

## Installation

To use this task in your React project, copy the task configuration and key-binding into your project's `.vscode/tasks.json` and `keybindings.json` files, respectively. Alternatively, copy these files into your global VS Code configuration folder at `C:\Users\UserName\AppData\Roaming\Code\User` to use it globally for all projects.
