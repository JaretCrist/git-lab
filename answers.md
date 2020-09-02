Answer 1: git version 2.28.0.windows.1


Answer 2: 
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
user.name=Jaret Crist
user.email=jc374719@ohio.edu


Answer 3: Within the terminal, it pulled up a list of git commands.


Answer 4: 
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answer.md

nothing added to commit but untracked files present (use "git add" to track)


Answer 5: 
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answer.md


Answer 6:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Answer 7:
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")


Answer 8: 
commit 243be8e2cacfb5f33df3b9aed3a57b7d201acfe7 (HEAD -> master)
Author: Jaret Crist <jc374719@ohio.edu>
Date:   Wed Sep 2 16:39:21 2020 -0400

    Initial commit

Answer 9:
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Answer 10: No, nothing has been changed locally yet

Answer 11: Git failed to push because of a version difference. It recommends pulling first.

Answer 12: Yes the changes were made.

Answer 13: ("ls -a" doesn't work so I use "dir -Force")
PS C:\Users\jmc09\Documents\2020-2021\cs2400\git-lab-2> ls -a
Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible matches include: -Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4
+ ls -a
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand
 
PS C:\Users\jmc09\Documents\2020-2021\cs2400\git-lab-2> dir -Force


    Directory: C:\Users\jmc09\Documents\2020-2021\cs2400\git-lab-2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d--h--          9/2/2020   5:10 PM                .git
-a----          9/2/2020   5:10 PM            302 .gitignore
-a----          9/2/2020   5:10 PM             11 README.md