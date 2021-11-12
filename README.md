<div align="center">
    <img src="https://user-images.githubusercontent.com/63168118/140657907-e5e7c29e-36d7-4870-8e20-50e0d00d9c35.jpg" width="100%" height="100%">
  <table>
    <tr>
      <th width="51%" text-align="center">Command</th>
      <th>Description</th>
    </tr>
    <tr><td><h3>git init</h3></td><td><h3>initialize current project folder for version control (creates .git files)</h3></td></tr>
    <tr><td><h3>git status</h3></td><td><h3>show status of current branch: the changes that need to be staged (tracked) or committed</h3></td></tr>
    <tr><td><h3>git add .</h3></td><td><h3>add all changed files to stage</h3></td></tr>
    <tr><td><h3>git add <i>file.extension</i></h3></td><td><h3>add file to stage</h3></td></tr>
    <tr><td><h3>git commit -m <i>"message"</i></h3></td><td><h3>commit current staged changes with message</h3></td></tr>
    <tr><td><h3>git commit -am <i>"message"</i></h3></td><td><h3>add all changed files then commit</h3></td></tr>
    <tr><td><h3>git commit --amend</h3></td><td><h3>edit last commit</h3></td></tr>
    <tr><td><h3>git checkout master</h3></td><td><h3>move pointer to master</h3></td></tr>
    <tr><td><h3>git checkout <i>commit_id</i></h3></td><td><h3>move pointer to selected commit</h3></td></tr>
    <tr><td><h3>git revert <i>commit_id</i></h3></td><td><h3>undo by creating a new commit with reverted changes from previous commit</h3></td></tr>
    <tr><td><h3>git reset <i>--flag</i> <i>commit_id</i></h3></td><td><h3>undo by removing changes from previous commit totally <br><br>flags:<br>--hard : remove from stage & directory<br>--mixed : remove from stage not directory<br>--soft : doesn't remove from stage or directory</h3></td></tr>
    <tr><td><h3>git rm <i>file.extension</i></h3></td><td><h3>remove file from stage & project repository</h3></td></tr>
    <tr><td><h3>git rm --cached <i>file.extension</i></h3></td><td><h3>remove file from stage</h3></td></tr>
    <tr><td><h3>git log</h3></td><td><h3>show history of commits including author & date</h3></td></tr>
    <tr><td><h3>git blame <i>file.extension</i></h3></td><td><h3>show when each line was last modified in file & who did it</h3></td></tr>
    <tr><td colspan="2" align="center"><h2>Branches commands</h2></td></tr>
    <tr><td><h3>git branch</h3></td><td><h3>list all local branches</h3></td></tr>
    <tr><td><h3>git branch -a</h3></td><td><h3>show all including remote branches</h3></td></tr>
    <tr><td><h3>git branch <i>new_branch_name</i></h3></td><td><h3>create new branch</h3></td></tr>
    <tr><td><h3>git checkout <i>branch_name</i></h3></td><td><h3>move pointer to branch</h3></td></tr>
    <tr><td><h3>git checkout -b <i>new_branch_name</i></h3></td><td><h3>create new branch and moves to it</h3></td></tr>
    <tr><td><h3>git branch -d <i>branch_name</i></h3></td><td><h3>delete branch</h3></td></tr>
    <tr><td><h3>git merge <i>branch_name</i></h3></td><td><h3>merge a branch to current branch</h3></td></tr>
    <tr><td colspan="2" align="center"><h2>Remote commands</h2></td></tr>
    <tr><td><h3>git remote add <i>give_name</i> <i>repository_https_or_ssh</i></h3></td><td><h3>add a remote repository</h3></td></tr>
    <tr><td><h3>git remote set-url <i>remote_name</i> <i>new_link</i></h3></td><td><h3>change remote repository link</h3></td></tr>
    <tr><td><h3>git remote -v</h3></td><td><h3>show all remote repositories</h3></td></tr>
    <tr><td><h3>git clone <i>repository_https_or_ssh</i></h3></td><td><h3> clone a remote repository</h3></td></tr>    
    <tr><td><h3>git pull</h3></td><td><h3>pull project from remote to local repository</h3></td></tr>
    <tr><td><h3>git push</h3></td><td><h3>push commits from local to remote repository</h3></td></tr>
    <tr><td><h3>git pull <i>given_name</i> <i>branch_name</i></h3></td><td><h3>pull from a branch</h3></td></tr>
    <tr><td><h3>git push <i>given_name</i> <i>branch_name</i></h3></td><td><h3>push to a branch</h3></td></tr>
    <tr><td><h3>git fetch <i>given_name</i> <i>branch_name</i></h3></td><td><h3>pull from a branch but doesn't merge with local files</h3></td></tr>
    <tr><td><h3>git push <i>given_name</i> --delete <i>branch_name</i></h3></td><td><h3>delete remote branch</h3></td></tr>
</table>
  <h2>creating .gitignore</h2>
  <h4>make a file .gitignore without extensions and add directories & files</h4>
  <h2>Example:</h2>
  <p># comment: Project exclude paths<br>
/folder/<br>
file.txt</p>
    <h2>Https Auth using token</h2>
  <h4>github website > Settings > Developer Settings > Generate New Token</h4>
    <h4>copy token and put in this link & replace { } with your data</h4>
    <h4>https://{PROJECTNAME}:{TOKEN}@github.com/{USER_OR_ORG}/{REPOSITORYNAME}.git</h4>
    <h4>Use the link in git remote</h4>
    </br>
    ⬇ Save Git Commands (Cheat Sheet): <a href="https://user-images.githubusercontent.com/63168118/140658206-4b22d476-fb5a-4c06-bb26-e1a33e5ca4cc.png">Download Image</a>

  </div>
 
