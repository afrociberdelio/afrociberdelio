### 🌟 Hey! I’m Mikael! 😊  

Passionate about technology, I turn ideas into code that connects people and solves problems. 🚀  

As a **Python developer**, I specialize in **FastAPI**, **Flask** and **Django**, building robust applications and stunning interfaces.  

Expertise in **databases** like **MongoDB**, **PostgreSQL**, and **MySQL**, always aiming for efficiency and scalability.  

An **Computer Network** undergraduate at **Est'acio de Sá University**, I’m always ready to innovate and deliver impactful solutions.  

**Python Backend Developer** at **Natura&Co**, an Cosmetics e-commerce . 🚀

---


 <div>
  <a href="https://github.com/afrociberdelio">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=afrociberdelio&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>
  
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=afrociberdelio&layout=compact&langs_count=7&theme=algolia"/>
</div>

 ![Streak](https://streak-stats.demolab.com/?user=afrociberdelio&theme=algolia)

 ## Techs:
    
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=plastic&logo=c&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
    
 ## Social:
   
  <a href="https://www.instagram.com/afrociberdelio/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
   <a href = "mailto:contato@mikaelsouza.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/mikaeldevs/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
 

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>
 
    
```python
# app/main.py (FastAPI)
from fastapi import FastAPI
from fastapi.responses import JSONResponse

app = FastAPI()

@app.get("/api/message")
async def get_message():
    return JSONResponse(content={"message": "Mikael with FastAPI magic!"})

```
