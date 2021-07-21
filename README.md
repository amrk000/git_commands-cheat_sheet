<head>
    <meta name="google-site-verification" content="mZdcMLgEOK8O1SWt8vm7UI2KgP2gjVEjy2HARysTxdA" />
</head>

<div align="center">
    <h1>Git Commands (Cheat Sheet)</h1>
    <img src="https://user-images.githubusercontent.com/63168118/126414925-3feba664-3a8b-42e7-9dbb-90c25c10861d.jpg" width="100%" height="100%">
    
  <table>
    <tr>
      <th width="50%" text-align="center">Command</th>
      <th>Description</th>
    </tr>
    <tr><td><h3>git init</h3></td><td><h3>initialize current project folder for version control (creates .git files)</h3></td></tr>
    <tr><td><h3>git status</h3></td><td><h3>show status of current branch: the changes that need to be staged (tracked) or commited</h3></td></tr>
    <tr><td><h3>git add .</h3></td><td><h3>add all changed files to stage</h3></td></tr>
    <tr><td><h3>git add <i>file.extension</i></h3></td><td><h3>add file to stage</h3></td></tr>
    <tr><td><h3>git commit -m <i>"message"</i></h3></td><td><h3>commit current staged changes</h3></td></tr>
    <tr><td><h3>git checkout master</h3></td><td><h3>move pointer to master</h3></td></tr>
    <tr><td><h3>git checkout <i>commit_id</i></h3></td><td><h3>move pointer to selected commit</h3></td></tr>
    <tr><td><h3>git revert <i>commit_id</i></h3></td><td><h3>undo by creating a new commit with reverted changes from previous commit</h3></td></tr>
    <tr><td><h3>git reset <i>--flag</i> <i>commit_id</i></h3></td><td><h3>undo by removing changes from previous commit totally <br><br>flags:<br>--hard : remove from stage & directory<br>--mixed : remove from stage not directory<br>--soft : doesn't remove from stage or directory</h3></td></tr>
    <tr><td><h3>git rm <i>file.extension</i></h3></td><td><h3>remove file from stage & project repository</h3></td></tr>
    <tr><td><h3>git rm --cached <i>file.extension</i></h3></td><td><h3>remove file from stage</h3></td></tr>
    <tr><td><h3>git log</h3></td><td><h3>show history of commits including author & date</h3></td></tr>
    <tr><td><h3>git blame <i>file.extension</i></h3></td><td><h3>show when each line was last modified in file & whod did it.</h3></td></tr>
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
    <tr><td><h3>git pull</h3></td><td><h3>pull project from remote to local repository</h3></td></tr>
    <tr><td><h3>git push</h3></td><td><h3>push project from local to remote repository</h3></td></tr>
    <tr><td><h3>git pull <i>given_name</i> <i>branch_name</i></h3></td><td><h3>pull from a branch</h3></td></tr>
    <tr><td><h3>git push <i>given_name</i> <i>branch_name</i></h3></td><td><h3>push to a branch</h3></td></tr>
    <tr><td><h3>git fetch <i>given_name</i> <i>branch_name</i></h3></td><td><h3>pull from a branch but doesn't merge with local files</h3></td></tr>
    <tr><td><h3>git push <i>given_name</i> --delete <i>branch_name</i></h3></td><td><h3>delete remote branch</h3></td></tr>
</table>
  <h2>creating .gitignore</h2>
  <h4>make a file .gitignore without extenstions and add directories & files</h4>
  <h2>Example:</h2>
  <p># comment: Project exclude paths<br>
/folder/<br>
file.txt</p>
  </div>
