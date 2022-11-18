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


