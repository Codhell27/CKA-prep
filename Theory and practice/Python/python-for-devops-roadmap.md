
## Table of Contents

- [Day 1: Introduction to Python, Installation, and Configuration](#day-1-introduction-to-python-installation-and-configuration)
- [Day 2: Data Types, Strings, and Numbers](#day-2-data-types-strings-and-numbers)
- [Day 3: Keywords and Variables](#day-3-keywords-and-variables)
- [Day 4: Functions, Modules, and Packages](#day-4-functions-modules-and-packages)
- [Day 5: Environment Variables and Command-Line Arguments](#day-5-environment-variables-and-command-line-arguments)
- [Day 6: Operators](#day-6-operators)
- [Day 7: Conditional Handling](#day-7-conditional-handling)
- [Day 8: Working with Lists — Part 1](#day-8-working-with-lists--part-1)
- [Day 9: Loops](#day-9-loops)
- [Day 10: Working with Lists — Part 2](#day-10-working-with-lists--part-2)
- [Day 11: Dictionaries and Sets — Project 1](#day-11-dictionaries-and-sets--project-1)
- [Day 12: File Operations — Project 2](#day-12-python-for-devops-part-1-file-operations--project-2)
- [Day 13: Remote Automation and AWS — Project 3](#day-13-python-for-devops-part-2-remote-automation-and-aws--project-3)
- [Day 14: GitHub–Jira Integration — Part 1](#day-14-githubjira-integration--project-4-part-1)
- [Day 15: GitHub–Jira Integration — Part 2](#day-15-githubjira-integration--project-4-part-2)
- [Day 16: Python Interview Questions — Beginner and Intermediate](#day-16-python-interview-questions--beginner-and-intermediate)
- [Day 17: Python Interview Questions — Advanced](#day-17-python-interview-questions--advanced)
- [Additional Topics to Learn Later](#additional-topics-to-learn-later)
- [Shell Scripting vs. Python in DevOps](#shell-scripting-vs-python-in-devops)

---

## Day 1: Introduction to Python, Installation, and Configuration

- Introduction to Python and its role in DevOps.
- Installing Python and setting up a development environment.
- Writing your first Python program.

## Day 2: Data Types, Strings, and Numbers

- String data type in Python.
- String manipulation and formatting.
- Regular expressions for text processing.
- Numeric data types in Python: `int` and `float`.

## Day 3: Keywords and Variables

- Understanding variables in Python.
- Variable scope and lifetime.
- Variable naming conventions and best practices.

### Practice Exercise

- Use variables to store and manipulate configuration data in a DevOps context.

## Day 4: Functions, Modules, and Packages

- What are the differences between functions, modules, and packages?
- How do you import a package?
- What are Python workspaces?

## Day 5: Environment Variables and Command-Line Arguments

- Reading and writing environment variables in Python.
- Using the `os` and `dotenv` modules.
- Securing sensitive information stored in environment variables.
- Handling command-line arguments in Python.

### Practice Exercise

- Develop a Python script that accepts command-line arguments to customize DevOps automation tasks.

## Day 6: Operators

- Introduction to operators in Python.
- Arithmetic, comparison, and logical operators.
- Bitwise and assignment operators.

### Practice Exercise

- Use operators to perform calculations and comparisons in a DevOps script.

## Day 7: Conditional Handling

- Conditional statements: `if`, `elif`, and `else`.

### Practice Exercises

- Practice writing conditional statements to handle different situations in a Python script.

## Day 8: Working with Lists — Part 1

- Understanding lists and the list data structure.
- List manipulation and common list operations.

### Practice Exercise

- Write a script to manage a list of user accounts in a DevOps environment.

## Day 9: Loops

- Loops in Python: `for` and `while`.
- Loop control statements: `break` and `continue`.

### Practice Exercise

- Automate log file analysis with a loop to find errors.

## Day 10: Working with Lists — Part 2

- List comprehensions.
- Nested lists and advanced list operations.

### Practice Exercise

- Print the list of files in a provided list of folders.

## Day 11: Dictionaries and Sets — Project 1

- Dictionaries and key-value pairs.
- Sets and set operations.

### Practice Exercise

- Manage a dictionary of server configurations and optimize data retrieval.

## Day 12: Python for DevOps — Part 1: File Operations (Project 2)

- Introduction to file operations and Boto3.
- Automating file operations.

### Practice Exercise

- Update server resources in the `server.conf` file when an external notification is received.

## Day 13: Python for DevOps — Part 2: Remote Automation and AWS (Project 3)

- Using Fabric for remote task automation.
- AWS automation with Boto3.
- Managing EC2 instances, S3 buckets, and other AWS resources.

### Practice Exercise

- Create an AWS script for deploying applications to remote servers.

## Day 14: GitHub–Jira Integration — Project 4, Part 1

- Introduction to RESTful APIs.
- Making HTTP requests using Python.
- Parsing JSON responses and handling errors.

### Practice Exercise

- Write a Python API that listens for a GitHub comment and creates a ticket in Jira.

## Day 15: GitHub–Jira Integration — Project 4, Part 2

- Introduction to Flask.
- Writing your first API in Python.
- Handling API calls and deploying your API to a server.

### Practice Exercise

- Build on the GitHub–Jira integration project by writing a Python API that listens for a GitHub comment and creates a Jira ticket.

## Day 16: Python Interview Questions and Answers

- Beginner-level interview questions.
- Intermediate-level interview questions.

## Day 17: Python Interview Questions and Answers

- Advanced-level interview questions.

---

## Additional Topics to Learn Later

After completing this 17-day learning path, consider adding the following topics to strengthen your Python and DevOps skills.

### 1. YAML and JSON Parsing

DevOps relies heavily on configuration files. Learn to read and write YAML files using libraries such as **PyYAML**, and work with JSON to automate Kubernetes manifests, configuration files, and CI/CD pipelines.

### 2. Containerizing Python Scripts

Learn how to write a `Dockerfile` to package Python scripts so they can run consistently across environments, including inside containers and Kubernetes clusters.

### 3. Unit Testing Automation

Learn a testing framework such as **pytest** to test automation scripts and help prevent regressions or unexpected behavior when scripts run against infrastructure.

Mastering the topics in this roadmap will help prepare you for many Python scripting tasks encountered in DevOps interviews and day-to-day work.

---

## Shell Scripting vs. Python in DevOps

The choice between shell scripting and Python depends on the task. Both are useful in DevOps and have different strengths.

### When to Use Shell Scripting

#### 1. System Administration Tasks

Shell scripting is well suited to routine system administration tasks, such as:

- Managing files and directories.
- Starting and stopping services.
- Managing processes and users.
- Performing basic file manipulation.

#### 2. Command-Line Interactions

When a task primarily involves running command-line tools and utilities, shell scripting can be efficient. It makes it easy to call and combine command-line utilities.

#### 3. Rapid Prototyping

For quick prototypes, one-off tasks, and ad hoc automation, shell scripts are often faster to write.

#### 4. Text Processing

Shell scripting is useful for simple text-processing tasks, such as:

- Searching log files.
- Replacing text.
- Extracting information from command output.
- Combining tools with pipes and redirection.

#### 5. Environment Variables and Configuration

Shell scripts are useful for setting environment variables and configuring the environment in which commands run.

### When to Use Python

#### 1. Complex Logic

Python is a general-purpose programming language well suited to complex logic, data structures, and algorithms. It is often easier to maintain when a task involves extensive data manipulation.

#### 2. Cross-Platform Compatibility

Python is available across major operating systems and can be a good choice for automation that needs to run in different environments.

#### 3. API Integration

Python has a broad ecosystem of libraries for interacting with APIs, databases, cloud platforms, and web services.

#### 4. Reusable Code

Python supports functions, modules, and packages, making larger automation projects easier to organize, reuse, test, and maintain.

#### 5. Error Handling

Python provides structured exception handling and debugging tools, which are valuable when building reliable DevOps automation.

#### 6. Advanced Data Processing

For advanced data processing, analysis, or machine learning, Python offers a rich ecosystem of libraries, including **Pandas**, **NumPy**, and **SciPy**.

### Quick Comparison

| Use Case | Shell Scripting | Python |
|---|---|---|
| Simple command-line workflows | Excellent fit | Useful when more logic is needed |
| Routine file and process operations | Excellent fit | Also suitable |
| Complex logic and data structures | Can become difficult to maintain | Strong fit |
| API and cloud integrations | Possible, depending on tools | Strong library ecosystem |
| Reusable, multi-module automation | Possible, but can become unwieldy | Strong fit |
| Cross-platform automation | Depends on the shell and tools available | Often a good fit |
| Advanced data processing | Limited built-in capabilities | Strong library ecosystem |

### Rule of Thumb

- **Use shell scripting** when the task mainly connects a few command-line tools or performs a small system operation.
- **Use Python** when the task requires complex logic, structured data, API integration, reusable code, or more extensive error handling.
- **Use both when appropriate:** shell can orchestrate command-line tools, while Python can handle the complex logic and data processing.

The best choice is the simplest approach that remains reliable, secure, and maintainable.
