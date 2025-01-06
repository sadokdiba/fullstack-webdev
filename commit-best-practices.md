# Commit Best Practices

Writing clear and professional commit messages is essential for maintaining a clean and understandable project history. Below are the best practices for writing commit messages:

---

## 🛠 Commit Message Structure

A commit message should consist of three parts:

1. **Header** (Required)
   - A short summary of the changes (50 characters or less).
2. **Body** (Optional)
   - A detailed explanation of what was changed and why.
3. **Footer** (Optional)
   - Any references to issues, tickets, or breaking changes.

---

## 🔖 Commit Prefixes

Use the following prefixes to categorize your commits:

| Prefix     | Purpose                                                       |
|------------|---------------------------------------------------------------|
| `feat`     | Introducing a new feature                                     |
| `fix`      | Fixing a bug or issue                                         |
| `chore`    | Routine tasks like updating dependencies or configurations    |
| `docs`     | Documentation updates                                         |
| `style`    | Code formatting or stylistic changes (no logic changes)       |
| `refactor` | Code refactoring without adding new features or fixing bugs   |
| `test`     | Adding or updating tests                                      |
| `perf`     | Performance improvements                                      |
| `revert`   | Reverting a previous commit                                   |

---

## ✅ Examples

### Example 1: Adding a New Feature
```
feat: add user authentication using JWT

Added login and signup functionality with JWT-based authentication. Updated routes to require authentication for protected resources.
```

### Example 2: Fixing a Bug
```
fix: resolve crash on user profile page

Fixed a null pointer exception that caused the app to crash when viewing a user profile without a bio.
```

### Example 3: Updating Documentation
```
docs: update README with setup instructions

Added detailed steps to set up the project locally, including environment variables and database configuration.
```

---

## 🔗 References

- [Conventional Commits Specification](https://www.conventionalcommits.org/en/v1.0.0/)

---

By following these best practices, you will create a more organized and professional project history. Happy coding! 🚀
