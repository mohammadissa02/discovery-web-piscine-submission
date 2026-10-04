# Discovery Web Piscine

## Project Overview
This project covers the fundamentals of Linux, Git, GitHub, and secure Git authentication.

## Project Structure
- ex00: tree_structure.txt
- ex01: manage_files.sh and run_log.txt
- ex02: repo_url.txt and git_log.txt
- ex03: README.md, git_workflow.txt and id_ed25519_pub.txt

## Why Git Makes Development Easier

Git makes development easier because it keeps track of changes to files. It lets developers save different versions of their work and go back to an older version when needed.

**Safeguarding code:**
Git saves the changes I make in commits. If something goes wrong, I can go back to an earlier version. GitHub also keeps a copy of the project online.

**Tracking history:**
Git keeps a history of the changes made to the project. Each commit has a message that helps me understand what was changed.

**Team collaboration:**
Git helps multiple developers work on the same project. It keeps track of each person's changes and helps manage conflicts. GitHub also makes it easier to share the project with the team.


## Git Workflow
1. Edit files with `nano README.md`
2. Add changes with `git add README.md`
3. Commit changes with `git commit -m "message"`
4. Push changes to GitHub with `git push`

The recorded cycle is in git_workflow.txt.

## Authentication
SSH authentication connects the local Git repository to GitHub securely, without entering a password for every push. The public key is saved in id_ed25519_pub.txt, and the private key stays on my computer.
