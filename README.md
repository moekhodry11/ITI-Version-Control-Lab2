# How to Remove Branches Locally and Remotely

## Removing a Branch Locally

To delete a branch locally, use the following command:

```bash
git branch -d <branch-name>
```

If the branch has not been merged, you can force delete it using:

```bash
git branch -D <branch-name>
```

## Removing a Branch Remotely

To delete a branch from the remote repository, use:

```bash
git push origin --delete <branch-name>
```

Make sure to replace `<branch-name>` with the name of the branch you want to delete.
