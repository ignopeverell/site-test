---
layout: post
title: "Contributing to these web pages"
---

# How to contribute to the grin webpage

1. Fork it
  - On https://github.com/ignopeverell/site-test (the _original_ or _upstream_) click Fork
  - Once forking action completes, click Settings and enable Github pages
  - Verify that it works: visit https://YOUR_GITHUB_USERNAME.github.io/site-test/
    i.e. if your github name is "grinner" then replace YOUR_GITHUB_USERNAME with grinner
2. Edit it
  - The lazy/easy option: just open files in your fork and click Edit, then reload the page from your github.io page as above.
3. Upstream it.
   Easiest is maybe to create a branch and from there click to make a new pull request against the master repo.

If you're a more advanced user you could consider having more than one branch and "PR" (pull request - which means a change suggestion) open at the same time.

You could also use git on the command line or via some graphical Git client, or use a git integration in your text editor.

# Organizing files
Adding a new file? Follow the guidlines here [File structure for current page theme](https://github.com/mmistakes/so-simple-theme#structure)

# Logo
It's been voted on, and will probably be voted on sometime again in the future. Tastes keep changing.
If you have suggestions for new logos, please use the discussion forums instead. Or if it needs to be shown in context, then add a separate logo-example-YOUR_USERNAME.md page and put it in there for people to see, and share your github.io page link on the forums etc.

# Git Command line example:
git clone (your repo url after you forked the master repo)
git remote add upstream https://github.com/ignopeverell/site-test
git fetch --all
git checkout -b my-task-branch upstream/master
(add some files, maybe with git add learn.md images/illustrative.png)
git commit -m "added illustration to learn.md"
git push --set-upstream origin my-task-branch
(then find the link that is displayed, and browse there to easily create a PR)

# Previous examples, see here for content ideas:
- [https://grin-tech.org/](https://grin-tech.org/)
- [https://grin.mw/up/](https://grin.mw/up/)
- [https://sesam.github.io/grin-pages/](https://sesam.github.io/grin-pages/)
