Answer 1 git version 2.24.3 (Apple Git-128)


Answer 2: credential.helper=osxkeychain
user.name=Adam House
user.email=ah367119@ohio.edu


answer 3: usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.



Answer 4: On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	READ.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)

answer 6: 
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	READ.md
Answer 7 
[master (root-commit) c038082] Initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 answers.md
adamhouse@MacBook-Pro git-lab % git commit -m "Initial commit"
On branch master
Untracked files:
	READ.md

nothing added to commit but untracked files present

answer 8 
commit c038082aa371256ffdc7e25643c94c81259b3454 (HEAD -> master)
Author: Adam House <ah367119@ohio.edu>
Date:   Tue Jan 26 18:46:11 2021 -0500

    Initial commit

answer 9: 
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   README.md    


    answer 10: no 

    answer 11: 
    To https://github.com/ah367119/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/ah367119/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
answer 12: yes

answer 13: .		..		.git		.gitignore	README.md