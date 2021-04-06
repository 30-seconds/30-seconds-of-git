---
title: Restore a deleted file
tags: branch,intermediate
---

Restores a file deleted in a specific commit.

- Use `git checkout <commit>^ -- <file>` to restore the specified `<file>` deleted in the specified `<commit>`.

```sh
git checkout <commit>^ -- <file>
```

```sh
# "30seconds.txt" was deleted in the commit `3050fc0de`
git checkout 3050fc0de^ -- "30seconds.txt"
# Restores the 30seconds.txt file
```