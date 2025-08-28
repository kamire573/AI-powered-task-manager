# AI-powered-task-manager
This is a beginner friendly AI-powered Task manager, using Lit, Bulma and Typescript. It allows users to add tasks, view them on a list and get an AI generated priority suggestions on each task.  
The main aim was to learn Lit Element’s component structure, TypeScript’s type safety, Bulma’s styling, and basic AI integration. 
The main features of the Task manager are to;
Add tasks with a title and description.
Display tasks in a list with AI-suggested priorities (high, low, medium).
Style the app with Bulma for a clean, responsive UI.
Store tasks in localStorage for persistence.
Fetch AI-generated priority suggestions (low, medium, high) for task descriptions.

I did this project because I wanted to learn how to;
Create and compose Lit Element web components.
Use TypeScript for type-safe data handling.
Apply Bulma classes for styling without custom CSS.

This is my project structure 
task-manager/
├── src/
│   ├── components/
│   │   ├── task-form.ts
│   │   ├── task-item.ts
│   │   ├── task-list.ts
│   ├── services/
│   │   ├── task-service.ts
│   ├── types/
│   │   ├── task.ts
│   ├── my-app.ts
├── index.html
├── package.json
|__vite.config.ts
├── tsconfig.json
