# [Git y GitHub: Conceptos y Comandos Básicos](README.md)

<img src="img/concepto.JPG" alt="Github" width="400"
height="250"/>

---
##  Repositorio
- Carpeta que guarda el proyecto (código, documentación, ejemplos).  
- Tipos: 
  - **Público**: visible para todos.  
  - **Privado**: acceso restringido.  
- **README**: archivo con nombre del proyecto, descripción, uso, licencia, etc.  

Ejemplo:  
```bash
git init   # Inicializa un nuevo repositorio
```

---

##  Ramas
- Copias del proyecto para trabajar en paralelo.  
- **Master/Main**: proyecto original.  
- **Remota/Local**: versiones para desarrollo sin afectar al original.  

Ejemplo:  
```bash
git branch nueva-rama       # Crear una rama
git checkout nueva-rama     # Cambiar a la nueva rama
```

---

##  Clone / Fork
- **Clone**: copia local (offline) del proyecto.  
- **Fork**: copia online en tu perfil de GitHub.  

Ejemplo:  
```bash
git clone https://github.com/usuario/repositorio.git
```

---

##  Commit
- Registro de cambios guardados en la rama local.  

Ejemplo:  
```bash
git add archivo.txt
git commit -m "Descripción del cambio"
```

---

##  Push / Pull Request
- **Push**: enviar cambios a la rama remota.  
- **Pull Request (PR)**: solicitar integración de cambios desde GitHub.  

Ejemplo:  
```bash
git push origin nueva-rama
```

---

##  Merge
- Combina ramas y actualiza el proyecto.  

Ejemplo:  
```bash
git checkout master
git merge nueva-rama
```

---

##  Áreas de trabajo en Git
- **Working Directory**: directorio de trabajo.  
- **Staging Area**: zona de preparación (`git add`).  
- **Repository**: historial de cambios (`git commit`).  

---

##  Definiciones clave
- **Git**: software de control de versiones distribuido.  
- **GitHub**: plataforma web que usa Git para alojar proyectos.  
- **Markdown**: lenguaje de marcas para dar formato a texto en la web.  

---

##  Chuleta rápida de comandos

| Comando | Descripción |
|---------|-------------|
| `git init` | Inicializa un repositorio en la carpeta actual |
| `git clone <url>` | Clona un repositorio remoto en local |
| `git status` | Muestra estado del repositorio |
| `git add <archivo>` | Añade archivo al área de preparación |
| `git commit -m "mensaje"` | Guarda cambios en el repositorio |
| `git branch <nombre>` | Crea una nueva rama |
| `git checkout <rama>` | Cambia de rama |
| `git merge <rama>` | Combina una rama con la actual |
| `git push origin <rama>` | Sube cambios al repositorio remoto |
| `git pull` | Descarga e integra cambios del remoto |
