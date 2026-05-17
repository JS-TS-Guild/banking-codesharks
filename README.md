[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/W3nV4mdD)
# Banking management

## Overview

We are going to code up a banking management system using TypeScript and basic OOPS knowledge. This is a real world problem and will give you a good understanding of how to design and implement a similar system, but all within your own codebase for now.

## Requirements

- New banks can be created from the factory.
- Bank can specify if it's allowed for its accounts to have negative balance. If not specified, an account cannot have negative balance in that bank.
- Users can have multiple accounts. These accounts can be in same or different banks.
- Users can transfer money between their own accounts or others. If the money is being transferred within the same bank, then the bank details are not required.
- The accounts listed in user's account list are based on the priority of usage.
- When transferring money, if one of the accounts within the same bank doesn't have sufficient funds, then the next account belonging to the same user in the same bank will be used.

## Rules

- Use pnpm as the package manager
- Don't change anything in package.json, __tests__ or .github/workflows (Those assignments will be disqualified for grading and evaluation)
- You can form a team of 2-3 people and submit the solution
- There will be 3 levels of evaluation:
  - Simple: 2 points
  - Real: 7 points
  - Final: 24 points

## Steps

1. Accept the assignment via the link provided.
2. Design the classes and methods for the banking management system. Maybe create a class diagram and sequence diagram for early review.
3. Make sure all test cases pass and also make sure all requirements are met. First focus on passing the tests in `simple.test.ts` and then move on to `real.test.ts`.
4. Use proper commit messages and push your changes to the repo in the default branch.
5. Check the status of your GitHub actions.
6. Let Ankush know when you are done in the JS TS Discord server.
