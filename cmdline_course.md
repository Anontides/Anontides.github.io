---
layout: default
---

## **Introduction**

This course, Essential Tools for Language Technology, or previously known as Command Line Tools for Linguists, is aimed for those
who are eager to learn the basic and most essential command line tools used in language technology. On this course you will learn, 
for example, to operate in a Unix-like environment, process text data, run programs and use remote servers and version control tools. 
As a final project you will learn the basics of web page development.

The link to the course page:  
[Essential Tools for Language Technology](https://studies.helsinki.fi/courses/course-unit/otm-c13d30ee-e5cc-4e1c-b8b3-67883288b9a4/KIK-LG221?cpId=hy-lv-77)

### **Module 1**

In this module, we explored the basics of command line tools. We set up the environment and got to know some basic commands, as well 
as the the basic structure of the Unix-like environment. Learning these has proven to be very useful throughout the course.  
Some commands  
1. for directories
   * mkdir (make directory)
   * rm -R (remove non-empty directory)
   * cd (change working directory)
2. for (text) files
   * cp (copy a file)
   * mv (move or rename files)
   * nano (open a file in a text editor)
   * cat (reads the contents of a file)
3. others
   * ls (list files and directories)
   * pwd (print working directory)
   * echo (writes to files or echoes a text)

### **Module 2**

In this module, we focused on text processing. We learned some regular expressions (RegEx), character encodings and the essential 
commands for manipulating text files.

Here is an example of piped text processing commands:  
```bash
cat life_of_bee.txt | dos2unix | sed 's/^$/#/' | tr '\n' ' ' | sed -E 's/([.?!]) ([A-Z])/\1# \2/g' | sed -E 's/([IVX][.])#/\1/g' 
| tr '#' '\n' | sed 's/^ *//' | sed 's/ *$//' | grep -v "^$" | less
```
This uses sed for text subtitution, tr for replacing characters and grep for searching and removing characters.

### **Module 3**

x

### **Module 4**

x

### **Final Assignment**
