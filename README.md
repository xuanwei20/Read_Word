# 📘 Read Word

A simple **C program** that reads words from input or a file and prints them.  
This project demonstrates a basic example of **word reading and text processing** using standard C file I/O and string handling.

---

## 📌 Purpose

The `readword.c` program reads text input and extracts individual words one at a time from either standard input or a specified file.  
This type of functionality is useful for text processing tasks such as:

- Counting words
- Filtering or analyzing text
- Building simple parsers
- Learning how to handle file and input reading in C

The repository includes:

- `readword.c` — the C source code
- `LICENSE` — MIT open source license

---

## 📁 Repository Structure

```
Read_Word/
│
├── readword.c    # C source file to read and print words
├── LICENSE       # MIT License
├── README.md     # This file
└── .gitignore
```

---

## 🛠 Requirements

- **C compiler** (such as `gcc` or `clang`)
- A terminal or command prompt to run compiled executable

---

## ▶️ How to Build & Run

### 1. Compile the Program

Use a C compiler to build the executable:

```bash
gcc readword.c -o readword
```

or with `clang`:

```bash
clang readword.c -o readword
```

### 2. Run the Program

#### Read from Standard Input

```bash
./readword
```

Then type or paste text and press **Enter**.  
The program will parse and print each word.

#### Read from a File

If `readword.c` supports file input (e.g., via file redirection):

```bash
./readword < textfile.txt
```

Or, if the program accepts filename arguments (modify based on your code):

```bash
./readword input.txt
```

*(Check the source code to confirm argument handling.)*

---

## 🧠 What It Teaches

This project teaches:

- How to open and read text data in C
- How to extract tokens (words) from input
- How to iterate over characters and use standard library functions for I/O

A typical approach to reading a word from input in C is to loop over characters and copy letters into a buffer until whitespace or EOF is reached. :contentReference[oaicite:1]{index=1}

---

## 📜 License

This project is licensed under the **MIT License**. :contentReference[oaicite:2]{index=2}

---

⭐ If you find this helpful, feel free to ⭐ star the repository!
