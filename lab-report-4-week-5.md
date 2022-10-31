# **Lab Report 3** #
---
During this weeks lab report, we were tasked with exploring three different terminal command-line options that are related to one of the three terminal commands `less`, `find`, and `grep`.

---
## **First Command - maxdepth** ##

The first command I explored was the `-maxdepth n` command. Essentially, this command allows the user to limit the find search to a specific directory level. For instance: 

![Image](finddepth.png)

The above code is searching for the Meda file through every directory of technical up until a depth of two. This can be useful when looking for a group of files across different directories excluding their subdirectories. 

![Image](findfalse.png)

This image uses the same `-maxdepth`



Practice with the find command
1. find -path "technical/quiz-layout/biomed" //find the path, File name matches shell pattern pattern.
2. find -links 4 //File has less than, more than or exactly n hard links.
3. find -delete Delete files; true if removal succeeded.  If the removal failed, an error message will be produced.