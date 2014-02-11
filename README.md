____
# git-workshop

git-workshop is a teaching repository created by Chris Grandin on Feb 10, 2014

---

## Useful commands in the Git Shell

      git help                      <List git commands>
      git clone url                 <Clone repository found at url>
      git status                    <View changes & staging>
      gitk                          <GUI - show revision tree information>
      git gui                       <GUI - show revisions, merge branches>
      git remote -v                 <Look at all remote data sources (URLs)>
      git add FILENAME              <Add new file called FILENAME>
      git remove FILENAME           <Remove existing file called FILENAME>
      git rm FILENAME               <Remove existing file called FILENAME>
      git commit -a -m "MESSAGE"    <Commit with MESSAGE recorded to the log>
      git log                       <View commit log>
      git branch                    <List all branches>
      git checkout -b NAME          <Create new branch called NAME>
      git checkout NAME             <Switch to already-existing branch called NAME>
      git branch -d NAME            <Safely delete the branch called NAME>
      git branch -D NAME            <Forcibly delete the branch called NAME>
      git log branchA ^branchB      <show log of commits in branchA but not in branchB>
      git log master ^origin/master <Show difference between local master and origin/master (GitHub)>

## Useful Git aliases
      git r                         <View remote URLs for the project, same as 'git remote -v'>
      git s                         <View status of the repository, same as 'git status'>
      git f                         <View sync information between remote/master and master>
      git co  "NAME"                <Change to branch "NAME", same as 'git checkout "NAME"'>
      git cb  "NAME"                <Create branch "NAME", same as 'git checkout -b "NAME"'>
      git com "MESSAGE"             <Commit all with message, same as 'git commit -a -m "MESSAGE"'>
      git pom                       <Push to origin/master (Github), same as 'git push origin master'>
      git mas                       <Show difference between local master and origin/master, same as 'git log master ^origin/master'>
      git sam                       <Show difference between origin/master and local master, same as 'git log ^master origin/master'>
      git dl                        <Show modified files in last commit>
      git dlc                       <Show file differences in last commit>
      git lg                        <Show merge structure in a colored format>
      git lds                       <Show one-line commits in a colored format>
      git ld                        <Show one-line commits with reletive times in a colored format>

## Advanced aliases used for setup of two users

These commands are used when you have two Github users setup on the same machine, using SSH keys.
The email address found in the .gitconfig file is the one used to push. The u1 and u2 commands simply change the address in .gitconfig.

      git wu                        <Show which user is setup to commit next (must have ssh keys setup)>
      git u1                        <Switch to user 1 (cgrandin@shaw.ca)>
      git u2                        <Switch to user 2 (chrisgrandin@gmail.com)>

There are many online resources for GIT and most of them can be found at: http://git-scm.com/documentation

A very useful video tutorial, a must watch if you will be using GIT: http://www.youtube.com/watch?v=ZDR433b0HJY

---

