# Martín Pentito

<p align="left">
  <a href="mailto:martinepentito@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://portafolio-espejo-codigo-html-css-j.vercel.app" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Portfolio-Live-0A66C2?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://github.com/MartinPentito" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress" />
</p>

```python
# profile.py

class Profile:
    """
    ES:
    Apasionado por las computadoras y la música.
    Responsable y autodidacta, características que me definieron desde niño.
    Siempre en busca de experiencias que me saquen de mi zona de confort.
    Disfruto del trabajo en equipo con respeto y empatía.

    EN:
    Passionate about computers and music.
    Responsible and self-taught, traits that shaped me from an early age.
    Always looking for experiences that push me out of my comfort zone.
    I enjoy teamwork built on respect and empathy.
    """

    NAME = "Martín Pentito"
    TITLE_ES = "Artista_Tecnico_Computacion_Electronica"
    TITLE_EN = "Artist_Computers_Electronics_Technician"

    FOCUS_ES = "Desarrollo web, automatización y soporte técnico"
    FOCUS_EN = "Web development, automation, and technical support"

    LOCATION = "Argentina"

    TRAITS_ES = ["Curioso", "Responsable", "Autodidacta", "Empático", "Resiliente", "Social"]
    TRAITS_EN = ["Curious", "Responsible", "Self-taught", "Empathetic", "Resilient", "Social"]

    LANGUAGES = {
        "Español": "Nativo",
        "Inglés": "Básico",
        "Spanish": "Native",
        "English": "Basic"
    }


class Services:
    WEB_DEVELOPMENT = {
        "es": "Desarrollo Web",
        "en": "Web Development",
        "stack": "HTML · CSS · JavaScript · WordPress"
    }

    TECHNICAL_SERVICE = {
        "es": "Servicio Técnico",
        "en": "Technical Service",
        "description_es": "Reparación de computadoras y laptops",
        "description_en": "Computer and laptop repair"
    }

    COMPOSER = {
        "es": "Compositor",
        "en": "Composer",
        "description_es": "Estudio Musical - JipiCueva",
        "description_en": "Music Studio - JipiCueva"
    }


class Stack:
    TECH_STACK = ["HTML", "CSS", "JavaScript", "Python", "SQL", "Git"]
    PLATFORMS = ["Windows", "Mobile", "WordPress", "macOS"]
    TOOLS = ["Visual Studio Code", "GitHub", "XAMPP", "PHPMyAdmin"]


class Projects:
    # Solo proyectos visibles y publicados / Only visible and published projects
    PORTFOLIO_ESPEJO = {
        "name": "Portfolio espejo",
        "type": {
            "es": "Proyecto personal",
            "en": "Personal project"
        },
        "stack": ["HTML", "CSS", "JavaScript", "JSON"],
        "url": "https://portafolio-espejo-codigo-html-css-j.vercel.app",
        "repo": "https://github.com/MartinPentito/Portafolio_espejo_codigo_HTML_CSS_JS",
        "description": {
            "es": "Portfolio estático con estética de editor de código, fuente única de datos en JSON y render dinámico.",
            "en": "Static portfolio with a code-editor aesthetic, single JSON data source, and dynamic rendering."
        }
    }


class Contact:
    EMAIL = "mailto:martinepentito@gmail.com"
    PORTFOLIO = "https://portafolio-espejo-codigo-html-css-j.vercel.app"
    GITHUB = "https://github.com/MartinPentito"

    @staticmethod
    def quick_links_terminal() -> str:
        lines = [
            "[CONTACT]",
            f"├── email     : {Contact.EMAIL}",
            f"├── portfolio : {Contact.PORTFOLIO}",
            f"└── github    : {Contact.GITHUB}",
        ]
        return "\n".join(lines)


if __name__ == "__main__":
    print("ES: Tecnología para resolver problemas. Creatividad para abrir caminos.")
    print("EN: Technology to solve problems. Creativity to open new paths.")
    print()
    print(Contact.quick_links_terminal())
```
