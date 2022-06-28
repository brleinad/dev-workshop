# [Atomic commits](https://www.aleksandrhovhannisyan.com/blog/atomic-git-commits/#:~:text=Atomic%20commits%20make%20it%20easier%20to%20track%20down%20regressions&text=If%20you%20make%20atomic%20commits,other%20areas%20of%20the%20code.)

### Do:
- ✅ Make small commits with the smallest possible change.
- ✅ Use `git add` to only add the files relevant to the commit.
- ✅ Use semantic commit messages.

## Avoid:
- 🛑 Pushing all the changes in one big commit
- 🛑 Using `git add -A` or `git commit -a`.

## Why:
- To track down bugs or issues and allows to roll back changes.


