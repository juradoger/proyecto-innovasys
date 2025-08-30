# Proyecto InnovaSys - Automatización con Ansible
## Descripcion
Playbook de Ansible para configurar un servidor Ubuntu 24.04 con Apache y Samba para la startup InnovaSys, cumpliendo con los requisitos del desafio DevOps.
## Servicios Configurados
- Apache: Servidor web con pagina de bienvenida personalizada usando plantilla Jinja2
- Samba: Recurso compartido seguro para el equipo de desarrollo.
## Requisitos Previos
- Ansible instalado en el nodo de control (Linux Lite)
- Servidor Ubuntu 24.04 con acceso SSH configurado 
- Clave SSH configurada para acceso sin contraseña
## Ejecucion del Playbook
# Clonar el repositorio
git clone https://github.com/juradoger/proyecto-innovasys.git
cd proyecto-innovasys
# Ejecutar el playbook (pedirá contraseña sudo)
ansible-playbook site.yml --ask-become-pass
