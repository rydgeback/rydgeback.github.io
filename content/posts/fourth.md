+++
title = "My fourth post"
date = 2022-12-03
+++

So after a bit of struggling with the submodules and authentication and updating the deploy Action. I am back here again, no issues for now. And I believe I am on the newest theme version and Zola version. Pretty sweet. Let me see if I decide to change themes or not. For future reference, when updating submodules I followed this series of steps (source: https://stackoverflow.com/questions/5828324/update-git-submodule-to-latest-commit-on-origin)

```git
git submodule update --init
git submodule update --remote --merge
git add .
git commit -m "Submodules updated"
```
I think the second step here is redundant but in the end I achieved the desired result. 🤷🏻‍♂️