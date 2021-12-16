# learning-git

A repository for git learning purposes

---

We want to talk about a strong git tool : MERGING

- create a branch from `exercise-02` with name `to-merge-1`
- checkout on this branch
- create a file and commit it.

Now we would like to integrate the modifications just made in `to-merge-1` to be available on `exercise-02`

<br>

So we can use the following commands to merge the 2 branches.
First checkout on `exercise-02` as it's your destination branch.

```
git checkout exercise-02
```

Then merge the content of `to-merge-1`

```
git merge to-merge-1 -m "My first merge"
```

<br>

Amazing, you know enough git to start your coding journey.
