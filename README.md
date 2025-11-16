import pypandoc

content = """# 🌿 **Proyecto SUMAK – Landing Page**

<div align="center">
  
🌱 *Capacitación accesible y práctica para microemprendedores peruanos*  
✨ *Impulsando negocios, cambiando vidas*

</div>

---

## 🚀 **Descripción General**
**SUMAK** es una solución digital centrada en ofrecer **microlearning**, **gamificación** y **acompañamiento personalizado** para microemprendedores peruanos que buscan mejorar la gestión y crecimiento de sus negocios.

Este repositorio contiene la **Landing Page oficial** del proyecto SUMAK, diseñada para presentar:

- El propósito de la iniciativa  
- El valor que brinda  
- Los usuarios a los que impacta  
- Las características principales del producto  

---

## 🎯 **Objetivo del Proyecto**
Reducir la brecha de acceso a formación empresarial mediante una plataforma:

✔ accesible  
✔ práctica  
✔ motivadora  
✔ adaptada a baja conectividad  
✔ basada en retos diarios  

---

## 🧑‍🤝‍🧑 **Segmentos Objetivo**
- **Microemprendedores peruanos** (18 a 45 años)  
- **Profesores y facilitadores** de programas de capacitación  
- **Clientes de microempresas** que se benefician del crecimiento del negocio  

---

## 🌟 **Características Principales**
✨ Microlearning práctico  
✨ Retos diarios y recompensas  
✨ IA para personalizar el aprendizaje  
✨ Comunidad emprendedora  
✨ Plataforma web + móvil  
✨ Analítica del progreso  

---

## 🧩 **Tecnologías Utilizadas**
- HTML5  
- CSS3  
- JavaScript  
- Git y GitHub  
- GitFlow para control de versiones  

---

## 📁 **Estructura del Proyecto**

Proyecto-SUMAK/
│
├── README.md
   └── public/
    ├── index.html
     ├── favicon.ico
    └── assets/
├── styles/
│ └── styles.css
├── images/
└── scripts/
└── main.js

---

## 🌱 **Flujo de Trabajo – GitFlow**

🔹 Rama principal → `main`  
🔹 Rama de desarrollo → `develop`  
🔹 Ramas feature → `feature/nombre`  
Ejemplos:  
- `feature/hero-section`  
- `feature/footer`  

---

## 👥 **Autores**
| Integrante | Rol |
|-----------|------|
| Estefany Amaya | Desarrollo / Documentación |
| Matias Flores | Desarrollo |
| **Elynor Palma** | Team Leader |
| Sebastián Suárez | Diseño / Documentación |
| Rosmery Villar | Investigación / Apoyo UX |

---

## 📬 **Contacto**
📧 sumak.startup@gmail.com
"""

output_path = "/mnt/data/README.md"
pypandoc.convert_text(content, 'md', format='md', outputfile=output_path, extra_args=['--standalone'])
output_path
