17th November 2026

What terminal is?
Terminal is an application where we write commands without using mouse

Todays breaking on purpose
I typed cd somefolder_that_does_not_exist
Error came  no such file or directory: somefolder_that_does_not_exist
The fix is to “create the folder first with mkdir, or cd into a folder that already exists”)

Built: a plantops folder containing README.md, LOG.md and phase1_notes.md; learned how to use mkdir to make folders and cd to move into them.

Broke: typed “cd~” with no space, got “zsh: command not found: cd~” — fixed by adding a space between cd and ~.  typed something like cd somefolder_that_does_not_exist

Broke: ran “git add -A” and got “fatal: not a git repository (or any of the parent directories): .git” — this is expected, since the folder isn’t a Git repo yet; tomorrow’s lesson (git init) fixes this.

Learned: even a tiny typo like a missing space can cause a command to completely fail, so I need to type carefully and read error messages properly instead of panicking.

# Day 2 - Wednesday 18 November 2026

Built: Created my first Git repository and made commits.

Broke: cat: locked.txt: Permission denied

Learned: Git tracks project changes using add and commit. File permissions control who can read or modify a file.



# Day 3 - Thursday 19 November 2026

**Built**
- Created a GitHub repository and connected it to my local plantops project.
- Pushed my project to GitHub.
- Used curl to fetch two JSON records from a website.
- Checked the HTTP status code and received 200.

**Broke**
- Changed the GitHub remote URL to an incorrect address.
- Got the "Repository not found" error.
- Fixed the remote URL using git remote set-url.

**Learned**
- How git push uploads commits to GitHub.
- How curl fetches data from a website.
- How JSON and HTTP status codes work.
- How to identify and fix a wrong Git remote URL.
