# Source Control Assignment

## Instructions
You will demostrate that you know how to import/clone the project, add file, commit/check-in, revert/undo changes, view change history, diff changes

Personal assignment:
- Pick your own client, import/clone the project
- Add a file (C, HTML, PHP, …) named with your net id prefix
- Make changes to the file, check in
- Undo the previous changes, check in
- Make different changes to the file, check in
  
Turn in write-up including
- [x] Instruction to setup the repository
- [x] Instruction to import/clone the repository
- [x] Screen shot of your client (GUI or console)
- [x] File history dump (screen shot) showing file was added, changed, reverted
- [x] Screen shot of file diff for one of the check-ins
---
### This writeup is also the README for the repo. It can be found at https://github.com/chancesm/capstone-github-starter
---
## Step 1 - Create Github Repo
* Log into Github
* Click the "New" button at the to of the repositories list
* Name your repository
* Make it public or private
  * I made mine private because I am planning on deleteing it anyway as soon as this assignment is complete
* Click "Create Repository"

## Step 2 - Clone the Repository
* In the repository on Github, copy the given url.
  * This will look like one of the following URLs
    * `https://github.com/[NAME]/[REPO].git`
    * `git@github.com:[NAME]/[REPO].git`
  * I chose the ssh version(the second one) because I already have ssh keys set up on my laptop.
* Clone the repository locally by running the following command:
  * `git clone [REPOSITORY_URL]`
  * You should see a message indicating that the repository was empty.
* Open the new directory in your editor/tool/terminal of choice and run whatever git commands you want. To update Github with your local Git changes, run the following command:
  * `git push origin/master`
    * This will not do anything if you haven't made local changes.
---
## Source Control Client
Many text editors come with git tools. I use VSCode to manage my repositories. I have installed an extension in VSCode that extends the traditional source control features. It is called Git Lens.
Git Lens will show the status of the repo, any uncommitted changes, the file and line history for your current editor position, comparisons with other branches, and more.

### VSCode Regular Git Extension (with git status in Terminal)
![VSCode Git Extension][defaultGit]

### Git Lens Extension (with git status in Terminal)
![Git Lens Extension][gitLens]
---
## File History and Diff Viewer

### File History (left sidebar) with commit diff (editor)
![File History and Commit Diff][fileHistoryCommmitDiff]



<!-- Image Resources -->
[defaultGit]: images/defaultGit.png "VSCode Git Extension"
[gitLens]: images/gitLens.png "Git Lens Extension"
[fileHistoryCommmitDiff]: images/fileHistoryCommitDiff.png "File History and Commit Diff"