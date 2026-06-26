# Linux Commands Assignment

## Name
Shivam Talim

## Commands Performed

### 1. Create a directory
```bash
mkdir test_dir
```
**Explanation:** Creates a new directory named `test_dir`.

### 2. Create a file
```bash
touch example.txt
```
**Explanation:** Creates an empty file named `example.txt`.

### 3. Rename a file
```bash
mv example.txt renamed_example.txt
```
**Explanation:** Renames the file.

# Linux Commands Assignment

**Name:** Shivam Talim
**Platform:** Ubuntu (WSL)

## 1. Creating and Renaming Files/Directories

### Create a directory

**Command:**

```bash
mkdir test_dir
```

**Explanation:** Creates a new directory named `test_dir`.

### Create an empty file

**Command:**

```bash
touch test_dir/example.txt
```

**Explanation:** Creates an empty file named `example.txt` inside the `test_dir` directory.

### Rename the file

**Command:**

```bash
mv test_dir/example.txt test_dir/renamed_example.txt
```

**Explanation:** Renames `example.txt` to `renamed_example.txt`.

---

## 2. Viewing File Contents

### Display the contents of `/etc/passwd`

**Command:**

```bash
cat /etc/passwd
```

**Explanation:** Displays the complete contents of the `/etc/passwd` file.

### Display the first 5 lines

**Command:**

```bash
head -5 /etc/passwd
```

**Explanation:** Shows the first five lines of the file.

### Display the last 5 lines

**Command:**

```bash
tail -5 /etc/passwd
```

**Explanation:** Shows the last five lines of the file.

---

## 3. Searching for Patterns

### Search for the word "root"

**Command:**

```bash
grep "root" /etc/passwd
```

**Explanation:** Searches and displays all lines containing the word `root`.

---

## 4. Zipping and Unzipping

### Compress a directory

**Command:**

```bash
zip -r test_dir.zip test_dir
```

**Explanation:** Compresses the `test_dir` directory into `test_dir.zip`.

### Extract the ZIP file

**Command:**

```bash
unzip test_dir.zip -d unzipped_dir
```

**Explanation:** Extracts the ZIP file into a new directory named `unzipped_dir`.

---

## 5. Downloading Files

### Download a file using wget

**Command:**

```bash
wget https://example.com/sample.txt
```

**Explanation:** Downloads the file from the specified URL to the current directory.

---

## 6. Changing Permissions

### Create a file

**Command:**

```bash
touch secure.txt
```

### Change file permissions

**Command:**

```bash
chmod 444 secure.txt
```

**Explanation:** Makes the file read-only for the owner, group, and others.

---

## 7. Working with Environment Variables

### Create an environment variable

**Command:**

```bash
export MY_VAR="Hello, Linux!"
```

**Explanation:** Creates a new environment variable named `MY_VAR` with the value `"Hello, Linux!"`.

### Verify the variable

**Command:**

```bash
echo $MY_VAR
```

**Explanation:** Displays the value stored in the environment variable.

---

## Conclusion

This assignment was completed using Ubuntu on Windows Subsystem for Linux (WSL). It demonstrates basic Linux commands related to file management, file viewing, searching, compression, downloading files, file permissions, environment variables, and GitHub version control.
(Continue adding the remaining commands...)# Linux Commands Assignment
