# Proyecto InnovaSys - Automatización con Ansible

## 🎯 Descripción
Playbook de Ansible para configurar un servidor Ubuntu 24.04 con Apache y Samba para la startup InnovaSys.

## 🚀 Servicios Configurados
- Apache: Servidor web con página de bienvenida personalizada
- Samba: Recurso compartido para el equipo de desarrollo

## 📋 Requisitos Previos
- Ansible instalado en el nodo de control
- Servidor Ubuntu 24.04 accesible via SSH
- Clave SSH configurada para acceso sin contraseña

## ⚡ Ejecución
```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/proyecto-innovasys.git
cd proyecto-innovasys

# Ejecutar el playbook
ansible-playbook site.yml
