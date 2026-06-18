# git exet exrcise one

the first exercise



### Bundle 3 -Exercise
```python
PS C:\Users\USER\Git exercise> git status
On branch ft/bundle-2-redesign
Your branch is up to date with 'origin/ft/bundle-2-redesign

Untracked files:
  (use "git add <file>..." to include in what will be commi

nothing added to commit but untracked files present (use "g
PS C:\Users\USER\Git exercise> git log
commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (HEAD -> ft
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200

    the first bundle exercise
PS C:\Users\USER\Git exercise> git log
commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (HEAD -> ft
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200

    the first bundle exercise
PS C:\Users\USER\Git exercise> 
 *  History restored 
PS C:\Users\USER\Git exercise> git status
On branch ft/bundle-2-redesign
Your branch is up to date with 'origin/ft/bundle-2-redesign

Untracked files:
  (use "git add <file>..." to include in what will be commi
        git advanced/

nothing added to commit but untracked files present (use "g
PS C:\Users\USER\Git exercise> git checkout -b fft/team-pag
Switched to a new branch 'fft/team-page'
PS C:\Users\USER\Git exercise> git add fft/team-page       
fatal: pathspec 'fft/team-page' did not match any files
PS C:\Users\USER\Git exercise> git add team.html    
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed
  (use "git restore <file>..." to discard changes in workin
        modified:   readme.md
Untracked files:
        git advanced/

PS C:\Users\USER\Git exercise> git add .
PS C:\Users\USER\Git exercise> git status 
On branch fft/team-page
  (use "git restore --staged <file>..." to unstage)
        new file:   git advanced/exercise1.html
        new file:   git advanced/readme.md
        modified:   readme.md
        new file:   team.html

PS C:\Users\USER\Git exercise> git commit "bundle 3 exercis
error: pathspec 'bundle 3 exercise 1' did not match any fil
[fft/team-page 32c2a77] bundle 3 exercise 1
 4 files changed, 15 insertions(+)
 create mode 100644 git advanced/exercise1.html
 create mode 100644 git advanced/readme.md
 create mode 100644 team.html
PS C:\Users\USER\Git exercise> git push
fatal: The current branch fft/team-page has no upstream bra
To push the current branch and set the remote as upstream, 

    git push --set-upstream origin fft/team-page

To have this happen automatically for branches without a tr
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\USER\Git exercise> git push --set-upstream orig
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 
remote:   https://github.com/aromeirera/git-exercises-one-.
remote: 
remote:      https://github.com/aromeirera/git-exercises-on
remote: 
 * [new branch]      fft/team-page -> fft/team-page
branch 'fft/team-page' set up to track 'origin/fft/team-pag
PS C:\Users\USER\Git exercise> 
PS C:\Users\USER\Git exercise> git checkout main           
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\USER\Git exercise> git checkout -b ft/contact-p
Switched to a new branch 'ft/contact-page'
PS C:\Users\USER\Git exercise> git checkout fft/team page  
error: pathspec 'fft/team' did not match any file(s) known 
error: pathspec 'page' did not match any file(s) known to g
PS C:\Users\USER\Git exercise> git checkout fft/team-page
Switched to branch 'fft/team-page'
Your branch is up to date with 'origin/fft/team-page'.
PS C:\Users\USER\Git exercise> git log
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/design)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai:
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/design)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai:
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> fft/team-page, origin/fft/team-page)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/bundle-2-redesign, ft/bundle-2-redesign)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

:
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
:
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
, origin/fft/team-page)





design, ft/bundle-2-redesign)





EAD, main, ft/contact-page)
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200

...skipping...
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> ff
Author: aromeirera20-spec <aromeirera20@gmail.com>
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200

:
Author: aromeirera20-spec <aromeirera20@gmail.com>
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/mai
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200

    the first bundle exercise
(END)
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/bundle-2-redesign, ft/bundle-2-redesign)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/main, origin/HEAD, main, ft/contact-page)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
...skipping...
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/bundle-2-redesign, ft/bundle-2-redesign)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/main, origin/HEAD, main, ft/contact-page)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200:
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/bundle-2-redesign, ft/bundle-2-redesign)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200
    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e42
:
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/bundle-2-redesign, ft/bundle-2-redesign)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/main, origin/HEAD, main, ft/contact-page)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200
:
On branch fft/team-page
Your branch is up to date with 'origin/fft/team-page'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in workin
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\USER\Git exercise> git add .
PS C:\Users\USER\Git exercise> git checkout  ft/contact-page  verwritten by checkout:
        readme.md
Please commit your changes or stash them before you switch branches.
Aborting
PS C:\Users\USER\Git exercise> git cherry-pick 32c2a77430bfe8cef7159a9b8239e01b58454a74
error: your local changes would be overwritten by cherry-pick.
hint: commit your changes or stash them to proceed.
fatal: cherry-pick failed
PS C:\Users\USER\Git exercise> git commit -m "new"         
[fft/team-page 1fdcafc] new 
 1 file changed, 135 insertions(+)
PS C:\Users\USER\Git exercise> git push           
Enumerating objects: 5, done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: This repository moved. Please use the new location:remote:   https://github.com/aromeirera/git-exercises-one-.
To https://github.com/aromeirera20-spec/git-exercises-one-.git
   32c2a77..1fdcafc  fft/team-page -> fft/team-page
PS C:\Users\USER\Git exercise> git checkout  ft/contact-page                           
Switched to branch 'ft/contact-page'
PS C:\Users\USER\Git exercise> git cherry-pick 32c2a77430bfe8cef7159a9b8239e01b58454a74
 Date: Thu Jun 18 18:26:15 2026 +0200
 4 files changed, 15 insertions(+)
 create mode 100644 git advanced/exercise1.html
 create mode 100644 git advanced/readme.md
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\USER\Git exercise> git commmit "new contact"
git: 'commmit' is not a git command. See 'git --help'.
The most similar command is
        commit
PS C:\Users\USER\Git exercise> git add .                
PS C:\Users\USER\Git exercise> git commmit "new contact"
git: 'commmit' is not a git command. See 'git --help'.

The most similar command is
        commit
PS C:\Users\USER\Git exercise> git commmit -m "new contact"

git: 'commmit' is not a git command. See 'git --help'.

        commit
PS C:\Users\USER\Git exercise> git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\USER\Git exercise> git push --set-upstream origin ft/contact-page
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 657 bytes | 32.00 KiB/s, done.Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 
remote: This repository moved. Please use the new location:remote:   https://github.com/aromeirera/git-exercises-one-.git
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/aromeirera/git-exercises-one-/pull/new/ft/contact-page
remote: 
To https://github.com/aromeirera20-spec/git-exercises-one-.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

PS C:\Users\USER\Git exercise> 
```