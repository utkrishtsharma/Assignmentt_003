
Here are clear, step-by-step instructions for your students to create a GitHub repository, push their code and text answers, and share the link with you. These instructions will help them learn essential version control skills and ensure smooth submission of their assignments.[^1][^2][^3][^4][^5]

***

### Assignment Submission Using GitHub: Step-by-Step Guide

#### 1. Create a GitHub Account (if you don’t have one)

- Go to https://github.com and sign up using your email address.


#### 2. Create a New Repository

- Click the ‘+’ icon in the top-right corner → Select **‘New repository’**.
- Repository Name: Use a format like `Assignment-3-YourName`.
- Set privacy to **Public** or **Private** (as instructed).
- Do **not** initialize with a README, .gitignore, or License yet.
- Click **‘Create repository’**.


#### 3. Set Up Git Locally

- Install Git if you don’t have it already (https://git-scm.com).


#### 4. Clone the Repository to Your Computer

```bash
git clone https://github.com/YourUsername/Assignment-3-YourName.git
```

- Replace `YourUsername` and the repository name appropriately.
- Change into your repo directory:

```bash
cd Assignment-3-YourName
```


#### 5. Add Your Assignment Files

- Add your **code files**, **text answers** (as `.txt` or `.md`), and any other required documents to this folder.


#### 6. Stage and Commit Your Changes

```bash
git add .
git commit -m "Add assignment solutions"
```


#### 7. Push Your Work to GitHub

```bash
git push origin main
```


#### 8. Check Your Repository on GitHub

- Go to your repository page on GitHub in your browser.
- Make sure all files appear as expected.


#### 9. Share the Repository Link

- Copy your repo link (e.g., `https://github.com/YourUsername/Assignment-3-YourName`).
- Submit the link to your instructor as directed (email, online form, etc.).

***

### Useful Tips

- **Commit Often:** Break your work into small parts, and commit each time you complete a section.
- **Commit Messages:** Write clear, short messages describing what you changed.
- **File Organization:** Name files clearly (e.g., `knapsack.py`, `answers.md`).
- **README:** Optionally, add a `README.md` file summarizing your assignment and listing the problems you solved.
- **Version History:** Explore `git log` to view your commit history and see how Git tracks your progress.
- **Help:** If you get stuck, visit https://docs.github.com or ask for help on Piazza/class forum.

***

### Example Folder Structure

```
Assignment-3-YourName/
├── knapsack.py
├── graph_algorithms.py
├── answers.md
├── README.md
```

Following these steps will help you submit your assignment correctly and introduce you to best practices in version control with GitHub.[^2][^3][^4][^5][^1]

<div align="center">⁂</div>

[^1]: https://docs.github.com/en/get-started/using-git/about-git

[^2]: https://www.youtube.com/watch?v=tRZGeaHPoaw

[^3]: https://github.blog/developer-skills/github-education/set-up-your-digital-classroom-with-github-classroom/

[^4]: https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-the-git-and-github-starter-assignment

[^5]: https://stackoverflow.com/questions/75663866/how-can-students-update-their-github-classroom-assignment-repository

<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>
