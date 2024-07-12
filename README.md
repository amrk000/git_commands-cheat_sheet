<div align="center">
    <img src="https://user-images.githubusercontent.com/63168118/140657907-e5e7c29e-36d7-4870-8e20-50e0d00d9c35.jpg"
        width="100%">
    <table>
        <tr>
            <th width="51%" text-align="center">Command</th>
            <th>Description</th>
        </tr>
        <tr>
            <td colspan="2" align="center">
                <h2>Main Operations</h2>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git init</h3>
            </td>
            <td>
                <h3>initialize current project folder for version control (creates .git files)</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git status</h3>
            </td>
            <td>
                <h3>show status of current branch: the changes that need to be staged (tracked) or committed</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git add .</h3>
            </td>
            <td>
                <h3>add all changed files to stage/index</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git add FILE</h3>
            </td>
            <td>
                <h3>add file to stage/index</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git rm FILE --cached</h3>
            </td>
            <td>
                <h3>remove files from stage/index</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git rm FILE</h3>
            </td>
            <td>
                <h3>delete file</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git commit -m "MESSAGE"</h3>
            </td>
            <td>
                <h3>commit changes</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git commit -m.</h3>
            </td>
            <td>
                <h3>commit changes without message</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git commit --amend</h3>
            </td>
            <td>
                <h3>Edit/overwrite last commit</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git revert COMMIT_ID</h3>
            </td>
            <td>
                <h3>undo by creating a new commit with reverted changes from previous commit</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git reset COMMIT_ID</h3>
            </td>
            <td>
                <h3>[Danger] commits (removes all commits until selected one & make changes untracked)</h3>
                <h3>Flags: --hard (force remove changes) , --soft (put changes in stage)</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git checkout FILE</h3>
            </td>
            <td>
                <h3>[Danger] restore file from last commit and remove uncommited changes</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git mv old_FILE new_FILE</i></h3>
            </td>
            <td>
                <h3>rename file</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git log</h3>
            </td>
            <td>
                <h3>show history of commits</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git log -p</h3>
            </td>
            <td>
                <h3>show history of commits & changes</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git log -p --author=userName</h3>
            </td>
            <td>
                <h3>show history of commits & changes by specific user</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git log -p --since=2.days</h3>
            </td>
            <td>
                <h3>show history of commits & changes in time duration (minutes, hours, weeks, etc...)</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git blame FILE</h3>
            </td>
            <td>
                <h3>show when each line was last modified in file & who did it</h3>
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                <h2>Branches Operations</h2>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git branch</h3>
            </td>
            <td>
                <h3>list all local branches</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git branch -a</h3>
            </td>
            <td>
                <h3>show all including remote branches</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git branch BRANCH_NAME</h3>
            </td>
            <td>
                <h3>create new branch</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git branch -d BRANCH_NAME</h3>
            </td>
            <td>
                <h3>delete branch</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git checkout BRANCH_NAME</h3>
            </td>
            <td>
                <h3>move to branch</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git merge BRANCH_NAME</h3>
            </td>
            <td>
                <h3>merge a branch to current branch (in new commit)</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git rebase BRANCH_NAME</h3>
            </td>
            <td>
                <h3>merge a branch to current branch (editing commits chain of current branch)</h3>
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                <h2>Remote Operations</h2>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git clone REPO_URL</h3>
            </td>
            <td>
                <h3>get copy of remote repo</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git remote add REPO_NAME REPO_URL</h3>
            </td>
            <td>
                <h3>add remote repo</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git pull REMOTE_REPO_NAME REMOTE_BRANCH_NAME</h3>
            </td>
            <td>
                <h3>get remote repo latest files</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git fetch REMOTE_REPO_NAME REMOTE_BRANCH_NAME</h3>
            </td>
            <td>
                <h3>get remote repo changes history</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git push REMOTE_REPO_NAME REMOTE_BRANCH_NAME</h3>
            </td>
            <td>
                <h3>update remote repo</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git remote</h3>
            </td>
            <td>
                <h3>show all remote repos</h3>
            </td>
        </tr>
        <tr>
            <td>
                <h3>git push REMOTE_REPO_NAME --delete REMOTE_BRANCH_NAME</h3>
            </td>
            <td>
                <h3>delete remote branch</h3>
            </td>
        </tr>
    </table>
    <h2>creating .gitignore</h2>
    <h4>make a file .gitignore without extensions and add directories & files</h4>
    <h2>Example:</h2>
    <p># comment: Project exclude paths<br>
        /folder/<br>
        file.txt</p>
    <h2>updating .gitignore (untrack files)</h2>
    <h4>add file path in .gitignore file then Open git bash and Run:</h4>
    <b>git rm -r --cached .</b>
    <h2>Auth with Token instead of password (passwords removed)</h2>
    <h4>github website > Settings > Developer Settings > Generate New Token</h4>
    <h4>copy token</h4>
    <h3>method 1:</h3>
    <h4>add remote repo url and login with user name and paste token in password</h4>
    <h3>method 2:</h3>
    <h4>replace the link below with your data and use it as remote repo url</h4>
    <h4>https://{PROJECTNAME}:{TOKEN}@github.com/{USER_OR_ORG}/{REPOSITORYNAME}.git</h4>
    </br>
    ⬇ Save Git Commands (Cheat Sheet):
    <a href="https://github.com/amrk000/git_commands-cheat_sheet/blob/main/Git%20Cheat%20Sheet.png">Download Image</a>
    <a href="https://github.com/amrk000/git_commands-cheat_sheet/blob/main/Git%20Cheat%20Sheet.pdf">Download PDF</a>
</div>
