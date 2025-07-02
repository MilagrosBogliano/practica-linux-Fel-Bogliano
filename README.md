# Trabajo Práctico – Administración de Sistemas Linux con Vagrant 🐧

🔗 **Repositorio en GitHub:**   
[https://github.com/MilagrosBogliano/practica-linux-Fel-Bogliano](https://github.com/tu-usuario/practica-linux-Fel-Bogliano)

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

- Cada alumno ejecutó `neofetch` en su VM y agregó la salida a `system_info.txt` de forma colaborativa sin sobrescribir a otros.

## 🖥️ Vista previa de Neofetch
===== NEOFETCH DE BOGLIANO =====
            .-/+oossssoo+/-.               vagrant@linux-practice
        `:+ssssssssssssssssss+:`           ----------------------
      -+ssssssssssssssssssyyssss+-         OS: Ubuntu 22.04.5 LTS x86_64
    .ossssssssssssssssssdMMMNysssso.       Host: VirtualBox 1.2
   /ssssssssssshdmmNNmmyNMMMMhssssss/      Kernel: 5.15.0-140-generic
  +ssssssssshmydMMMMMMMNddddyssssssss+     Uptime: 1 hour, 43 mins
 /sssssssshNMMMyhhyyyyhmNMMMNhssssssss/    Packages: 693 (dpkg), 4 (snap)
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Shell: bash 5.1.16
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Resolution: 1024x768
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   Terminal: /dev/pts/0
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   CPU: 12th Gen Intel i7-1255U (2) @ 2.611GHz
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   GPU: VirtualBox Graphics Adapter
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Memory: 216MiB / 1963MiB
 /sssssssshNMMMyhhyyyyhdNMMMNhssssssss/
  +sssssssssdmydMMMMMMMMddddyssssssss+
   /ssssssssssshdmNNNNmyNMMMMhssssss/
    .ossssssssssssssssssdMMMNysssso.
      -+sssssssssssssssssyyyssss+-
        `:+ssssssssssssssssss+:`
            .-/+oossssoo+/-.




===== NEOFETCH DE FEL =====
            .-/+oossssoo+/-.               vagrant@linux-practice
        `:+ssssssssssssssssss+:`           ----------------------
      -+ssssssssssssssssssyyssss+-         OS: Ubuntu 22.04.5 LTS x86_64
    .ossssssssssssssssssdMMMNysssso.       Host: VirtualBox 1.2
   /ssssssssssshdmmNNmmyNMMMMhssssss/      Kernel: 5.15.0-140-generic
  +ssssssssshmydMMMMMMMNddddyssssssss+     Uptime: 1 hour, 47 mins
 /sssssssshNMMMyhhyyyyhmNMMMNhssssssss/    Packages: 692 (dpkg), 4 (snap)
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Shell: bash 5.1.16
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Resolution: 1024x768
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   Terminal: /dev/pts/2
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   CPU: AMD Ryzen 5 5500 (2) @ 3.593GHz
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   GPU: VirtualBox Graphics Adapter
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Memory: 228MiB / 1963MiB
 /sssssssshNMMMyhhyyyyhdNMMMNhssssssss/
  +sssssssssdmydMMMMMMMMddddyssssssss+
   /ssssssssssshdmNNNNmyNMMMMhssssss/
    .ossssssssssssssssssdMMMNysssso.
      -+sssssssssssssssssyyyssss+-
        `:+ssssssssssssssssss+:`
            .-/+oossssoo+/-.

===== NEOFETCH DE TERCER PERSONA =====
[?25l[?7l[0m[31m[1m            .-/+oossssoo+/-.
        `:+ssssssssssssssssss+:`
      -+ssssssssssssssssssyyssss+-
    .ossssssssssssssssss[37m[0m[1mdMMMNy[0m[31m[1msssso.
   /sssssssssss[37m[0m[1mhdmmNNmmyNMMMMh[0m[31m[1mssssss/
  +sssssssss[37m[0m[1mhm[0m[31m[1myd[37m[0m[1mMMMMMMMNddddy[0m[31m[1mssssssss+
 /ssssssss[37m[0m[1mhNMMM[0m[31m[1myh[37m[0m[1mhyyyyhmNMMMNh[0m[31m[1mssssssss/
.ssssssss[37m[0m[1mdMMMNh[0m[31m[1mssssssssss[37m[0m[1mhNMMMd[0m[31m[1mssssssss.
+ssss[37m[0m[1mhhhyNMMNy[0m[31m[1mssssssssssss[37m[0m[1myNMMMy[0m[31m[1msssssss+
oss[37m[0m[1myNMMMNyMMh[0m[31m[1mssssssssssssss[37m[0m[1mhmmmh[0m[31m[1mssssssso
oss[37m[0m[1myNMMMNyMMh[0m[31m[1msssssssssssssshmmmh[0m[31m[1mssssssso
+ssss[37m[0m[1mhhhyNMMNy[0m[31m[1mssssssssssss[37m[0m[1myNMMMy[0m[31m[1msssssss+
.ssssssss[37m[0m[1mdMMMNh[0m[31m[1mssssssssss[37m[0m[1mhNMMMd[0m[31m[1mssssssss.
 /ssssssss[37m[0m[1mhNMMM[0m[31m[1myh[37m[0m[1mhyyyyhdNMMMNh[0m[31m[1mssssssss/
  +sssssssss[37m[0m[1mdm[0m[31m[1myd[37m[0m[1mMMMMMMMMddddy[0m[31m[1mssssssss+
   /sssssssssss[37m[0m[1mhdmNNNNmyNMMMMh[0m[31m[1mssssss/
    .ossssssssssssssssss[37m[0m[1mdMMMNy[0m[31m[1msssso.
      -+sssssssssssssssss[37m[0m[1myyy[0m[31m[1mssss+-
        `:+ssssssssssssssssss+:`
            .-/+oossssoo+/-.

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
