
<p align="center"> 
  <h2 align="center"> Hi there, I am Babaji <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="30px"></h2>
  <h3 align="center"> Data Analyst | Data Science Enthusiast | Python Programmer </h3>
</p>

<p align="center">
<a href="https://www.linkedin.com/in/babajisawant/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" width="85px"/> </a>
<a href="https://www.hackerrank.com/bvsawant1995"><img src="https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" width="100px"/> </a>
<a href="mailto:bvsawant1995@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" width="68px"/> </a>
</p>
<p align="center"> <img src="https://komarev.com/ghpvc/?username=deepak4u&label=Profile%20Visits&color=blue&style=plastic%22%20alt=%22deepak4u" width="95px"/> </p>


- 👨‍💻 I’m currently working on Data Analysis, Web Scraping, ML Model Development and Deployment.
- 📊 I love to explore new technologies and leverage them to solve real-life problem.
- 🌱 Currently learning Django.
- ⚡ Fun fact: Torture the data and it will confess!

***
**⚙️ &nbsp;GitHub Analytics**
<table style="width:100%">
  <tr>
    <td><img src="https://github-readme-stats.vercel.app/api?username=deepak4u&show_icons=true&theme=dark&locale=en&hide_border=true" alt="deepak4u" /></td>
    <td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deepak4u&theme=dark&hide_border=true&layout=compact"></td>
  </tr>
</table>


# Contact me:
import pandas as pd
d = {
    0: [1, 0, 1, 0, 0, 1, 1, 0, 1, 1, 1, 0, 1, 1, 1, 1, 0, 1, 0, 1, 1, 1, 1, 0, 0, 0, 
        1, 1, 0, 1, 0, 1, 1, 0, 1, 0, 1, 1, 1, 0, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0, 0, 1, 
        0, 0, 1, 0, 1, 1, 1, 0, 0, 1, 1, 1, 0, 0, 0, 0, 1, 1, 0, 1, 0, 0, 0, 1, 0, 0],
    1: [6, 16, 29, 14, 23, 24, 25, 37, 27, 26, 20, 29, 5, 0, 32, 19, 0, 10, 22, 3, 30, 8, 22, 4, 11, 2,
        4, 9, 7, 13, 12, 14, 16, 8, 11, 17, 38, 33, 23, 26, 28, 12, 21, 18, 30, 10, 38, 25, 37, 35, 36, 
        28, 15, 3, 31, 19, 21, 36, 17, 13, 9, 35, 7, 2, 27, 34, 24, 31, 18, 15, 1, 1, 6, 5, 32, 34, 20, 33],
    2: [32, 115, 111, 111, 105, 97, 105, 101, 46, 108, 53, 99, 32, 32, 32, 57, 78, 118, 115, 32, 109, 32, 103, 101, 100,
        109, 32, 98, 32, 119, 32, 97, 116, 110, 115, 97, 32, 32, 109, 105, 105, 97, 32, 121, 97, 101, 33, 110, 32, 97, 108,
        99, 32, 98, 32, 32, 64, 32, 49, 116, 101, 32, 32, 32, 102, 116, 103, 110, 57, 110, 117, 32, 115, 114, 116, 32, 97, 32]
}
print (pd.DataFrame(d).pivot(1,0,2).applymap(chr).agg(''.join))
