# git_test
Hello Odin!

# Git Cheatsheet

A reference list of the most commonly used Git commands.

## Remote Repository Commands

```bash
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
git push                     # pushes to default remote
git push origin main         # same goal as above in this context
```

## Workflow Commands

```bash
git add .                    # stage all changes in current directory
git commit -m "A message describing what you have done to make this snapshot different"
```

## Status & History Commands

```bash
git status                   # show working directory and staging area status
git log                      # show commit history
```

## Syntax Pattern

The basic Git syntax is: **program | action | destination**

| Example | Breakdown |
|---------|-----------|
| `git add .` | `git` \| `add` \| `.` (`.` = everything in current directory) |
| `git commit -m "message"` | `git` \| `commit -m` \| `"message"` |
| `git status` | `git` \| `status` \| (no destination) |