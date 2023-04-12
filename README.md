# SOS-projekt
## Description
This is repository for project from BPC-SOS. Goal of this project is to make CentOS Stream 9 as small as possible. It must be able to open website in browser and pdf document. It's a minimal install, for browser I chose Otter browser and Xpdf reader. Currently I managed to drop it to 745MB, which is pretty good all things considered. This is my first time actually digging deeper into linux than just basic commands. It's not the best, there is always room for improvement
## Contents of this repo
- **sos.txt** script that installs xorg, otter browser and xpdf as needed. Then it removes everything unnecessary.
- **OS_theory_classics.pdf file** the pdf file that I must be able to open 
- bunch of .rpm files which I wget to CentOS (the mirror links died so I uploaded it here)
## How to run
- first you need to do a minimall install of CentOS Stream 9 (I will not be explaining how to do that here)
after that run
 ```shell
$ yum install wget -y --nogpgcheck
```
and then
 ```shell
$ wget github.com/roadside-picnicx/SOS-projekt/raw/main/sos.txt
```
## Browser and pdf
- to open pdf or browser, simply open xinit, switch directory to **cd home/ja** and user **su ja** and type **xpdf "name"** or **otter-browser "site"**

## Authors
- [REDACTED]
- [REDACTED]
- [REDACTED]
- [REDACTED]
