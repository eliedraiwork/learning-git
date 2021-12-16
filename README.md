# learning-git

A repository for git learning purposes

---

Wonderful, you just performed your first checkout.
<br>
You can also checkout on a non-existing branch by using this command:

```
git checkout -b new-branch
```

Next thing to do is to create your first commit.
<br>
So in the root of the project, create a file "hello.txt" and write something in it by using this command:

```
echo "Hello, world!" > hello.txt
```

You can check the status of all your git files by using the following command:

```
git status
```

As you can see, the file "hello.txt" is not tracked. Use the following command to stage it:

```
git add hello.txt
```

If you want to add all the untracked files, you can also write:

```
git add .
```

Once you are sure you want to save this file in your git repository, you can perform a commit by tapping the following command:

```
git commit -m "Give a short description about the commit here"
```

Write down the following command to start the next step:

```
git checkout exercise-01
```
