Aboubacar Ali
Exercice 1 :
Git version
git version 2.39.0.windows.2
Exercice 2 :
Git init
Initialized empty Git repository in C:/Users/PC/Desktop/git1/.git
Exercice 3 :
Git status
On branch master
 
No commits yet
 
nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\PC\Desktop\git1>
Exercice 4 :
Git status
No commits yet
 
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Bonjour.py
Git add
PS C:\Users\PC\Desktop\git1> git add bonjour.py
Exercice 5 :
Git add bonjour.py
PS C:\Users\PC\Desktop\git1> git add bonjour.py
PS C:\Users\PC\Desktop\git1> git status
On branch master
 
No commits yet
 
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   bonjour.py
Exercice 6 :
Git commit –m “enregistrement des modifications”
[master (root-commit) cd98542] enregistrement des modifications
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 bonjour.py
PS C:\Users\PC\Desktop\git1>
Exercice 7 :
Git log
commit cd985420a5b9ca2172f8499f5eca5aa99037dbc1 (HEAD -> master)
Author: Aboubacar Ali <Aboubacar.Ali-MAMOUDOU@ecole-it.com>
Date:   Wed Jan 4 14:22:38 2023 +0100
 
    enregistrement des modifications
PS C:\Users\PC\Desktop\git1>
Exercice 9 :
Git diff
PS C:\Users\PC\Desktop\git1> git diff
diff --git a/bonjour.py b/bonjour.py
index e69de29..3286ede 100644
--- a/bonjour.py
+++ b/bonjour.py
@@ -0,0 +1 @@
+print("Bonjour!")
\ No newline at end of file