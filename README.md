# VersionControl
-----------------------------------------------------------
Pagina 70
-----------------------------------------------------------
1)git status
PS E:\Projects\Version Control\University\VersionControl\VersionControl> git status
On branch main
Your branch is up to date with 'origin/main'.
---------------------------------------------------
2) git status data
PS E:\Projects\Version Control\University\VersionControl\VersionControl> git status data
On branch main
Your branch is up to date with 'origin/main'.
nothing to commit, working tree clean
PS E:\Projects\Version Control\University\VersionControl\VersionControl>
------------------------------------------------------------------------

3) nothing to commit, working tree clean
PS E:\Projects\Version Control\University\VersionControl\VersionControl> echo touch main.o
touch
main.o
PS E:\Projects\Version Control\University\VersionControl\VersionControl> echo touch main.o >.gitignore 
PS E:\Projects\Version Control\University\VersionControl\VersionControl> 
-------------------------------------------------------------------------

4) PS E:\Projects\Version Control\University\VersionControl\VersionControl> git ls-files
.gitignore
README.md
index.html
touch main.o
PS E:\Projects\Version Control\University\VersionControl\VersionControl> 
----------------------------------------------------------------------------------
5) PS E:\Projects\Version Control\University\VersionControl\VersionControl>  git hash-object data
fatal: could not open 'data' for reading: No such file or directory
PS E:\Projects\Version Control\University\VersionControl\VersionControl> 
--------------------------------------------------------------------------------------------------------------
6) PS E:\Projects\Version Control\University\VersionControl\VersionControl> git ls-files --stage   
100644 f45febc5e315b6e4ce67fffc918961fa210a8fc3 0       .gitignore
100644 cb63da57a4418cf8df01ede6f6a183e4141c31d3 0       README.md
100644 56efbdba61ff12f90f864930b9a85eac0259666d 0       index.html
100644 e69de29bb2d1d6434b8b29ae775ad8c2e48c5391 0       touch main.o
PS E:\Projects\Version Control\University\VersionControl\VersionControl> 
-------------------------------------------------------------------------------------------------------------
7) PS E:\Projects\Version Control\University\VersionControl\VersionControl>  git init  
Reinitialized existing Git repository in E:/Projects/Version Control/University/VersionControl/VersionControl/.git
PS E:\Projects\Version Control\University\VersionControl\VersionControl>
----------------------------------------------------------------------------------------------------------
8) PS E:\Projects\Version Control\University\VersionControl\VersionControl>  git init  
Reinitialized existing Git repository in E:/Projects/Version Control/University/VersionControl/VersionControl/.git/
PS E:\Projects\Version Control\University\VersionControl\VersionControl> echo something >> ready
PS E:\Projects\Version Control\University\VersionControl\VersionControl> echo something >> ready
PS E:\Projects\Version Control\University\VersionControl\VersionControl> echo something >> ready
PS E:\Projects\Version Control\University\VersionControl\VersionControl> echo somthing else >> notyet 
PS E:\Projects\Version Control\University\VersionControl\VersionControl> echo somthing else >> notyet 
PS E:\Projects\Version Control\University\VersionControl\VersionControl> git add ready notyet
PS E:\Projects\Version Control\University\VersionControl\VersionControl> 
--------------------------------------------------------------------------------------------
9) S E:\Projects\Version Control\University\VersionControl\VersionControl> git commit -m "Setup" 
[main b226d41] Setup
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 notyet
 create mode 100644 ready
PS E:\Projects\Version Control\University\VersionControl\VersionControl> 

10) PS E:\Projects\Version Control\University\VersionControl\VersionControl> git commit -m "Setup" 
[main b226d41] Setup
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 notyet
 create mode 100644 ready
PS E:\Projects\Version Control\University\VersionControl\VersionControl>   
--------------------------------------------------------------------------------------
11) PS E:\Projects\Version Control\University\VersionControl\VersionControl>  git add ready
-------------------------------------------------------------------------------------------
12) PS E:\Projects\Version Control\University\VersionControl\VersionControl>   git status
>>
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS E:\Projects\Version Control\University\VersionControl\VersionControl> 
------------------------------------------------------------------------------------
13)               







