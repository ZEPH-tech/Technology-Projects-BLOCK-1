
## ⭐ Activity 2: Creating and Managing Files

### 🎯 Goal  
Practise working with files and folders.

### 📝 Tasks

*Push everything to your GitHub assigment. Make as many commits as needed.*

1. Create a new folder called `practice` in your CLI directory:
   ```bash
   mkdir practice
   ```
2. Move into it:
   ```bash
   cd practice
   ```
3. Create two files:
   ```bash
   touch file1.txt file2.txt
   ```
4. Rename `file1.txt` to `notes.txt`:
   ```bash
   mv file1.txt notes.txt
   ```
5. Copy `notes.txt` to a new file called `notes_backup.txt`:
   ```bash
   cp notes.txt notes_backup.txt
   ```
6. Delete `file2.txt`:
   ```bash
   rm file2.txt
   ```

### ✅ Completion notes

All commands were run inside `1.1_software/02_CLI/`. Final contents of the `practice` folder:

```text
practice/
├── notes.txt
└── notes_backup.txt
```

`file2.txt` was created and then deleted with `rm`, so it no longer exists.

