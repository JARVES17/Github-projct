# Github-projct
 In this used most of and frequently used commands for devlopment


 1. git add .
 2. git commit -m "Initial commit"
 3. git push origin main
 5. git checkout -b BRANCH_NAME [create new branch]
 6. git add FILE_NAME [specific file add ]
 7. git branch [to check branches in project]
 8. git merge BRANCH_NAME [merge to origin branch]
 9. git branch -D BRANCH_NAME [deltes the branch]
 10. git push -u origin BRANCH_NAME [publish the branch]
 11. git push origin --delete  BRANCH_NAME [Delets the published Branch]
 12. git clone URL [Clone the repo to your local machine]

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "updated the readme
 file"
[main 564d4cd] updated the readme file
 1 file changed, 5 insertions(+)

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 435 bytes | 435.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JARVES17/Github-projct.git
   a513790..564d4cd  main -> main

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "creatd Html file" 
[main ef088d7] creatd Html file
 3 files changed, 4 insertions(+)
 delete mode 100644 chapter1.txt
 create mode 100644 index.html

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 542 bytes | 542.00 KiB/s, done.        
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/JARVES17/Github-projct.git
   564d4cd..ef088d7  main -> main

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout -b feature-update-reame
Switched to a new branch 'feature-update-reame'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "Added project status to readme"
[feature-update-reame d2ff37b] Added project status to readme
 1 file changed, 9 insertions(+), 1 deletion(-)

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git log --oneline --graph --all
* d2ff37b (HEAD -> feature-update-reame) Added project status to readme
* ef088d7 (origin/main, origin/HEAD, main) creatd Html file
* 564d4cd updated the readme file
* a513790 Initial commit
* 825e350 Initial commit

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push origin main
Everything up-to-date

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>      
 *  History restored 


