# Configuración

Para comenzar a desarrollar código en JavaScript con Node.js, necesitarás instalar algunas herramientas esenciales. Aquí te explico cómo configurar tu entorno de desarrollo:

## Instalación de Node.js

Tienes dos opciones principales para instalar Node.js:

1. Instalación directa:
   - Visita el sitio oficial de Node.js (https://nodejs.org/)
   - Descarga e instala la versión adecuada para tu sistema operativo
   - Sigue las instrucciones del asistente de instalación

2. Usando un gestor de versiones (recomendado):
   - Para Windows: NVM for Windows
   - Para Linux/macOS/WSL: NVM (Node Version Manager)

Usar un gestor de versiones te permite instalar y cambiar fácilmente entre diferentes versiones de Node.js.

## Instalación de Visual Studio Code

Visual Studio Code es un editor de código altamente recomendado para desarrollo con JavaScript/Node.js:

- Descarga el instalador desde: https://code.visualstudio.com
- Ejecuta el instalador y sigue las instrucciones

## Configuración del entorno

### Windows

Para configurar el entorno directamente en Windows:
1. Instala Node.js usando el instalador o NVM for Windows
2. Instala Visual Studio Code
3. Abre una terminal y verifica la instalación con `node --version`

### WSL (Windows Subsystem for Linux)

Para usar Node.js en WSL:
1. Instala y configura WSL 2
2. Instala NVM dentro del entorno Linux
3. Usa NVM para instalar Node.js
4. Instala Visual Studio Code en Windows
5. Instala la extensión "Remote - WSL" en VS Code

## Verificación

Después de la instalación, abre una terminal y ejecuta:

```
node --version
npm --version
```

Esto confirmará que Node.js y npm (el gestor de paquetes) están instalados correctamente.

Con estas herramientas instaladas, estarás listo para comenzar a desarrollar aplicaciones JavaScript con Node.js.
