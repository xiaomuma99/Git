# Git
Git for beginners
This is the foundation of git. To summarize, using our photo analogy:

git init: Creates a box in which to permanently store panoramic pictures.
git add: Takes a temporary photo of one thing that can be assembled into a panoramic photo later.
git commit: Assembles all available temporary photos into a panoramic photo. Also destroys all temporary photos.
git log: Lists all the panoramic photos we’ve ever taken.
git show: Looks at what is in a particular panoramic photo.
git checkout: Rearranges files back to how they looked in a given panoramic photo. Does not affect the panormiac photos in your box in any way.

![image](https://user-images.githubusercontent.com/60707406/184521953-e764264c-b928-4e40-92c4-8fe0f1c87bc0.png)

As this figure shows, files fall into two main categories:
untracked files: These files have either never been tracked or were removed from tracking. Git is not maintaining history for these files.
tracked files: These files have been added to the Git repository and can be in various stages of modification: unmodified, modified, or staged.
An unmodified file is one that has had no new changes since the last version of the files was added to the Git repo.
A modified file is one that is different from the last one Git has saved.
A staged file is one that a user has designated as part of a future commit (usually through use of the git add command). We can think of these as files which have lights shining upon them.

Rule of Thumb: If you commit, you can always revert your code or change it. However, if you don’t commit, you won’t be able to get old versions back. So commit often!
