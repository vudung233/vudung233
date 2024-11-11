upyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~$ mkdir git-lab1
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~$ cd git-lab1
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ git --version
git version 2.34.1
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ git config --global user.name "Vu Manh Dung"
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ git config --global user.email "24102831@st.phenikaa-un.edu.vn"
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ git config --list
user.name=Vu Manh Dung
user.email=24102831@st.phenikaa-un.edu.vn
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
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
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ ls -a
.  ..
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /home/jupyter-24102831@st.phenik-5dd0c/git-lab1/.git/
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ vi README.md
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ git add README.md
jupyter-24102831@st.phenik-5dd0c@jupyter-virtual-machine:~/git-lab1$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

