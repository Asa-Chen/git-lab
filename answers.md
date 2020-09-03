/**
* @file: answers.md
* @author: Asa Chen
* @date: September 03, 2020
* @brief: Answer File for Lab 02
*/

//Answer 1
    git version 2.28.0.windows.1

//Answer 2
    diff.astextplain.textconv=astextplain
    filter.lfs.clean=git-lfs clean -- %f
    filter.lfs.smudge=git-lfs smudge -- %f
    filter.lfs.process=git-lfs filter-process
    filter.lfs.required=true
    http.sslbackend=openssl
    http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
    core.autocrlf=true
    core.fscache=true
    core.symlinks=false
    pull.rebase=false
    credential.helper=manager
    user.name=Asa-Chen
    user.email=ac581218@ohio.edu

//Answer 3
    When "git <command> --help" is typed, a local .html file is opened. Displaying instructions for whatever command you typed in.

//Answer 4
    On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

//Answer 5
    On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

//Answer 6
    On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

//Answer 7
    On branch master
nothing to commit, working tree clean

//Answer 8
    commit 9c12e66aa14fd2c7fc1fe0496598896dd1ee2fd6 (HEAD -> master)
Author: Asa-Chen <ac581218@ohio.edu>
Date:   Thu Sep 3 16:02:04 2020 -0400

    Initial commit

//Answer 9
    On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

//Answer 10 
    Local changes were not observed after commiting changes on git-hub

//Answer 11
    To https://github.com/Asa-Chen/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/Asa-Chen/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

//Answer 12
    Local changes reflected online changes once the "git pull" command was initiated.

//Answer 13
    Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible matches
include: -Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4
+ ls -a
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand

