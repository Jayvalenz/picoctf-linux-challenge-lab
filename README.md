# Picoctf Linux Challenge Lab

Hands-on documentation of beginner-level challenges completed through 
PicoCTF by Carnegie Mellon University, focused on Linux command-line usage,
file inspection, and introductory capture-the-flag (CTF) techniques.

## Objectives
This lab demonstrates practical skills in:

- Linux command-line navigation
- File and string analysis
- Basic enumeration techniques
- Challenge-based problem solving
- Security documentation and evidence collection

---

## Challenges Completed

## Challenge 1: Strings It

**Objective:** Identify a hidden flag in a file without executing it.

**Tools/Commands Used**
```bash
strings strings.1 | grep picoCTF
```

**Concepts Practiced**
- String extraction
- Pattern matching with grep
- Static file analysis

Screenshots:  
`/challenge-1-strings-it/screenshots/`

---

## Challenge 2: Obedient Cat

**Objective:** Locate and read a flag stored in a file.

**Tools/Commands Used**
```bash
ls -al
cat flag
```

**Concepts Practiced**
- File enumeration
- Hidden file discovery
- File content inspection

Screenshots:  
`/challenge-2-obedient-cat/screenshots/`

---

## Challenge 3: Tab, Tab, Attack

**Objective:** Navigate complex file paths and retrieve the flag.

**Tools/Commands Used**
```bash
cat fang-of-haynekhtnamet
```

**Concepts Practiced**
- Directory navigation
- Relative paths
- File access in Linux

Screenshots:  
`/challenge-3-tab-tab-attack/screenshots/`

---

## Skills Demonstrated

- Linux
- Bash
- grep
- strings
- File Enumeration
- CTF Methodology
- Cybersecurity Fundamentals

---

## Repository Structure

```text
picoctf-beginner-writeups/
├── README.md
├── challenge-1-strings-it/
│   └── screenshots/
├── challenge-2-obedient-cat/
│   └── screenshots/
└── challenge-3-tab-tab-attack/
    └── screenshots/
```

---

## Platform
Challenges completed via PicoCTF  
https://picoctf.org