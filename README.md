#  Lanzador TEU

<div align="center">

![Versión](https://img.shields.io/badge/Versión-1.0-blue?style=for-the-badge&logo=appveyor)
![Python](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python&logoColor=white)
![Plataforma](https://img.shields.io/badge/Plataforma-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Licencia](https://img.shields.io/badge/Licencia-Personal-green?style=for-the-badge)

**Herramienta para la instalación masiva y automatizada de programas en equipos nuevos o formateados**

</div>

---

##  Descripción

**Lanzador TEU** es una aplicación diseñada para facilitar la instalación masiva de programas en equipos nuevos o recién formateados. Permite gestionar un catálogo completo de instaladores, organizarlos por categorías y crear plantillas personalizadas para diferentes necesidades (Oficina, Gaming, Diseño, etc.).

Con soporte para **instalación silenciosa/desatendida**, puedes automatizar todo el proceso de configuración de un equipo en minutos.

---

## ✨ Características Principales

### 🎯 Gestión Completa
- ✅ **Categorías personalizadas**: Organiza tus programas por tipo (Compresores, Imagen, Ofimática, etc.)
- ✅ **Catálogo de programas**: Agrega, edita y elimina instaladores (.exe y .msi)
- ✅ **Detección automática**: Extrae nombre y versión del producto automáticamente
- ✅ **Búsqueda en tiempo real**: Filtra por nombre, versión o categoría

### 🤖 Automatización
- ✅ **Comandos silenciosos**: Soporte para instalación desatendida (/S, /silent, /qn, etc.)
- ✅ **Integración USSF**: Universal Silent Switch Finder para detectar comandos automáticamente
- ✅ **Activadores**: Ejecución automática de keygens o parches post-instalación
- ✅ **Instalación secuencial**: Instala múltiples programas en cola

### 📋 Plantillas
- ✅ **Plantillas predefinidas**: Crea conjuntos de programas para diferentes escenarios
- ✅ **Selección múltiple**: Marca varios programas con checkboxes
- ✅ **Filtrado rápido**: Aplica plantillas con un clic

### 🎨 Interfaz Moderna
- ✅ **Tema oscuro**: Diseño moderno y cómodo para la vista
- ✅ **Notificaciones Toast**: Feedback visual en tiempo real
- ✅ **Tooltips informativos**: Ayuda contextual en cada botón

###  Logs y Reportes
- ✅ **Historial completo**: Registro detallado de todas las instalaciones
- ✅ **Estadísticas**: Programas exitosos y fallidos
- ✅ **Exportación**: Logs en formato texto consultable

### 🔧 Portable
- ✅ **Sin instalación**: Ejecutable directamente desde USB o disco externo
- ✅ **Base de datos local**: SQLite embebido, sin dependencias externas
- ✅ **100% Offline**: No requiere conexión a internet

---

## 📸 Capturas de Pantalla

<div align="center">

| Interfaz Principal | Gestión de Plantillas |
|:---:|:---:|
| ![Principal](<img width="1104" height="685" alt="Interfaz Principal" src="https://github.com/user-attachments/assets/663d6fe1-7505-49bf-8d4c-3ced920eed43" />) | ![Plantillas](https://via.placeholder.com/400x300/1a1a2e/00d9ff?text=Gestion+Plantillas) |
| **Ventana principal con tabla de programas** | **Gestor de plantillas con vista de 2 columnas** |

| Agregar Programa | Ayuda del Instalador |
|:---:|:---:|
| ![Agregar](<img width="702" height="733" alt="Agregar Programa" src="https://github.com/user-attachments/assets/3f7a03c5-be2a-415b-9690-17ea209928d7" />) | ![Ayuda](<img width="752" height="534" alt="Ayuda Instalador" src="https://github.com/user-attachments/assets/ad89981b-91d0-4171-bb07-39e30bca15de" />) |
| **Formulario de agregar programa** | **Extracción de comandos silenciosos** |

</div>

---

## 🚀 Instalación y Uso

###  Descarga

1. Ve a la sección **[Releases](https://github.com/Hellowen6060/LanzadorTEU/releases)** del repositorio
2. Descarga la última versión: `Setup_LanzadorTEU_1.0.exe`
3. Extrae el contenido en tu USB o disco externo

###  Uso Rápido
LanzadorTEU/
├── LanzadorTEU.exe ← Ejecuta este archivo
└── conf/ ← Carpeta de configuración (no eliminar)


### 📋 Primeros Pasos

1. **Crear Categoría**: Clic en "Nueva" → Asigna nombre → Guardar
2. **Agregar Programa**: Selecciona categoría → Clic "Agregar Programa" → Busca el instalador
3. **Configurar Comando Silencioso** (opcional): Usa USSF o /? para extraer comandos
4. **Crear Plantilla** (opcional): Gestiona plantillas para conjuntos de programas
5. **Instalar**: Selecciona programas → Clic "INSTALAR"

---

## ️ Requisitos del Sistema

### Mínimos
- **Sistema Operativo**: Windows 10/11 (64-bit)
- **Espacio en disco**: 50 MB libres
- **RAM**: 2 GB
- **Resolución**: 1280x720

### Recomendados
- **Sistema Operativo**: Windows 10/11 (64-bit) actualizado
- **Espacio en disco**: 100 MB libres
- **RAM**: 4 GB
- **Resolución**: 1920x1080

---

## 📁 Estructura del Proyecto
LanzadorTEU/
├── LanzadorTEU.py # Código fuente principal
├── version.txt # Metadatos del ejecutable
├── README.md # Documentación
├── LICENSE # Licencia
└── conf/ # Carpeta de configuración
├── catalog.db # Base de datos SQLite (auto-generada)
├── ussf.exe # Universal Silent Switch Finder
├── logs/ # Registros de instalación
│ └── instalaciones.log
└── docs/ # Documentación y assets
├── ayuda.txt
├── acerca.txt
├── desarrollo.txt
├── enlaces.txt
├── logo.png
├── logo.ico
└── [iconos redes sociales]


---

📄 Licencia
Este proyecto está bajo la Licencia de Uso Personal y Educativo.

Copyright © 2026 Diego Gamer. Todos los derechos reservados.

Se permite el uso personal y educativo de este software.
Queda prohibida la distribución comercial sin autorización previa.

🙏 Agradecimientos
Universal Silent Switch Finder (USSF) - Herramienta para detección de comandos silenciosos
Python - Lenguaje de programación
Tkinter - Biblioteca GUI
SQLite - Motor de base de datos
La comunidad de desarrolladores por el apoyo y recursos

Apoya el Proyecto
Si te gusta este proyecto, considera darle una estrella ⭐ en GitHub y compartirlo con otros.
<div align="center">

¡Gracias por usar Lanzador TEU! 🚀
Desarrollado con ❤️ por Diego Gamer
</div>
