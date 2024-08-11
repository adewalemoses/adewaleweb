USER@DESKTOP-H7PN58M MINGW64 ~/git-project
$ cd adewaleweb

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-contact-info)
$ ls
README.md  about_us.html  contact_us.html  events.html  home.html  index.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-contact-info)
$ git branch main
fatal: a branch named 'main' already exists

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-contact-info)
$ switch branch main
bash: switch: command not found

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-contact-info)
$ git switch main
A       about_us.html
A       contact_us.html
A       events.html
A       home.html
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ ls
README.md      contact       contact_us.html  home.html
about_us.html  contact.html  events.html      index.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ cat events
cat: events: No such file or directory

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ cat events.html

for booking contact us
adewalemoses@gmail.com


USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ cat home.html
this is my home page


USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ git switch add-book-review
A       about_us.html
A       contact_us.html
A       events.html
A       home.html
Switched to branch 'add-book-review'

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ touch book_reviews.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ vim book_reviews.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ ls
README.md      book_reviews.html  contact.html     events.html  index.html
about_us.html  contact            contact_us.html  home.html

add book reviews section

warning: in the working copy of 'book_reviews.html', LF will be replaced by CRLF
 the next time Git touches it
[add-book-review 074e4db] add book reviews section
 1 file changed, 1 insertion(+)
 create mode 100644 book_reviews.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git push
fatal: The current branch add-book-review has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin add-book-review

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git push add-book-review
fatal: 'add-book-review' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git push book_reviews.html
fatal: invalid gitfile format: book_reviews.html
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git status
On branch add-book-review
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about_us.html
        new file:   contact_us.html
        new file:   events.html
        new file:   home.html


USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ ls
README.md      book_reviews.html  contact.html     events.html  index.html
about_us.html  contact            contact_us.html  home.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git switch main
A       about_us.html
A       contact_us.html
A       events.html
A       home.html
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ ls
README.md      contact       contact_us.html  home.html
about_us.html  contact.html  events.html      index.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ git pull
Already up to date.

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ ls
README.md      contact       contact_us.html  home.html
about_us.html  contact.html  events.html      index.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ git push
Everything up-to-date

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ ls
README.md      contact       contact_us.html  home.html
about_us.html  contact.html  events.html      index.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ git switch add-book-review
A       about_us.html
A       contact_us.html
A       events.html
A       home.html
Switched to branch 'add-book-review'

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ ls
README.md      book_reviews.html  contact.html     events.html  index.html
about_us.html  contact            contact_us.html  home.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git push
fatal: The current branch add-book-review has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin add-book-review

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git push --set-upstream origin add-book-review
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 155.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'add-book-review' on GitHub by visiting:
remote:      https://github.com/adewalemoses/adewaleweb/pull/new/add-book-revie
remote:
To https://github.com/adewalemoses/adewaleweb.git
 * [new branch]      add-book-review -> add-book-review
branch 'add-book-review' set up to track 'origin/add-book-review'.

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git switch main
A       about_us.html
A       contact_us.html
A       events.html
A       home.html
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ ls
README.md      contact       contact_us.html  home.html
about_us.html  contact.html  events.html      index.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (main)
$ git switch add-book-review
A       about_us.html
A       contact_us.html
A       events.html
A       home.html
Switched to branch 'add-book-review'
Your branch is up to date with 'origin/add-book-review'.

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ ls
README.md      book_reviews.html  contact.html     events.html  index.html
about_us.html  contact            contact_us.html  home.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git switch update-events
fatal: invalid reference: update-events

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git switch update-event
fatal: invalid reference: update-event

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git branch
* add-book-review
  add-contact-info
  jerry
  main
  update-navigation

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git branch update-events

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ switch git update-events
bash: switch: command not found

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (add-book-review)
$ git switch update-events
A       about_us.html
A       contact_us.html
A       events.html
A       home.html
Switched to branch 'update-events'

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (update-events)
$ touch events.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (update-events)
$ ls
README.md      book_reviews.html  contact.html     events.html  index.html
about_us.html  contact            contact_us.html  home.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (update-events)
$ vim events.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (update-events)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 925 bytes | 16.00 KiB/s, done.
From https://github.com/adewalemoses/adewaleweb
   0628258..a0b9074  main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:
this is the events page





















warning: in the working copy of 'events.html', LF will be replaced by CRLF the n
ext time Git touches it
[update-events 90854ee] this is the events page
 1 file changed, 4 insertions(+)
 create mode 100644 events.html

USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (update-events)
$ git push
fatal: The current branch update-events has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin update-events

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


USER@DESKTOP-H7PN58M MINGW64 ~/git-project/adewaleweb (update-events)
$ git push --set-upstream origin update-events
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 325 bytes | 162.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'update-events' on GitHub by visiting:
remote:      https://github.com/adewalemoses/adewaleweb/pull/new/update-events
remote:
To https://github.com/adewalemoses/adewaleweb.git
 * [new branch]      update-events -> update-events
branch 'update-events' set up to track 'origin/update-events'.
