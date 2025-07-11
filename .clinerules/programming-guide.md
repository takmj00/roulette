# Programming Guide

## Error Fixing Rule

- When an error occurs, first look for the root cause rather than merely fixing the symptom.
- When fixing an error, follow these steps:
  1. Check all the information provided about the error.
     - For example, check the error message, log files, and related documentation.
  2. Instead of just fixing the symptom, identify the root cause of the error.
     - For example, look for logical errors in the code or configuration issues.
  3. After identifying the cause, create a plan to fix the error.
     - For example, consider code modifications or configuration changes.
  4. Review the feasibility of the plan and start working on the fix.
  5. After the fix is complete, follow the Build Check Rule.

## Code Planning Rule (For Plan Mode)

- For planning, you should read the code and understand its overall structure.
- You must read all related code by yourself. You should proactively read and understand the code.
  - Use read_file freely to read the code.
- By reading the code, you can understand the following:
  - The overall structure of the codebase.
  - How different components interact with each other.
  - The purpose and functionality of each module or file.
- After reading the code, you can create a plan for your work.
- The plan should include:
  - The specific tasks to be completed.
  - The expected outcomes of each task.
  - Any dependencies or prerequisites for the tasks.
- The plan should be clear and concise, making it easy to follow.

## Code Writing Rule (For Act Mode)

- Write code by following the plan you created.
- Follow the coding standards and conventions of the project.
  - For example, use consistent naming conventions, indentation, and commenting styles.
  - To do this, refer to the project's documentation or existing codebase.
- Write code that is efficient and performs well.
- Ensure that your code is modular and reusable.
  - Break down complex tasks into smaller, manageable functions or modules.
  - Use libraries and frameworks where appropriate to avoid reinventing the wheel.
- Write code that is easy to understand and maintain.
- Use meaningful variable and function names.
- Follow the best practices of the programming language, library, or framework you are using.
- Ensure that your code is well-structured and easy to read.
- After completing the writing, follow the Build Check Rule.