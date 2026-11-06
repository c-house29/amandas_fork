How to set up this repository to use GitHub
1. Download Git
2. Clone the repoistory (FIRST TIME ONLY) - open terminal in the cd/folder you want to clone the repoistory. Then enter git clone https://github.com/jewelahn/EK301-Truss-Preliminary-Design
3. Created a fork: go to code (main page of this repository), fork (in upperright corner), and make a fork with your name or smth

Standard procedure for pushing code/code revisisions to GitHub
1. Sync your forked repository – on GitHub, in your forked repository click “Sync.”
2. Open terminal, cd into the EK301-Truss-Preliminary-Design folder (The one you cloned locally)
3. [In terminal] git pull – to get the most recent version of the repository from remote to our local files.
4. [In terminal] git checkout -b <branch_name> – makes a git branch for your changes locally. 
- In stereotypical coding, when you want to make changes, you make a branch, make changes, then merge back to the main branch to bring your changes in.
5. [In terminal] Make changes to the hw file however you like – either using emacs, vscode, or apple text editor (open file_name).
6. [In terminal] git add . / git add file_name – adds all changes made to the staging area. “git add .” or “git add -a” saves all changes, not just on the 1 file named.
7. [In terminal] git commit -m “message”– saves all changes to your local repository.
8. [In terminal] git push -u origin <branch_name> – pushes these changes to the GitHub cloud. These changes are still not visible to others on the GitHub.
9. Create a pull request on GitHub - compare the main branch to your git branch. Now your changes can be seen
10. Merge (accept) or Reject code pull request changes
