# git exet exrcise one

the first exercise



### Bundle 3 -Exercise
```python
PS C:\Users\USER\Git exercise> git status
On branch ft/bundle-2-redesign
Your branch is up to date with 'origin/ft/bundle-2-redesign'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\USER\Git exercise> git log
commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (HEAD -> ft/bundle-2-redesign, origin/ft/bun
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/main, origin/HEAD, main)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200

    the first bundle exercise
PS C:\Users\USER\Git exercise> git log
commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (HEAD -> ft/bundle-2-redesign, origin/ft/bun
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/main, origin/HEAD, main)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 14:29:36 2026 +0200

    the first bundle exercise
PS C:\Users\USER\Git exercise> 
 *  History restored 
PS C:\Users\USER\Git exercise> git status
On branch ft/bundle-2-redesign
Your branch is up to date with 'origin/ft/bundle-2-redesign'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        git advanced/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\USER\Git exercise> git checkout -b fft/team-page
Switched to a new branch 'fft/team-page'
PS C:\Users\USER\Git exercise> git add fft/team-page        
fatal: pathspec 'fft/team-page' did not match any files
PS C:\Users\USER\Git exercise> git add team.html    
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
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

PS C:\Users\USER\Git exercise> git commit "bundle 3 exercise 1"
error: pathspec 'bundle 3 exercise 1' did not match any file(s) known to git
[fft/team-page 32c2a77] bundle 3 exercise 1
 4 files changed, 15 insertions(+)
 create mode 100644 git advanced/exercise1.html
 create mode 100644 git advanced/readme.md
 create mode 100644 team.html
PS C:\Users\USER\Git exercise> git push
fatal: The current branch fft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin fft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\USER\Git exercise> git push --set-upstream origin fft/team-page
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:   https://github.com/aromeirera/git-exercises-one-.git
remote: 
remote:      https://github.com/aromeirera/git-exercises-one-/pull/new/fft/team-page
remote: 
 * [new branch]      fft/team-page -> fft/team-page
branch 'fft/team-page' set up to track 'origin/fft/team-page'.
PS C:\Users\USER\Git exercise> 
PS C:\Users\USER\Git exercise> git checkout main                           
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\USER\Git exercise> git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'
PS C:\Users\USER\Git exercise> git checkout fft/team page     
error: pathspec 'fft/team' did not match any file(s) known to git
error: pathspec 'page' did not match any file(s) known to git
PS C:\Users\USER\Git exercise> git checkout fft/team-page
Switched to branch 'fft/team-page'
Your branch is up to date with 'origin/fft/team-page'.
PS C:\Users\USER\Git exercise> git log
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> fft/team-page, origin/fft/team-page)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/bundle-2-redesign, ft/bundle-2-redesign)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/main, origin/HEAD, main, ft/contact-:
commit 32c2a77430bfe8cef7159a9b8239e01b58454a74 (HEAD -> fft/team-page, origin/fft/team-page)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Thu Jun 18 18:26:15 2026 +0200

    bundle 3 exercise 1

commit 4f04836566fe76a6963f9abdfe087e4eb9eb7c63 (origin/ft/bundle-2-redesign, ft/bundle-2-redesign)
Author: aromeirera20-spec <aromeirera20@gmail.com>
Date:   Tue Jun 9 16:26:22 2026 +0200

    bundle 2 exercise 2

commit b8e3316679678304ff40460dee0e426f369d9529 (origin/main, origin/HEAD, main, ft/contact-:
```