# Day 3 - Linux File Viewing Commands 📄

## 🎯 Objective

Learn how to read and analyze file contents using Linux commands.

---

## 📌 Commands

### 1. cat

```bash
cat file1.txt
```

Displays the full content of the file.

**Use Case:**
Quickly view small files.

---

### 2. head

```bash
head file1.txt
```

Displays the first 10 lines of the file.

**Use Case:**
Check the beginning of logs or files.

---

### 3. tail

```bash
tail file1.txt
```

Displays the last 10 lines of the file.

**Use Case:**
View recent logs and debug issues.

---

### 4. tail -f

```bash
tail -f file1.txt
```

Continuously monitors the file and displays new lines in real-time.

**Use Case:**
Used to monitor logs while an application is running.

---

### 5. less

```bash
less file1.txt
```

Opens the file in scrollable mode.

**Controls:**

* Press `q` to exit

**Use Case:**
Used for reading large files page by page.

---

## 🧪 Example Practice

```bash
echo "Error: DB connection failed" >> file1.txt
echo "Warning: retrying..." >> file1.txt
echo "Info: service started" >> file1.txt
```

---

## 🧠 Key Learnings

* Learned how to view file contents using different commands
* Understood importance of `tail` for log monitoring
* Practiced reading and analyzing file data
* Understood difference between `cat` and `less`

---

## 🚀 Real World Usage

* Debugging application logs
* Monitoring server activity
* Checking configuration files
* Troubleshooting production issues

---
