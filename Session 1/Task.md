# Session 1 Task

---

## 1. Create Your Directory

![](Screens/step%201.jpg)

```bash
mkdir "ziad ezzat"
cd "ziad ezzat"
```

---

## 2. Make Another Directory and Create Multiple Files

![](Screens/step%202.jpg)

```bash
mkdir Documents
cd Documents
touch file1.txt file2.txt file3.txt
ls
```

---

## 3. Hide a File

![](Screens/step%203.jpg)

```bash
cd ..
touch .hidden_file
ls -a
```

---

## 4. Write with Nano

![](Screens/step%204.2.jpg)
![](Screens/step%204.1.jpg)

```bash
cd Documents
nano
cat file1.txt
```

---

## 5. Go Back

![](Screens/step%205.jpg)

```bash
cd -
```

---

## 6. Create a Unique Directory

![](Screens/step%206.jpg)

```bash
mkdir "-"
cd ./-
```

---

## 7. Copy Directory

![](Screens/step%207.jpg)

```bash
cd ..
cp Documents My_Documents
ls My_Documents
```

---

## 8.Show Hidden Content

![](Screens/step%208.jpg)

```bash
cat .hidden_file
```

---

## 9.Move Files

![](Screens/step%209.jpg)

```bash
mv Documents/file2.txt Documents/file3.txt ./
ls
```

---

## 10.Remove Your Directory

![](Screens/step%2010.jpg)

```bash
cd ..
rm -r "ziad ezzat"
ls
```

---
