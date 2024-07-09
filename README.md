# Git Branch and Commit Naming Conventions

## Branch Naming

1. `feat/`: New features
   - Example: `feat/user-authentication`

2. `fix/`: Bug fixes
   - Example: `fix/login-error`

3. `chore/`: Maintenance tasks
   - Example: `chore/update-dependencies`

4. `docs/`: Documentation updates
   - Example: `docs/api-endpoints`

5. `refactor/`: Code refactoring
   - Example: `refactor/database-queries`

6. `test/`: Adding or modifying tests
   - Example: `test/user-registration`

## Commit Messages

1. `feat:` New features
   - Example: `feat: add user registration form`

2. `fix:` Bug fixes
   - Example: `fix: resolve login button not responding`

3. `chore:` Maintenance tasks
   - Example: `chore: update npm packages`

4. `docs:` Documentation updates
   - Example: `docs: update README with setup instructions`

5. `refactor:` Code refactoring
   - Example: `refactor: optimize database queries`

6. `test:` Adding or modifying tests
   - Example: `test: add unit tests for user authentication`

7. `style:` Code style changes
   - Example: `style: format code using prettier`

8. `perf:` Performance improvements
   - Example: `perf: optimize image loading`
  

# PR Template:
## Overview
[Provide a brief description of what this PR does and why it's needed]

## Changes
- [List the main changes or additions made in this PR]
- [Include any important implementation details]
- [Mention any major refactoring or architectural changes]

## Screenshots
[If applicable, add screenshots to help explain your changes]

## Notes for Reviewers
[Add any specific points you want reviewers to pay attention to or explain any decisions you made that might not be obvious from the code]

# Example PR:
## Overview
This PR implements functionality to execute ClickHouse queries from the React frontend and display the results, using a new QueryExecutor component and React Query for efficient data fetching and state management.

## Changes
- Created new `QueryExecutor` component
- Implemented `useClickHouseQuery` custom hook using React Query
- Added error handling and loading states for query execution
- Updated main App component to include new QueryExecutor
- Added basic styling for query results display

## Screenshots
[Include screenshots of the new QueryExecutor component in action]

## Notes for Reviewers
- Pay special attention to error handling in the QueryExecutor component
- The useClickHouseQuery hook might be reusable for other components in the future
