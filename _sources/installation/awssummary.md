# Overview and setup videos.

```{note}
Disclaimer: Dealing with all these installations may be challenging if you are not from an IT background. Therefore, I have created this page to guide you through the things in a sequential order. You will also find various sources for assistance, including our lectures,  videos, or Office Hours, or a combination of all three. Hopefully, we will all navigate through this week smoothly.
```

## Following are the installations for first week 

- [Setting up conda, environment, and Jupyter notebook](one)
- [Install pgadmin](two)
- [Setting up AWS account](three)
- [Setting up your RDS database](four)
- [Connecting from your Jupyter Notebook to the RDS database](five)
- [Connecting from your pgadmin to the RDS database](six)
- [Loading dumps to your Database](seven)
- [Summary](summary) 


(one)=
## Setting up conda, environment and Jupyter notebook

- Setting up conda, environment, and Jupyter notebook (vscode, jupyterlab is also fine).
- We expect you to know this from your previous courses. But if you still need help, then use the following helpers.

```{admonition} Helpers:
- You can follow the instructions here 
    - [conda](https://ggeorg02.github.io/bait580_2024/installation/conda.html)
    - [JupyterLab](https://ggeorg02.github.io/bait580_2024/installation/jupyterlabtest.html)
- You can use previous year's tutorial recording. [https://canvas.ubc.ca/files/30831874/download?download_frd=1](https://canvas.ubc.ca/files/30831874/download?download_frd=1)
- Tutorial this week by Jordan 5 - 6 pm.
```
(two)=
## Install pgadmin.

- You can follow the instructions here [https://ggeorg02.github.io/bait580_2024/installation/pgadmin.html](https://ggeorg02.github.io/bait580_2024/installation/pgadmin.html)
- Basically, it is to download the pgadmin software for your operating system. 
- Please make sure you download the latest version. 

```{important}
For MAC OS users, download correct file based on your laptop chip.

- pgadmin4-8.1-arm64.dmg -- M1, M2, M3 chip
- pgadmin4-8.1-x86_64.dmg --- INTEL CHIP
```

```{admonition} Helpers:
Tutorial this week by Jordan 5 - 6 pm.
```
(three)=
## Setting up AWS account

```{admonition} Helpers:
- You can follow the instructions here [https://ggeorg02.github.io/bait580_2024/installation/aws.html](https://ggeorg02.github.io/bait580_2024/installation/aws.html)
- I showed you this in lecture 1.
```
(four)=
## Setting up your RDS database.

You need this for your worksheets and assignment 1.

```{admonition} Helpers:
- I will be showing you this in lecture 2.
- You can also check out the YouTube video [https://youtu.be/3OyQ3EeVPNs](https://youtu.be/3OyQ3EeVPNs)
    - 0:00  Setting up RDS database
    - 8:10 IMPORTANT Update security group RDS
```
(six)=
## Connecting from your pgadmin to RDS database.

```{admonition} Helpers:
- You can find information here in the lecture notes. [https://ggeorg02.github.io/bait580_2024/installation/pgadmin.html](https://ggeorg02.github.io/bait580_2024/installation/pgadmin.html)
- You can also check out the YouTube video [https://youtu.be/3OyQ3EeVPNs](https://youtu.be/3OyQ3EeVPNs)  
    - 9:35 Connecting pgadmin to the RDS
- I will also show this in class during lecture 2 time.
```
(seven)=
## Loading dumps to your Database

You need to do this for assignment 1 and worksheet 2.

```{admonition} Helpers:
- You can find information here in the lecture notes. [https://ggeorg02.github.io/bait580_2024/installation/dump.html](https://ggeorg02.github.io/bait580_2024/installation/dump.html) Windows users, make sure you check it.
- I will also show this in class during lecture 2 time.
- You can also check out the YouTube video [https://youtu.be/3OyQ3EeVPNs](https://youtu.be/3OyQ3EeVPNs) 
    - 12:30 Loading dumps to your Database

```

(five)=
## Connecting from your Jupyter notebook to RDS database.

```{admonition} Helpers:
- You can find information in our lecture 2 notes. [https://ggeorg02.github.io/bait580_2024/lectures/lecture2.html#ipython-sql-sql-and-sql](https://ggeorg02.github.io/bait580_2024/lectures/lecture2.html#ipython-sql-sql-and-sql)
- You can also check out the YouTube video [https://youtu.be/3OyQ3EeVPNs](https://youtu.be/3OyQ3EeVPNs) 
    - 18:19 Connecting Jupyter Notebook to the RDS
```
In order to do this correctly, you should know about absolute and relative paths and how to give file location correctly. We expect you know this from your previous courses. But if you still need help, then use the following helpers.

(summary)=
## Summary

Here is the summary of the contents in the YouTube video, which is in sections above. You will also find it in the description of the YouTube video.

[https://www.youtube.com/watch?v=3OyQ3EeVPNs](https://www.youtube.com/watch?v=3OyQ3EeVPNs)  

0:00  Setting up RDS database
8:10 IMPORTANT Update security group RDS
9:35 Connecting pgadmin to the RDS
12:30 Loading dumps to your Database
18:19 Connecting Jupyter Notebook to the RDS