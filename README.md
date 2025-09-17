# Raavana

Raavanaa is a digital platform that helps students build smart profiles, makes it easy for colleges to manage recruitment activities, and gives recruiters a clear view of candidates’ real skills.

It’s not just about resumes. It’s about skills, growth, and connecting the right people together.

The platform is made up of three main parts:

-	For colleges (Admin)
-	For students (Candidates)
-	For companies (Recruiters)

## Why we are Building Raavana?

In today’s world, students are learning many things beyond what’s in their textbooks. But a traditional resume doesn’t always show that.

Colleges are trying to help their students grow, but there’s no simple way to manage everything in one place. Recruiters want to hire the right talent, but it’s hard to know what a student is truly capable of just by reading a resume.

Raavana brings everyone together and makes it easier to see, grow, and connect through real skills.

## What is the purpose of this repository?

### Purpose

To enable recruiters to evaluate, score, and shortlist candidates using data-driven tools.

### Core Features

- Recruiter login (temporary credential)
- View candidate list per drive
- See skill matrix of candidates
- Provide scores and feedback (visible only to recruiters)
- ATS score generation for resumes (if JD is provided)
- View profile snapshots with resume
- Functional Requirements
- Recruiters access drive-specific pages using credentials
- AI-powered insights provide candidate analysis
- Recruiters mark application statuses (e.g., Shortlisted, Not Fit)
- Can compare applicants with JD

### Functional Requirements

- Recruiters access drive-specific pages using credentials
- AI-powered insights provide candidate analysis
- Recruiters mark application statuses (e.g., Shortlisted, Not Fit)
- Can compare applicants with JD

## What contents does it have?

```bash

•	Log in using credentials shared by the college

•	See a list of candidates for a specific drive

•	View each student’s profile and skill details

•	Upload a job description and see how well each candidate matches (ATS score)

•	Give feedback or marks to candidates (only visible to the recruiter)

•	Update the status of any student during the recruitment process

•	Use the portal until the drive is marked as completed by the admin

```

## What they can get?

```bash

•	They save time in filtering resumes.

•	They see a clear skill matrix and ATS score for each student.

•	They can share private notes and feedback internally.

•	They don’t need separate tools or forms – everything is in one place.

•	They find better-fit candidates faster.

```

## How to install and how to start?

# React + Vite Project

This project is built using **React** and **Vite**.  
Follow the steps below to set up, run, and contribute to the project.

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/pavi-191004/raavanaa-ui--recruiter.git
cd raavanaa-ui--recruiter
```

### 2. Install Dependencies

Make sure you have Node.js installed.
Then, install dependencies using npm (or yarn/pnpm if you prefer):

```bash
npm install
```

### 3. Run the Project

Start the development server with:

```bash
npm run dev
```
This will start the project at:

```bash
http://localhost:5173
```

Otherwise you can start the serve with:

```bash
npm run serve-mf
```
This will start the project at:
This is the localhost integrated in host app

```bash
 http://localhost:5177
 ```

## Working with GitHub
### Pull the Latest Code

Before making changes, always pull the latest code from the main branch:

```bash
git checkout main
git pull origin main
```

### Create a New Branch (Recommended)
It’s best practice to work on a separate branch:

```bash
git checkout -b your-branch-name
```

### Push Your Code

After making changes:

```bash
git add .
git commit -m "Your commit message"
git push origin your-branch-name
```

### Merge Changes into Main

If you pushed to a feature branch, create a Pull Request on GitHub and merge it into main.

## Contibution

- Create a new branch

- Make your changes

- Push and create a pull request


