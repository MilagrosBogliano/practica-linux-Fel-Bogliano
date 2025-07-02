# Trabajo Práctico – Administración de Sistemas Linux con Vagrant 🐧

🔗 **Repositorio en GitHub:**   
[https://github.com/MilagrosBogliano/practica-linux-Fel-Bogliano](https://github.com/MilagrosBogliano/practica-linux-Fel-Bogliano)

**Grupo:**  
- Lucas Agustin Fel Tajes  
- Milagros Vanesa Bogliano

## 🎯 Objetivo General

Aplicar conocimientos de administración de sistemas Linux, virtualización, control de versiones y contenedores en un entorno colaborativo utilizando Vagrant, Git y Docker.

---

## 📁 Estructura del Proyecto
![EstructuraDelProyecto](https://github.com/user-attachments/assets/fcd08083-062a-4358-b1c6-be9452f133e7)


## ✅ Ejercicios Realizados

### 1. 🛠️ Configuración Inicial y Git

- Se creó el repositorio público en GitHub.
- Cada alumno configuró su Git local, clonó el repo y colaboró con commits.
- Se armó la estructura de carpetas según el enunciado.

---

### 2. 📸 Neofetch Colaborativo
[https://github.com/MilagrosBogliano/practica-linux-Fel-Bogliano/tree/main/neofetch](https://github.com/MilagrosBogliano/practica-linux-Fel-Bogliano/tree/main/neofetch)

- Cada alumno ejecutó `neofetch` en su VM y agregó la salida a `system_info.txt` de forma colaborativa sin sobrescribir a otros.

## 🖥️ Vista previa de Neofetch
===== NEOFETCH DE BOGLIANO =====
 
 ![neofetch_bogliano](https://github.com/user-attachments/assets/f6acf628-bdd9-4f4a-8b53-51277946154e)

===== NEOFETCH DE FEL =====

![neofetch_fel](https://github.com/user-attachments/assets/65d0fa19-1bcf-463b-9606-1cdfa58fd60b)

===== NEOFETCH DE TERCER PERSONA =====

![neofetch_tercer_persona](https://github.com/user-attachments/assets/0a683007-064e-42d2-a64e-3de072cc3bcd)

---

### 3. 👥 Gestión de Permisos y Usuarios

- Se crearon directorios personales con permisos adecuados.
- Se crearon usuarios locales (`usuario1`, `usuario2`, etc.).
- Se configuró el grupo `equipotrabajo`.
- Verificaciones guardadas en `usuarios_*.txt` y `verificacion_permisos.txt`.

---

### 4. 💽 Administración de Discos

- Cada alumno particionó, formateó, montó y configuró el montaje automático de un disco adicional.
- Se verificó espacio, montaje y `fstab`.

---

### 5. 📂 Archivos y Directorios

- Se creó la estructura `proyectos/`, `respaldos/`, `temporal/`.
- Se generaron archivos, se copiaron, movieron y eliminaron según indicaciones.
- Verificación guardada en `verificacion_archivos.txt`.

---

### 6. 🐳 Contenedores y Docker Compose

Se levantó el servicio Pi-hole utilizando Docker Compose.

Cada alumno realizó la verificación en su propia VM:

#### ✅ Fel
- Contenedor en ejecución
- Respuesta del servicio vía curl
- Capturas:
- ![pihole_fel](https://github.com/user-attachments/assets/37ad3e0e-7265-49f1-ab48-57ef51559b6d)

#### ✅ Bogliano
- Contenedor en ejecución
- Cambio de contraseña manual dentro del contenedor
- Capturas:
 ![pihole_bogliano](https://github.com/user-attachments/assets/97833a70-b5d3-4c0a-a3e6-899442d8bf0c)

#### ✅ Tercer_persona
- Verificación idéntica, funcionamiento confirmado
- Capturas:
- ![pihole_tercer_persona](https://github.com/user-attachments/assets/696b9d38-24a4-4c11-9124-f6ea963b0670)

---

## 💡 Conclusiones

- Se logró cumplir con todos los objetivos del trabajo práctico.
- Se trabajó de forma colaborativa usando Git, coordinando roles y resolviendo conflictos.
- Cada alumno validó el funcionamiento de servicios reales como Pi-hole en su entorno virtualizado.
- Se afianzaron conceptos de permisos, discos, scripting, y uso de herramientas como Docker y Vagrant.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

- Ubuntu 22.04 (Vagrant Box)
- Vagrant + VirtualBox
- Git y GitHub
- Docker y Docker Compose
- Neofetch
- Bash, Fdisk, Mkfs, Mount