(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git status
On branch feature-update-reame
nothing to commit, working tree clean

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch
* feature-update-reame
  main

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout -b main
fatal: a branch named 'main' already exists

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout -b new-branch
Switched to a new branch 'new-branch'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git status
On branch new-branch
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git chckout main
git: 'chckout' is not a git command. See 'git --help'.

The most similar command is
        checkout

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout main 
Switched to branch 'main'
M       README.md
Your branch is up to date with 'origin/main'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "updated readme"
[main 1706364] updated readme
 1 file changed, 12 insertions(+), 1 deletion(-)

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 545 bytes | 545.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JARVES17/Github-projct.git
   ef088d7..1706364  main -> main

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch
  feature-update-reame
* main
  new-branch

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout new-branch
Switched to branch 'new-branch'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch feature-update-reame
fatal: a branch named 'feature-update-reame' already exists

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout feature-update-reame

Switched to branch 'feature-update-reame'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit "feature-branch"
error: pathspec 'feature-branch' did not match any file(s) known to git

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push -u origin featured-update-reame
error: src refspec featured-update-reame does not match any
error: failed to push some refs to 'https://github.com/JARVES17/Github-projct.git'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push -u origin featured-update-reame
error: src refspec featured-update-reame does not match any
error: failed to push some refs to 'https://github.com/JARVES17/Github-projct.git'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "new-branch"       
On branch feature-update-reame
nothing to commit, working tree clean

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>gitgit push -u origin new-branch 
'gitgit' is not recognized as an internal or external command,
operable program or batch file.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout new-branch
Switched to branch 'new-branch'
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'new-branch' on GitHub by visiting:
remote:      https://github.com/JARVES17/Github-projct/pull/new/new-branch
remote:
To https://github.com/JARVES17/Github-projct.git
 * [new branch]      new-branch -> new-branch
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit "changed index.html"  
error: pathspec 'changed index.html' did not match any file(s) known to git

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "changed index.html"
[main 289dafe] changed index.html
 1 file changed, 66 insertions(+), 1 deletion(-)

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.86 KiB | 2.86 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/JARVES17/Github-projct.git
   1706364..289dafe  main -> main

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout new-branch
Switched to branch 'new-branch'
Your branch is up to date with 'origin/new-branch'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout -b new-branch-two
Switched to a new branch 'new-branch-two'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -u origin new-branch-two
error: pathspec 'origin' did not match any file(s) known to git
error: pathspec 'new-branch-two' did not match any file(s) known to git

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "new branch added"
[new-branch-two b2854b5] new branch added
 2 files changed, 31 insertions(+), 3 deletions(-)

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push -u origin new-branch-two

Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 728 bytes | 728.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'new-branch-two' on GitHub by visiting:
remote:      https://github.com/JARVES17/Github-projct/pull/new/new-branch-two
remote:
To https://github.com/JARVES17/Github-projct.git
 * [new branch]      new-branch-two -> new-branch-two
branch 'new-branch-two' set up to track 'origin/new-branch-two'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch -D new-branch-two
error: Cannot delete branch 'new-branch-two' checked out at 'C:/Users/shant/OneDrive/Desktop/Git_proj/Github-projct'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push origin --delete new-branch-two
To https://github.com/JARVES17/Github-projct.git
 - [deleted]         new-branch-two

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch    
  feature-update-reame
  main
  new-branch
* new-branch-two

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch -D new-branch-two     
error: Cannot delete branch 'new-branch-two' checked out at 'C:/Users/shant/OneDrive/Desktop/Git_proj/Github-projct'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch -D new-branch-two
Deleted branch new-branch-two (was b2854b5).

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch -D  feature-update-reame
Deleted branch feature-update-reame (was d2ff37b).

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout -b new-branch-two
Switched to a new branch 'new-branch-two'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "new branch-two"
[new-branch-two b03e76e] new branch-two
 1 file changed, 20 insertions(+), 67 deletions(-)
 rewrite index.html (100%)

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push -u orirgin new-branch-two
fatal: 'orirgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push -u origin new-branch-two

Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 419 bytes | 419.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'new-branch-two' on GitHub by visiting:
remote:      https://github.com/JARVES17/Github-projct/pull/new/new-branch-two
remote:
To https://github.com/JARVES17/Github-projct.git
 * [new branch]      new-branch-two -> new-branch-two
branch 'new-branch-two' set up to track 'origin/new-branch-two'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout new-branch
Switched to branch 'new-branch'
Your branch is up to date with 'origin/new-branch'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git merge new-branch-two
Updating ef088d7..b03e76e
Fast-forward
 README.md  | 13 ++++++++++++-
 index.html | 22 ++++++++++++++++++++--
(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git log --oneline --graph --all
* b03e76e (HEAD -> new-branch, origin/new-branch-two, new-branch-twog --oneline --graph --all) new branch-two                                                    ) new branch-two
* 289dafe (origin/main, origin/HEAD, main) changed index.html       
* 1706364 updated readme
* ef088d7 (origin/new-branch) creatd Html file
* 564d4cd updated the readme file
* a513790 Initial commit
* 825e350 Initial commit

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git psuh
git: 'psuh' is not a git command. See 'git --help'.

The most similar command is
        push

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push otigin
fatal: 'otigin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git merge new-branch
Updating 289dafe..b03e76e
Fast-forward
 index.html | 87 +++++++++++++++-----------------------------------------------
 1 file changed, 20 insertions(+), 67 deletions(-)

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m 'merged main and new-branch'
error: pathspec 'main' did not match any file(s) known to git
error: pathspec 'and' did not match any file(s) known to git
error: pathspec 'new-branch'' did not match any file(s) known to git

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JARVES17/Github-projct.git
   289dafe..b03e76e  main -> main

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push origin -delete new-branch
error: did you mean `--delete` (with two dashes)?

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push origin --delete new-branch
To https://github.com/JARVES17/Github-projct.git
 - [deleted]         new-branch

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch
* main
  new-branch
  new-branch-two

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push
Everything up-to-date

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch -D new-branch-two     
Deleted branch new-branch-two (was b03e76e).

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch -d new-branch
Deleted branch new-branch (was b03e76e).

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git branch
* main

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push origin --delete new-branch-two
To https://github.com/JARVES17/Github-projct.git
 - [deleted]         new-branch-two

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git checkout -b new-branch       
Switched to a new branch 'new-branch'

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git add .

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m 'test branch'
error: pathspec 'branch'' did not match any file(s) known to git

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git commit -m "test"       
[new-branch b37a1a1] test
 1 file changed, 6 insertions(+), 7 deletions(-)

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push -u origin new-branch
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'new-branch' on GitHub by visiting:
remote:      https://github.com/JARVES17/Github-projct/pull/new/new-branch
remote:
To https://github.com/JARVES17/Github-projct.git
 * [new branch]      new-branch -> new-branch
branch 'new-branch' set up to track 'origin/new-branch'.

(base) C:\Users\shant\OneDrive\Desktop\Git_proj\Github-projct>git push origin --delete new-branch
To https://github.com/JARVES17/Github-projct.git
 - [deleted]         new-branch
