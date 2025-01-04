# Getting Started
### Note: Exanple of file-path/directory is ```D:\Documents\...```
1. To set up file path,
   ```sh <!--highlight syntax: use js for javascript, sh for terminal or shell commands-->
   cd <file-path>
   ```
2. Clone the remote repository from Github:
   ```sh
   git clone <github-link> <file-path>
   ```
# Branch Commands
1. Update the branch to the latest version (usually master or main):
   ```sh
   git pull origin <branch-name>
   ```
2. Go to specified branch:
   ```sh
   git checkout <branch-name>
   ```
   Or for newer versions of linux (2.3+):
   ```sh
   git switch <branch-name>
   ```
3. Create a local new branch:
   ```sh
   git checkout -b <branch-name> 
   ```
   Or for newer versions of linux (2.3+):
   ```sh
   git switch -c <branch-name>
   ```
4. See all branches on the remote repository (only branches on github):
   ```sh
   git branch -r
   ```
5. See all (both local and remote) branches, use this to see branches created locally:
   ```sh
   git branch -a
   ```
6. Delete specified branch only if the branch is already merged (Safe Delete):
   ```sh
   git branch -d <branch-name>
   ```
7. Force branch delete
   ```sh
   git branch -D <branch-name>
   ```
# After Making File Changes
1. Add changes to staging area. Replace (file-name) with (.) to add all changes in current directory:
   ```sh
   git add <file-name or .>
   ```
2. Commits the file changes from the staging area:
   ```sh
   git commit -m "<message>"
   ```
3. Push up the branch to the remote repository for review:
   ```sh
   git push origin <branch-name>
   ```   

