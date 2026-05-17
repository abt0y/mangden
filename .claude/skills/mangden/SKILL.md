```markdown
# mangden Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches the core development patterns and workflows used in the `mangden` TypeScript codebase. The repository does not use a major framework, focusing instead on clear file organization, conventional commits, and modular TypeScript code. You'll learn how to structure files, write and organize code, update documentation, manage data files, and maintain the landing page, following the established conventions.

## Coding Conventions

### File Naming
- Use **snake_case** for all file names.
  - Example: `user_profile.ts`, `data_loader.test.ts`

### Import Style
- Use **relative imports** for all modules.
  ```typescript
  import { fetchData } from './data_loader';
  ```

### Export Style
- Use **named exports**.
  ```typescript
  // In data_loader.ts
  export function fetchData() { ... }
  ```

### Commit Messages
- Follow **conventional commit** format.
- Common prefixes: `docs:`, `feat:`, `data:`
- Example:
  ```
  feat: add user profile data migration script
  ```

## Workflows

### Update Index HTML Landing Page
**Trigger:** When you want to add or improve the landing page for the project.  
**Command:** `/update-landing-page`

1. Edit or create `index.html` to add new features or improve the UI.
2. Optionally update documentation (such as `README.md`) to reflect changes.
3. Commit changes with a descriptive message, e.g., `feat: improve landing page layout`.

**Example:**
```html
<!-- index.html -->
<body>
  <h1>Welcome to Mangden!</h1>
  <!-- Add new UI elements here -->
</body>
```

---

### Add or Migrate Data Files
**Trigger:** When you want to add or reorganize data files in the repository.  
**Command:** `/add-data-files`

1. Add or move data files into the appropriate `data/` or `references/` subfolders.
2. Update `.gitignore` if necessary to exclude/include new files.
3. Commit changes with a message like `data: migrate reference files`.

**Example:**
```
data/
  users.json
references/
  api_schema.yaml
.gitignore
```

---

### Update README Documentation
**Trigger:** When you want to document changes or improvements in the project.  
**Command:** `/update-readme`

1. Edit `README.md` to add or update documentation.
2. Commit `README.md` changes with a message such as `docs: update usage instructions`.

**Example:**
```markdown
## Usage
Run `npm start` to launch the application.
```

---

## Testing Patterns

- Test files use the pattern: `*.test.*` (e.g., `data_loader.test.ts`)
- The testing framework is **unknown**, but tests are colocated with the code using the above pattern.
- Example test file:
  ```typescript
  // data_loader.test.ts
  import { fetchData } from './data_loader';

  test('fetchData returns expected result', () => {
    expect(fetchData()).toEqual(/* expected value */);
  });
  ```

## Commands

| Command                | Purpose                                              |
|------------------------|------------------------------------------------------|
| /update-landing-page   | Add or improve the landing page (`index.html`)       |
| /add-data-files        | Add or migrate data or reference files               |
| /update-readme         | Update the README documentation                      |
```