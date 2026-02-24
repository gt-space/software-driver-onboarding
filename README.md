# Software Driver Onboarding Project

Welcome to the **Software Driver Onboarding Project** repository!

This repository contains onboarding implementations created by new members. Please follow the steps below to set up your development workflow and submit your work correctly.

---

## Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/gt-space/software-driver-onboarding.git
cd software-driver-onboarding
```

---

### 2️⃣ Create a New Branch

Create a personal development branch using the following naming convention:

```bash
git checkout -b dev/FirstName-LastName
```

Replace:

- `FirstName` with your first name  
- `LastName` with your last name  

**Example:**

```bash
git checkout -b dev/John-Doe
```

---

## Working on Your Code

- If you worked in a separate repository, upload your code here.
- If you have not started yet, begin your implementation in this repository.
- ALways make sure to work in your personal development branch.

---

## Committing Your Changes

When your updates are stable and ready to save, follow the steps below to get your work from your local machine to the remote repository:

### Add Files

To add a specific file:

```bash
git add <filepath>
```

To add **all modified files** in your current directory and subdirectories:

```bash
git add .
```

---

### Commit Changes

```bash
git commit -m "Concise description of what these changes did"
```

### Commit Message Guidelines

- Keep messages short and descriptive.
- Clearly explain what was implemented or fixed.

**Examples:**

- `"Add SPI functionality between IMU and STM32"`
- `"Fix data rate lag by updating register configuration"`
- `"Refactor driver initialization logic"`

---

## Push to Remote Repository

After committing, push your branch to GitHub:

```bash
git push
```

This uploads your commits to the remote repository.

---

## Important Notes

- Always work in your personal `dev/FirstName-LastName` branch.
- Make small, meaningful commits.
- Use clear and professional commit messages.

---

If you have questions, reach out to a team lead before merging.

Enjoy!
