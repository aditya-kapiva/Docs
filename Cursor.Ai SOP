# Best Practices for Using Cursor.ai in Daily Development Tasks

## Table of Contents

1. [Core Best Practices](#core-best-practices)
2. [How to Use Cursor.ai Effectively](#how-to-use-cursorai-effectively)
3. [Prompt Engineering for Accurate Answers](#prompt-engineering-for-accurate-answers)
4. [Managing Usage Limits](#managing-usage-limits)
5. [Cursor AI Workflow Specification](#cursor-ai-workflow-specification)
6. [Technology-Specific Rules](#technology-specific-rules)
7. [Productivity Analysis & Business Impact](#productivity-analysis--business-impact)

---

## Core Best Practices

### Use Custom AI Rules

Define project-specific rules in the `.cursorrules` file to guide AI behavior. For example:

- "Always use type hints in Python function definitions."
- "Use React functional components with hooks for UI development."

**Important**: Balance rule restrictiveness to ensure the AI remains flexible while adhering to your coding standards, as overly strict rules may limit output quality.

### Manage Documentation References

In the Features tab of Cursor settings, add references to documentation for lesser-known or private libraries to enable quick access during AI interactions.

### Balance AI and Manual Work

- **Use AI for repetitive tasks**, such as generating boilerplate code or simple UI components, to save time and mental energy.
- **Tackle complex problems manually** to maintain coding skills and problem-solving abilities. For example, use AI to "vibe code" a basic UI for 4 hours and spend 2 hours manually addressing intricate logic.
- **Avoid over-reliance on AI** to ensure you remain proficient in debugging and critical thinking.

### Leverage Context-Aware Features

Use the `@` tagging system to provide context for AI responses:

- `@files`: Reference specific files or folders.
- `@code`: Include existing code snippets.
- `@documentation`: Link to library-specific documentation.
- `@web`: Incorporate web search results.

**Tip**: Break large tasks into smaller prompts to maintain accuracy, especially for extensive codebases.

### Monitor Code Quality

- Use the bug finder feature (`Command+Shift+P`, type "bug finder") to identify potential issues compared to the main branch.
- Review AI-generated code in the diff view (red for deletions, green for additions) to ensure accuracy before applying changes.

---

## How to Use Cursor.ai Effectively

Cursor.ai offers a range of features to streamline development workflows. Below are the key methods to use it effectively:

### Core Features

| Feature                         | Description                                                                | How to Access                                      |
| ------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------- |
| **Inline Code Generation**      | Generate code directly in the editor using natural language prompts.       | `Cmd+K` (MacOS) or `Ctrl+K` (Windows/Linux)        |
| **Interact with Existing Code** | Refactor, rewrite, or edit selected code with AI assistance.               | Select code, then `Cmd+K`                          |
| **Ask Questions About Code**    | Query the AI about your codebase (e.g., "What does this function do?").    | `Cmd+K`, click "quick question"                    |
| **Autocompletion**              | Accept AI-generated code suggestions.                                      | Press `Tab`                                        |
| **Chat Interface**              | Use a chat panel for versatile code generation, debugging, or questions.   | `Cmd+L`                                            |
| **Enhance Query Context**       | Add context to queries using @ tags (e.g., @files, @web, @Docs).           | Include @ tags in prompts                          |
| **Global Codebase Questions**   | Ask questions about the entire project.                                    | Use "codebase" option in chat                      |
| **Image Support**               | Drag images (e.g., error messages, UI designs) into the chat for analysis. | Drag images into chat panel                        |
| **Add Documentation**           | Reference specific documentation with URLs.                                | Use @Docs with URL (e.g., @Docs https://react.dev) |
| **Use Extensions**              | Access over 40,000 VS Code extensions to enhance functionality.            | Via View menu                                      |

### Chat Modes

- **Agent Mode**: Ideal for autonomous tasks, such as generating a to-do app.
- **Manual Mode**: Suitable for targeted edits, like adding a footer.
- **Ask Mode**: Useful for learning about a codebase without making changes.

**Pro Tip**: Create custom modes (e.g., "code-docs" for documentation) with tools like Read File or List Directory.

### Background Agents (Paid Plans)

Use the web app or Slack integration to assign tasks like building sign-up forms or generating pull requests.

---

## Prompt Engineering for Accurate Answers

Crafting effective prompts is essential for obtaining accurate and relevant results from Cursor.ai. Follow these guidelines to optimize your prompts:

### Use Natural Language

Write prompts in plain English, clearly describing the desired outcome. For example:

- "Write a double for loop to iterate over pairs of lists in Javascript."
- "Create a React component for a login form with Tailwind CSS."

### Enhance with Context

Use `@` tags to provide additional context:

- `@files main.js`: Reference a specific file.
- `@code`: Include a code snippet.
- `@documentation https://react.dev`: Link to library documentation.
- `@web "hooks in react js"`: Incorporate web search results.

**Example**: Combine multiple references for comprehensive context, e.g., `@files main.js @web "hooks in react js"`.

### Be Precise

Clearly define the scope to prevent the AI from exceeding your intent. For example:

- Instead of "Fix this code," use "Add error handling to this Python function in server.js."
- Instead of "Write a function," use "Write a TypeScript function to parse JSON with error handling."

### Select AI Models

Use the model dropdown in the inline generator to choose specific LLMs (e.g., Claude-3.5-sonnet) for tailored responses based on task complexity.

#### Daily Driver Models (choose one as your primary):

- **Claude 4 Sonnet**: Best overall for most coding tasks, UI development, debugging
- **Gemini 2.5 Pro**: Best for codebase exploration, planning, multi-step reasoning
- **Auto Mode**: Cost-effective baseline that intelligently routes to appropriate models

#### Specialist Models (use when needed):

- **GPT-5**: Complex features, one-shot solutions, agentic tasks
- **o3**: Breakthrough debugging, unsolvable problems
- **Claude 4 Opus**: System architecture, complex reasoning tasks
- **GPT-4.1**: Documentation, general coding support

### Review Before Applying

- Use the diff view (red for deletions, green for additions) to review AI-generated changes.
- Apply suggestions using the "Apply" button in the chat panel or the "accept" button in the inline generator.

### Set Cursor Rules

Define rules in the `.cursorrules` file to guide AI behavior, such as:

- "Always use type hints in NodeJS."
- "Use React functional components with hooks."

**Important**: Test rules to ensure they don't overly restrict the AI's output.

### Handle Large Codebases

Break tasks into smaller prompts to prevent incomplete or buggy outputs. For example, instead of "Refactor my entire app," use "Refactor the authentication module in auth.js."

### Test Mode Boundaries

Understand the behavior of different modes:

- **Agent Mode**: May generate extensive code autonomously.
- **Manual Mode**: Limits changes to specific edits.
- **Ask Mode**: Provides read-only insights.

Choose the appropriate mode for your task to avoid unexpected results.

---

## Managing Usage Limits

Cursor.ai has limitations, such as restricted AI chat queries (approximately 50 per month) and limited access to advanced features like code refactoring and background agents. To use Cursor.ai conservatively:

### Plan Your Usage

- Prioritize tasks where AI provides significant value, such as generating boilerplate code or debugging simple errors.
- Reserve manual coding for complex tasks to maintain skills and reduce AI query usage.

### Monitor Tier Limits

- Avoid unnecessary queries by planning prompts carefully and combining multiple tasks into a single prompt when possible.

### Avoid Over-Reliance

- Use AI as a helper, not a replacement, to maintain proficiency in debugging and problem-solving.
- Regularly engage in manual coding to ensure long-term skill development.

---

## Cursor AI Workflow Specification

Workflow for using Cursor AI effectively, focusing on maintaining structured project documentation through `PLANNING.md` and `TASK.md` files, and adhering to a modular prompting process for consistent and reliable results.

### 1. PLANNING.md

**Purpose**: `PLANNING.md` serves as the central document for capturing the high-level vision, architecture, constraints, technology stack, tools, and other foundational decisions for the project.

**Content Guidelines**:

- Define the project's overarching goals and objectives.
- Outline the system architecture (e.g., components, data flow, integrations).
- Specify constraints (e.g., performance, scalability, budget).
- List the technology stack (e.g., programming languages, frameworks, libraries).
- Document tools used (e.g., IDEs, version control, CI/CD pipelines).
- Include any other high-level considerations (e.g., security, compliance).

**Prompt to AI**: When starting a new conversation or project, include the following prompt to ensure alignment with the project's foundation:

> "Use the structure and decisions outlined in PLANNING.md."

**Usage**:

- Reference `PLANNING.md` at the beginning of any new conversation with the AI to ensure consistency with the project's vision and constraints.
- Update `PLANNING.md` whenever there are changes to the project's scope, architecture, or tech stack.

### 2. TASK.md

**Purpose**: `TASK.md` tracks active tasks, the project backlog, and sub-tasks, providing a clear view of ongoing work and priorities.

**Content Guidelines**:

- **Active Tasks**: A bullet list of current tasks with descriptions, assignees (if applicable), and status (e.g., In Progress, Blocked, Done).
- **Backlog**: A prioritized list of tasks or features yet to be started.
- **Milestones**: Key project milestones or deadlines.
- **Discoveries**: Any insights, issues, or learnings uncovered during development.
- **Sub-tasks**: Break down complex tasks into smaller, actionable steps.

**Prompt to AI**: To update task status or add new tasks, use prompts like:

> "Update TASK.md to mark XYZ as done and add ABC as a new task."

For automation, configure global rules to allow the AI to update `TASK.md` automatically when tasks are completed or new ones are created.

**Usage**:

- Regularly update `TASK.md` to reflect the current state of the project.
- Use it to track progress and ensure alignment with project goals.
- Review `TASK.md` before assigning new tasks to avoid duplication or conflicts.

### 3. Modular Prompting Process

To achieve consistent and reliable outputs from the AI, follow a modular prompting approach, especially for follow-up fixes or changes to the project.

**Key Principles**:

- **Single-Task Focus**: Provide one task at a time unless the tasks are very simple. This ensures the AI focuses on a specific change, reducing errors and improving output quality.
  - **Good Example**: "Now update the list records function to add a parameter for filtering the records."
  - **Bad Example**: "Update list records to add filtering. Then I'm getting an error for the create row function that says API key not found. Plus I need to add better documentation to the main function and in README.md for how to use this server."
- **Single-File Updates**: Whenever possible, instruct the AI to update only one file per task to maintain clarity and avoid unintended changes.
- **Documentation Updates**: After any change, ensure the AI updates `README.md`, `PLANNING.md`, and `TASK.md` to reflect the modifications:
  - `README.md`: Update usage instructions, examples, or setup details as needed.
  - `PLANNING.md`: Revise if the change impacts the project's vision, architecture, or tech stack.
  - `TASK.md`: Mark completed tasks, add new tasks, or document discoveries.

**Prompting Best Practices**:

- Be specific and clear in prompts, avoiding vague or multi-part requests.
- Reference the relevant file or section explicitly (e.g., "Update the list_records function in src/main.js").
- If errors occur, address them one at a time with targeted prompts.
- Use iterative prompting to refine outputs, breaking complex tasks into smaller steps.

### 4. Workflow Summary

1. **Start with PLANNING.md**: Ensure every new conversation references `PLANNING.md` to align with the project's vision and constraints.
2. **Track Tasks in TASK.md**: Use `TASK.md` to manage active tasks, backlog, and milestones. Update it regularly via specific prompts or automated rules.
3. **Use Modular Prompts**: Focus on one task and one file per prompt to ensure consistent and accurate AI outputs.
4. **Update Documentation**: After every change, update `README.md`, `PLANNING.md`, and `TASK.md` to keep documentation current and comprehensive.
5. **Iterate and Refine**: Break complex tasks into smaller, manageable prompts, and address issues one at a time for optimal results.

By following this workflow, you can leverage Cursor AI to maintain a well-organized project, ensure consistent outputs, and streamline development and documentation processes.

---

## Technology-Specific Rules

### Flutter Rules

#### 1. flutter-core-rules.mdc

**Description**: Applies Flutter best practices and coding guidelines to the core directory, focusing on constants, themes, utilities, and widgets.
**Globs**: `lib/core/**/*.*`

**Guidelines**:

- Adapt to existing project architecture while maintaining clean code principles.
- Use Flutter 3.x features and Material 3 design.
- Implement proper null safety practices.
- Follow proper naming conventions.
- Use proper widget composition.
- Keep widgets small and focused.
- Use const constructors when possible.
- Implement proper widget keys.
- Follow proper layout principles.

#### 2. flutter-feature-rules.mdc

**Description**: Enforces clean architecture, BLoC pattern, and state management principles within Flutter feature modules.
**Globs**: `lib/features/**/*.*`

**Guidelines**:

- Adapt to existing project architecture while maintaining clean code principles.
- Use Flutter 3.x features and Material 3 design.
- Implement clean architecture with BLoC pattern.
- Follow proper state management principles.
- Use proper dependency injection.
- Implement proper error handling.
- Follow proper state management with BLoC.
- Implement proper dependency injection using GetIt.

#### 3. flutter-general-best-practices.mdc

**Description**: Applies general Flutter best practices across the entire project, focusing on architecture, design, and code quality.
**Globs**: `lib/**/*.*`

**Guidelines**:

- Adapt to existing project architecture while maintaining clean code principles.
- Use Flutter 3.x features and Material 3 design.
- Implement clean architecture with BLoC pattern.
- Follow proper state management principles.
- Use proper dependency injection.
- Implement proper error handling.
- Follow platform-specific design guidelines.
- Use proper localization techniques.

#### 4. flutter-performance-rules.mdc

**Description**: Provides performance-related guidelines for Flutter development, including image caching, list view optimization, and memory management.
**Globs**: `lib/**/*.*`

**Guidelines**:

- Use proper image caching.
- Implement proper list view optimization.
- Use proper build methods optimization.
- Follow proper state management patterns.
- Implement proper memory management.
- Use proper platform channels when needed.
- Follow proper compilation optimization techniques.

#### 5. flutter-presentation-rules.mdc

**Description**: Focuses on UI-related rules within Flutter feature's presentation layer, including BLoC, pages, and widgets.
**Globs**: `lib/features/**/presentation/**/*.*`

**Guidelines**:

- Adapt to existing project architecture while maintaining clean code principles.
- Use Flutter 3.x features and Material 3 design.
- Follow proper widget composition.
- Keep widgets small and focused.
- Implement proper routing using GoRouter.
- Use proper form validation.
- Implement proper error boundaries.
- Follow proper accessibility guidelines.

### Next.js Rules

**Description**: Next.js with TypeScript and Tailwind UI best practices
**Globs**: `**/*.tsx`, `**/*.ts`, `src/**/*.ts`, `src/**/*.tsx`

**Project Structure**

- Use the App Router directory structure
- Place components in `app` directory for route-specific components
- Place shared components in `components` directory
- Place utilities and helpers in `lib` directory
- Use lowercase with dashes for directories (e.g., `components/auth-wizard`)

**Components**

- Use Server Components by default
- Mark client components explicitly with 'use client'
- Wrap client components in Suspense with fallback
- Use dynamic loading for non-critical components
- Implement proper error boundaries
- Place static content and interfaces at file end

**Performance**

- Optimize images: Use WebP format, size data, lazy loading
- Minimize use of 'useEffect' and 'setState'
- Favor Server Components (RSC) where possible
- Use dynamic loading for non-critical components
- Implement proper caching strategies

**Data Fetching**

- Use Server Components for data fetching when possible
- Implement proper error handling for data fetching
- Use appropriate caching strategies
- Handle loading and error states appropriately

**Routing**

- Use the App Router conventions
- Implement proper loading and error states for routes
- Use dynamic routes appropriately
- Handle parallel routes when needed

**Forms and Validation**

- Use Zod for form validation
- Implement proper server-side validation
- Handle form errors appropriately
- Show loading states during form submission

**State Management**

- Minimize client-side state
- Use React Context sparingly
- Prefer server state when possible
- Implement proper loading states

### Node.js & Express.js Rules

**Description**: Node.js and Express.js best practices for backend development
**Globs**: `**/*.js`, `**/*.ts`, `src/**/*.ts`

**Project Structure**

- Use proper directory structure
- Implement proper module organization
- Use proper middleware organization
- Keep routes organized by domain
- Implement proper error handling
- Use proper configuration management

**Express Setup**

- Use proper middleware setup
- Implement proper routing
- Use proper error handling
- Configure proper security middleware
- Implement proper validation
- Use proper static file serving

**API Design**

- Use proper REST principles
- Implement proper versioning
- Use proper request validation
- Handle errors properly
- Implement proper response formats
- Document APIs properly

**Database Integration**

- Use proper ORM/ODM
- Implement proper migrations
- Use proper connection pooling
- Implement proper transactions
- Use proper query optimization
- Handle database errors properly

**Authentication**

- Implement proper JWT handling
- Use proper password hashing
- Implement proper session management
- Use proper OAuth integration
- Implement proper role-based access
- Handle auth errors properly

**Security**

- Use proper CORS setup
- Implement proper rate limiting
- Use proper security headers
- Implement proper input validation
- Use proper encryption
- Handle security vulnerabilities

**Performance**

- Use proper caching
- Implement proper async operations
- Use proper connection pooling
- Implement proper logging
- Use proper monitoring
- Handle high traffic properly

**Testing**

- Write proper unit tests
- Implement proper integration tests
- Use proper test runners
- Implement proper mocking
- Test error scenarios
- Use proper test coverage

**Deployment**

- Use proper Docker setup
- Implement proper CI/CD
- Use proper environment variables
- Configure proper logging
- Implement proper monitoring
- Handle deployment errors

**Best Practices**

- Follow Node.js best practices
- Use proper async/await
- Implement proper error handling
- Use proper logging
- Handle process signals properly
- Document code properly
---
