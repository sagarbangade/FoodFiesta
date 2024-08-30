# FoodFiesta

FoodFiesta is a fictional food delivery application designed to simulate a real-world software development project. The project is managed using Git and GitHub, with different features developed on separate branches to simulate a collaborative team environment.

## Project Overview

FoodFiesta aims to provide a seamless food ordering and delivery experience for users. The application is divided into several key features, each developed on its own branch to ensure modular and organized development.

### Team Members

- Raj Patel (Lead Developer)
- Priya Sharma (Backend Developer)
- Aman Verma (Frontend Developer)
- Anjali Mehta (UI/UX Designer)

## Features and Branches

### 1. User Authentication
- **Branch:** `feature-user-authentication`
- **Description:** This feature handles user registration, login, and authentication within the FoodFiesta platform. It ensures that users can create accounts, log in securely, and manage their profiles.
- **File:** `feature-user-authentication.js`
- **Challenges:** Implementing secure password storage and handling edge cases such as forgotten passwords were challenging.

### 2. Order Tracking
- **Branch:** `feature-order-tracking`
- **Description:** This feature allows users to track their food orders in real-time, from preparation to delivery. It provides updates on the order status and estimated delivery time.
- **File:** `feature-order-tracking.js`
- **Challenges:** Synchronizing the order status with the delivery partner's system to provide real-time updates required careful integration.

### 3. Payment System
- **Branch:** `feature-payment-system`
- **Description:** This feature manages payment processing for orders placed on FoodFiesta. It supports multiple payment methods, including credit cards, debit cards, and digital wallets.
- **File:** `feature-payment-system.js`
- **Challenges:** Ensuring secure payment processing and handling payment gateway failures were significant challenges.

## Development Workflow

### Branch Management

Each feature was developed on its own branch to ensure isolated and focused development. The branches created for this project are:

- `feature-user-authentication`
- `feature-order-tracking`
- `feature-payment-system`

### Simulated Collaboration

To simulate a team collaboration scenario, we used the following Git workflow:

1. **Branch Creation:** Each feature was developed on a separate branch.
2. **Feature Development:** Dummy code files were created and updated on each branch.
3. **Pull Requests:** After development, pull requests were created to merge the feature branches into the `main` branch.
4. **Code Review:** Each pull request was reviewed and merged to simulate a collaborative team environment.

### Final Integration

Once all features were developed and merged, the latest version of the `main` branch was pulled to ensure the project was up-to-date.

## Git Commands Used

- `git clone` - To clone the repository.
- `git checkout -b` - To create and switch to a new branch.
- `git add` - To stage changes for a commit.
- `git commit -m` - To commit changes with a message.
- `git push origin` - To push the branch to GitHub.
- `git pull origin main` - To update the branch with changes from the main branch.
- `git log` - To view the commit history.
- `git status` - To check the state of the workspace.

## Challenges and Learnings

- Managing merge conflicts during the integration of different branches was a key challenge.
- Ensuring that all team members followed the branching strategy helped maintain a clean and organized codebase.
- Simulating real-world collaboration highlighted the importance of clear commit messages and regular code reviews.

## Conclusion

FoodFiesta is a practical project designed to simulate the workflow and collaboration involved in real-world software development. Through this project, we gained hands-on experience with Git and GitHub, learned to manage branches effectively, and understood the importance of version control in team-based projects.

## Repository

- **URL:** [FoodFiesta Repository](https://github.com/sagarbangade/FoodFiesta)
