### **Three Staes in Git**
1. **Modified**: Working Directory
2. **Staged**: Staging Area
3. **Committed**: Git Directory (Repository)

---

#### Git config: First-time setup
git config --global user.name "name"
git config --global user.email address@gmail.com
git config --global inint.defalutBranch main
git config --list
git config --list --show-origin
---
### git init
Initializing a Repository in an Existing Directory.

---

### git staus

Checking Repository Status.

---
#### git add [file_name]

Adding a new file to be staged.

---

#### git add .

 Adding all files to be staged.
 
---

#### git rm –cached [file_name]

Unstaging a file.

---

#### nano .gitignore
Ignoring a file.

```sh
Ignore all .a files: *.a
But do track lib.a, even though you're ignoring .a files above:  !lib.a
Only ignore the TODO file in the current directory, not subdir/TODO:  /TODO
Ignore all files in any directory named build:  build/
Ignore doc/notes.txt, but not doc/server/arch.txt:  doc/*.txt
Ignore all .pdf files in the doc/directory and any of its subdirextories:  doc/**/*.pdf
```

---

#### git commit -m "commit message"
Commit.

---

#### git branch -m used_name new_name
Change branch name.
