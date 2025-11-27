# Contributing Guidelines

Thank you for your interest in contributing to the **Library Management System (LMS)** project!
This project is part of the *Build Your Own Project* VITyarthi course work, and contributions help improve the quality, structure, and reliability of the system.

Please read this guide before making any changes.


## How to Contribute

There are several ways you can contribute:

* Fix bugs or edge-case errors
* Improve input validation
* Add new features (persistence, GUI, JSON storage, reports, etc.)
* Improve documentation
* Add or update test cases
* Refactor code to make it cleaner or more modular



## 🔧 Getting Started

### 1. Fork the Repository

Click **Fork** on GitHub to create your copy of this project.

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 3. Create a New Branch

Use clear, descriptive branch names:

```bash
git checkout -b feature/add-json-storage
# or
git checkout -b fix/validate-input
```


##  Coding Standards

Please follow these guidelines while writing code:

1. Write clean and readable Python code.
2. Use descriptive variable and function names.
3. When adding new functions, include comments or docstrings explaining what the function does.
4. Keep each commit **focused on a single change**.
5. Avoid mixing formatting changes with logical changes.

---

## Tests

If you add or modify a feature, consider adding accompanying test cases in the `tests/` directory.

Example structure:

```
tests/
  test_books.py
  test_borrowers.py
```

To run tests:

```bash
pytest
```

---

## Commit Message Guidelines

Use short, meaningful commit messages using the following format:

| Type        | Meaning                             |
| ----------- | ----------------------------------- |
| `feat:`     | New feature                         |
| `fix:`      | Bug fix                             |
| `docs:`     | Documentation update                |
| `refactor:` | Code cleanup (no functional change) |
| `test:`     | Add or update tests                 |
| `chore:`    | Non-code maintenance                |

**Examples:**

```
feat: add due_date and issued_at fields for issued books
fix: handle invalid input for number of copies
docs: update README with run instructions
refactor: move operations into separate module
```

---

## Pull Request Process

1. Ensure your code works and passes all tests.
2. Run the application to verify no breaking changes.
3. Push your branch:

   ```bash
   git push origin feature/add-json-storage
   ```
4. Open a **Pull Request (PR)** on GitHub.
5. Use a clear and specific PR title:

   * *"feat: add JSON persistence for books and borrowers"*
   * *"fix: prevent issuing book when no copies available"*
6. In the PR description, explain:

   * What you changed
   * Why you changed it
   * How it improves the project

---

## Project Structure (for reference)

```
lms/
  model.py
  operations.py
  cli.py
LMS.py
README.md
statement.md
tests/
```

If adding a new file or module, make sure the structure stays clean and organized.

---

## Reporting Issues

If you find a bug or want to suggest an improvement:

1. Go to **Issues** tab
2. Click **New Issue**
3. Use one of the templates (Bug Report / Feature Request)
4. Provide clear steps to reproduce and expected behavior

---

Thank You

Your contributions — whether code, documentation, or ideas — help improve this project and make the system more complete and robust.
Thank you for helping build a better Library Management System!
