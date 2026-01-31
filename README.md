# ==========================================
# CONFIGURAÇÃO DE TEMA (O seu "Root")
# ==========================================
# Coloque a cor aqui (sem o #) e ela muda o README inteiro
THEME_COLOR = "0077B5"  

# ==========================================
# O TEMPLATE
# ==========================================
markdown_template = f"""
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color={THEME_COLOR}&height=250&section=header&text=Lucas%20Sá&fontSize=90&animation=fadeIn&fontAlignY=38" />

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color={THEME_COLOR}&center=true&vCenter=true&width=450&lines=Statistics+%26+Data+Science;Cloud+%26+ML+Enthusiast;Python+%26+R+Developer;Gamer+%26+Teacher" alt="Typing SVG" />
  </a>
  
  <br/>

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-{THEME_COLOR}?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-s%C3%A1-140a66368/)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saa_lucas.wrk@outlook.com)
  [![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/saa-luc-as?tab=repositories)
  [![Lattes](https://img.shields.io/badge/Lattes-00AEEF?style=for-the-badge&logo=cv&logoColor=white)](http://lattes.cnpq.br/ID_DO_SEU_LATTES)

</div>

---

### ⚡ About Me:
<div align="center">

Final-year Statistics student at UFC | Technical Project Support @ Gauss Jr.  
Dedicated to bridging statistical rigor with scalable cloud infrastructures.

`Machine Learning` • `Cloud Infrastructure` • `Statistical Consulting`

</div>

---

### 🛠️ My Tech Stack:
<div align="center">

| | | | | |
| :---: | :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) | ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white) | ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) | ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) |
| ![AWS](https://img.shields.io/badge/AWS-%23232F3E.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) | ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) | ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=microsoftpowerbi&logoColor=black) | ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white) |

</div>

---

### 🎓 Ongoing Learning & Education:
<div align="center">

| Course / Certification | Institution (Link) | Status |
| :--- | :---: | :---: |
| **B.S. in Statistics** | **UFC** | *Expected 2026* |
| Machine Learning com Python | [![USP/ESALQ](https://img.shields.io/badge/MBA_USP%2FESALQ-{THEME_COLOR}?style=flat-square&logoColor=white)](https://mbauspesalq.com/minicursos/introducao-ao-machine-learning-com-python) | *In Progress* |
| Azure Data Scientist (DP-100) | [![DIO](https://img.shields.io/badge/DIO_Bootcamp-{THEME_COLOR}?style=flat-square&logoColor=white)](https://www.dio.me/bootcamp/microsoft-certification-challenge-dp-100) | *In Progress* |
| AWS Cloud Foundations (CLF-C02) | [![Escola da Nuvem](https://img.shields.io/badge/Escola_da_Nuvem-{THEME_COLOR}?style=flat-square&logoColor=white)](https://escoladanuvem.org/) | *In Progress* |
| Microsoft Python Developer | [![Coursera](https://img.shields.io/badge/Coursera-{THEME_COLOR}?style=flat-square&logo=coursera&logoColor=white)](https://www.coursera.org/professional-certificates/microsoft-python-developer) | *In Progress* |
| Microsoft Data Visualization | [![Coursera](https://img.shields.io/badge/Coursera-{THEME_COLOR}?style=flat-square&logo=coursera&logoColor=white)](https://www.coursera.org/professional-certificates/microsoft-data-visualization) | *In Progress* |

</div>

---

### 📊 GitHub Activity:
<div align="center">
  <img height="170" src="https://github-readme-stats-rosy-sigma-80.vercel.app/api?username=saa-lucas&show_icons=true&theme=dark&icon_color={THEME_COLOR}&text_color=ffffff&title_color={THEME_COLOR}&include_all_commits=true&count_private=true" />
  <img height="170" src="https://github-readme-stats-rosy-sigma-80.vercel.app/api/top-langs/?username=saa-lucas&layout=compact&theme=dark&hide_border=false&title_color={THEME_COLOR}&icon_color={THEME_COLOR}&count_private=true" />
</div>

---

<div align="center">

  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&quote=In%20God%20we%20trust;%20all%20others%20must%20bring%20data.&author=W.%20Edwards%20Deming&quote_color={THEME_COLOR}&author_color={THEME_COLOR}" />
  
  <br/> 
  
  <img src="https://komarev.com/ghpvc/?username=saa-lucas&color={THEME_COLOR}&style=flat-square&label=Profile+Views" alt="Profile Views" />

</div>
"""

# ==========================================
# GERAR O ARQUIVO
# ==========================================
with open("README.md", "w", encoding="utf-8") as f:
    f.write(markdown_template)

print(f"✅ README.md gerado com sucesso usando a cor #{THEME_COLOR}!")
