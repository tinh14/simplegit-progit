# SimpleGit-ProGit

This repository is a practical example following the concepts from Chapter 10 
of the book **Pro Git** written by **Scott Chacon** and **Ben Straub**. 

This repository helps me understanding inner workings and implementation of Git by 
manually creating objects such as blob, tree, commit and tags using 
the **plumbing commands**.

---

### 🛠️ Plumbing Commands

These are some **Git plumbing commands** to be used in this repo to create and manipulate objects:

- `git hash-object` Creates a SHA-1 checksum hash of a file containing the 
contents and stores it in the object database (with -w option).
- `git cat-file` Displays the contents of a Git object.
- `git update-index` Adds a file or an object to the index (staging area) using its 
mode, SHA-1 hash value and path.
- `git write-tree` Creates a tree object from the index and returns its SHA-1 hash value.
- `git read-tree` Reads a tree object into the index.
- `git commit-tree` Creates a commit object from the tree object and returns its SHA-1 hash value.