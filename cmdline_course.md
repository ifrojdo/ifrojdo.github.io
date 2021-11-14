---
layout: default
---

## Command-line Course 2021
During the Command-line tools for linguist course, or KIK-LG221, the aim has been to learn the basics of operating a Unix 
environment using command-line. This course is especially aimed at linguists as we learn how to handle text files and do text processing using command-line tools. In addition to this, the course also introduces the concept of working through remote servers using tools as SSH and Github.   


**The course structure summmary**


Week     | Content | Important commands 
--- | --- | ---
Week 1  | Introduction | `ls`, `pwd`, `whoami`, `cd`, `wget`, `mv`, `cp`, `rm`, `mkdir`, `emacs` 
Week 2  | Navigation | `ls -F`,`cp -R`, `rm -R`, `rmdir`, `which`, `chmod`, `ssh`, `scp`
Week 3  | Basic Corpus Processing | `file`, `dos2unix`, `iconv`, `tr`, `sort`, `uniq`, `head`, `tail`, `wc`, `tr`, `(e)grep` 
Week 4  | Advanced Corpus Processing | `sed`,` -n, -E, //d, //p, s//g`
Week 5  | Scripting and configuration Files |  `printenv`, `echo`, `export`, `if`, `$PATH, $? and $#`, `nano`, `source`
Week 6  | Installing and running programmes | `su`, `sudo`, `passwd`, `apt-get`, `locate`, `pip`, `python3`, `make`
Week 7  | Version control using Github | `git add`, `git commit`, `git pull`, `git push` 


### **Week 1:** Introduction to Command Line
The first week of this course focused on setting up and getting used to the Unix environment. 
We set up our own shells in the introduction week.
We used commands like `pwd`
and `ls` to see our current working directory and to list the items in it. 
Other learning goals were to know how to change directory (with `cd`), fetch files from the internet `wget`, rename copy and move files using `mv`and `cp`. Lastly we also touched upon opening text files using `emacs`. 
 
At the end of the week we were able to set up the dircetory in which we have been working for the rest of the course, namely KIK-219 (which I guess is another code for the same course?).



### **Week 2:** Navigating Unix systems
The second week was split into three distinct parts: the unix system, processes, and remote servers. 
In the first part we looked at the structure of the unix systems with the root, directories and subdirectories and also how to copy, move and delete a directory and how to alter file permissions. Here we also touched upon how to compress and uncompress files using `gzip` and `tar`.
As for the process part, the main focus was how to initialice, identify, monitor and kill processes.
Lastly, in the third part we connected to a remote server using `ssh` and worked in remote terminals using `scp`.  



### **Week 3:** Basic Corpus Processing
The third consisted of learning how command-line can be used in text processing, with the first key lesson concerning encoding systems, such as ASCII and utf-8, and converting between these systems.
After the initial introduction we started working on text files using `wc`for word count, for example, `sort` for sorting lines into alphabetical order, and `tr`to make changes throughout the text file.   


### **Week 4:** Advanced Corpus Processing
After the previous week of basic text processing, the fourth week delved into more advenced methods, which was by using piplines in combination with `sed`. The `sed` command is used to transform texts similar to the previously mentioned `tr` command, however, `sed` is more flexible and can be used for many different things such as full line substitution, and deletion. 
This command was then used in combination with other commands to create pipelines that are a streamlined and more efficient tool to perform actions. 
We used this to create frequnecy lists, and n-grams.   


### **Week 5:** Scripting and Configuration Files
In this week of the couse we got accquainted with writing bash scripts. These scripts involved variables of different kinds, we also did if statements and other fun stuff. 
We learned how to set up our own variables, such as adding new paths to the `$PATH`variable.
We further learned how to personalice the `.bashrc` file, a.k.a the bash configuration file according to our own wishes.  

### **Week 6:** Installing and Running Programmes
In content of the sixth week conatined information about how to install programmes and packages to your local terminal using different methods depending on the operating system of your computer. 
In order to install said software we had to get the permissions, or rather overriding this by becoming the root user with either `su` or `sudo`
We then used the python specific `pip` command to get packages related to python code. 


Lastly we learned how to use python to use Makefiles that dealt with variables and could be used to work on multiple text files at once. 

### **Week 7:** Version Control using Github
For the last week we learned about the general structure of working on a collaborate project using Github. 
We learned how to set up a repository, how to add files, commit them and to pull and push any changes made within the repository. As a precaution we also studied how to reverse adds and commits and how to safely branch the master and to merge it back together. 




## A last word of advice:
Do ask for help if you're stuck. There are students who are stuck with the same issue, and the techers are more than willing to help. Google and Stack overflow are also helpful (but be cautious), and sometiiiimes, even the error code provides you with helpful information. 
![Joke about error messages](https://xkcd.com/2200)
