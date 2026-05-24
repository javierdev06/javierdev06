<div align="center">

![Banner](https://github.com/javierdev06/javierdev06/blob/main/banner.png?raw=true)

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=4A90D9&center=true&width=500&lines=Hola%2C+soy+Javier+Cortes;Desarrollador+Web+Frontend;Creando+interfaces+modernas)

</div>

---

## Sobre mí

- Desarrollador Web Frontend especializado en crear interfaces limpias y funcionales
- Trabajo con **HTML, CSS, JavaScript y React**
- Actualmente aprendiendo **TypeScript y desarrollo Fullstack**
- Me interesa construir **aplicaciones web con impacto real**

---

## Stack Tecnológico

**Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**Bases de datos**

![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

**DevOps y Herramientas**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## Proyectos Destacados

### FGAL Construcciones
> Sitio web profesional para empresa constructora con dominio propio

![HTML5](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

[![Ver sitio](https://img.shields.io/badge/Ver_sitio_web-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://fgalconstrucciones.com)

---

### Provisiones El Retiro
> Tienda web completa con carrito de compras, panel de administración y base de datos

![HTML5](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

[![Repositorio privado](https://img.shields.io/badge/Repositorio_privado-333333?style=for-the-badge&logo=github&logoColor=white)]()

---

## Código Destacado

```python
# PROVISIONES EL RETIRO — Servidor seguro con Flask
# Middleware de seguridad con headers HTTP

@app.before_request
def bloquear_sensibles():
    path   = request.path.lstrip("/")
    nombre = path.split("/")[-1]
    if nombre in BLOQUEADOS or path.startswith("."):
        abort(403)

@app.after_request
def security_headers(resp):
    resp.headers["X-Frame-Options"]        = "SAMEORIGIN"
    resp.headers["X-Content-Type-Options"] = "nosniff"
    resp.headers["Referrer-Policy"]        = "strict-origin-when-cross-origin"
    return resp

def get_db():
    conn = sqlite3.connect(DB_PATH)
    conn.row_factory = sqlite3.Row
    conn.execute("PRAGMA journal_mode=WAL")
    conn.execute("PRAGMA foreign_keys=ON")
    return conn
```

---

## Actividad Actual

- Trabajando en: proyectos web personales
- Aprendiendo: TypeScript y desarrollo Fullstack
- Objetivo actual: construir un portfolio profesional completo

---

## Contacto

[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:javier.dev06@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/javierdev06)

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=javierdev06&color=4A90D9&style=for-the-badge)

</div>
