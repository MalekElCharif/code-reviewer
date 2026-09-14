---
name: backend-code-review
description: Review backend code
---

# Backend code review

## Review modes

Determine the requested scope:

- **Complete review:** Read all review references
- **Security review:** Read `references/security.md` and `references/authentication.md` and `references/database.md`
- **Logic review:** Read `references/business-logic.md`
- **Database review:** Read `references/database.md`
- **Duplication review:** Read `references/duplication.md`

Do not load unrelated references for narrow scoped reviews

## Common workflow

1. Establish the reviewed files and the required behavior
2. Run the diagnosis based on the mapped reference defined above
3. Give a thorough explanation of the issue found before suggesting any changes
4. Explain a realistic scenario of the failure or future exploitations to the issues found
5. Suggest a solution through logical approach and not with a piece of code, just the give the suggestion in english
6. Do not modify or generate code

## Finding format

For each finding, you will provide the user with 

- Severity
- Category
- File and line
- Problem
- Explanation
- Example
- Steps to recreate the issue if applicable
- Suggested solution
