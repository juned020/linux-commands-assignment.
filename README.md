# Linux Basic Commands Assignment

## 1. Creating and Renaming Files/Directories

**Command:**
```bash
mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt
```

**Explanation:**
- `mkdir test_dir` → Creates a directory named *test_dir*.
- `cd test_dir` → Moves into that directory.
- `touch example.txt` → Creates an empty file named *example.txt*.
- `mv example.txt renamed_example.txt` → Renames the file to *renamed_example.txt*.

---

## 2. Viewing File Contents

**Command:**
```bash
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```

**Explanation:**
- `cat` → Displays full content of `/etc/passwd`.
- `head -n 5` → Shows only first 5 lines.
- `tail -n 5` → Shows last 5 lines.

---

## 3. Searching for Patterns

**Command:**
```bash
grep "root" /etc/passwd
```

**Explanation:**
- `grep "root"` → Searches for lines containing the word *root* in `/etc/passwd`.

---

## 4. Zipping and Unzipping

**Command:**
```bash
cd ..
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir
```

**Explanation:**
- `zip -r` → Compresses *test_dir* into *test_dir.zip*.
- `unzip -d` → Extracts into a new directory *unzipped_dir*.

---

## 5. Downloading Files

**Command:**
```bash
wget https://example.com/sample.txt
```

**Explanation:**
- `wget` → Downloads a file from the internet.

---

## 6. Changing Permissions

**Command:**
```bash
touch secure.txt
chmod 444 secure.txt
ls -l secure.txt
```

**Explanation:**
- `chmod 444` → Makes file read-only for everyone.
- `ls -l` → Verifies file permissions.

---

## 7. Working with Environment Variables

**Command:**
```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```

**Explanation:**
- `export` → Sets an environment variable.
- `echo $MY_VAR` → Displays the variable value.

---

# Submission Instructions

✅ Take **screenshots** while running each command.  
✅ Paste screenshots + commands + explanations in **Google Docs or Word Doc**.  
✅ Upload the same to **GitHub** (create a repo named `linux-commands-assignment`).  
✅ Share **Google Doc link + GitHub repo link** as submission.  
