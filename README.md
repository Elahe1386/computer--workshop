# computer--workshop
# GitHub README Practice for Computer Workshop

## Introduction
This repository is created for the **Computer Workshop** course (Computer Engineering).  
The goal is to practice **GitHub** + **Markdown** and learn how to document a project properly.

### Student Information
- **Name:**  Elahe
- **Major:** Computer Engineering
- **University:**  Tehran Gharb
- **Semester:** 1404-1405

#### Why this repo?
> Because a good `README.md` is the first step to building a professional GitHub profile.

##### What you will see here
- Markdown headings (1 to 6)
- Paragraphs + **bold** + *italic* + ***bold&italic***
- Blockquote
- Ordered + unordered + nested lists
- Code blocks (`python` and `bash`)
- Links
- Table
- Task list
- HTML inside Markdown
- Image (normal link) + optional Base64 section

###### Note
Use this file as a template and replace the placeholders with your real info.

---

## HTML Section
<p align="justify">
This paragraph is written using <b>HTML</b> tags inside Markdown.
You can mix <i>HTML</i> and Markdown when you need more control over formatting.
</p>

<p align="center">
<b>Centered text using HTML</b>
</p>

---

## Headings Demo

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

## Lists Demo

### Unordered List
- Git & GitHub
- Markdown
- Programming
  - Python
  - C/C++
  - Web basics
    - HTML
    - CSS

### Ordered List
1. Create a GitHub repository
2. Clone it on your computer
3. Create/Edit `README.md`
4. Add and commit changes
5. Push to GitHub

### Mixed (Nested) List
- Week 1
  1. Create account
  2. Create repository
- Week 2
  1. Learn Markdown syntax
  2. Write a clean README

---

## Text Formatting Demo
This is **bold** text.  
This is *italic* text.  
This is ***bold and italic*** text.  
This is `inline code` example (`git status`).

---

## Code Blocks

### Python Example
```python
def factorial(n: int) -> int:
"""Return factorial of n."""
if n < 0:
raise ValueError("n must be >= 0")
if n in (0, 1):
return 1
return n * factorial(n - 1)

print("factorial(5) =", factorial(5))
# 1) Clone repository
git clone https://github.com/El@he1386/computer-workshop.git

# 2) Enter the repo folder (some teachers say: "git in" -> means go inside)
cd REPO-NAME

# 3) Check status
git status

# 4) Add files
git add .

# 5) Commit changes
git commit -m "Add README for computer workshop"

# 6) Push to GitHub
git push origin main

A link to a website:
[Myhomepage](https://www.markdownguide.org/basic-syntax/)
Task List
. [x] Create GitHub account
. [x] Create repository
. [x] Add README.md
. [ ] Add more practice files (optional)
. [ ] Final review
![My Image](data:image/png;base64,PASTE_BASE64_TEXT_HERE)
How to get Base64 text:

Use an online converter: “image to base64”
Upload a small PNG/JPG
Copy the generated Base64 string
Replace PASTE_BASE64_TEXT_HERE
Final Notes
This repository is for educational practice and demonstrates different Markdown elements in one file.

Author:  Elahe Alihosseini

Date: 2026-05-30
