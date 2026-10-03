# Discovery Web Piscine

## Project Overview
This project covers the fundamentals of Linux, Git, GitHub, and secure Git authentication.

## Project Structure
- ex00: tree_structure.txt
- ex01: manage_files.sh and run_log.txt
- ex02: repo_url.txt and git_log.txt
- ex03: README.md, git_workflow.txt and id_ed25519_pub.txt

## Why Git Makes Development Easier

Git makes development easier by keeping track of changes made to files over time. It allows developers to save different versions of their work, so they can review changes or return to an earlier version if needed.

**Safeguarding code:** Git keeps every saved version of the project. If I break something, I can go back to a version that worked. When I push to GitHub, there is also a copy online, so my code is safe if my computer fails.

**Tracking history:** Each commit records what was changed, who changed it, and when. The commit message explains why. This makes it easier to find when a problem started.

**Team collaboration:** Multiple developers can work on the same project and keep track of their changes. Git shows conflicts instead of silently overwriting someone's work, and GitHub gives the team one place to store and share the project.

## Git Workflow
1. Edit files
2. Add changes with `git add`
3. Commit changes with `git commit`
4. Push changes to GitHub with `git push`

The recorded cycle is in git_workflow.txt.

## Authentication
SSH authentication connects the local Git repository to GitHub securely, without entering a password for every push. The public key is saved in id_ed25519_pub.txt, and the private key stays on my computer.
