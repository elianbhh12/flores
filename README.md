Pasos para generar una imagen desde `noestoy.html` (Windows)

Requisitos:
- Node.js instalado (v16+ recomendado)

Instrucciones:

1. Abre una terminal en la carpeta:

```powershell
cd "d:\Elian\Proyectos\Twitich\Escenas"
```

2. Instala dependencias:

```powershell
npm install
```

3. Genera la imagen (usa el script del package.json):

```powershell
npm run screenshot
```

Esto creará `noestoy.png` en la misma carpeta.

Uso alternativo (pasar archivos personalizados):

```powershell
node capture.js noestoy.html salida.png
```

Notas:
- Puppeteer descargará una versión de Chromium en la primera instalación.
- Si quieres usar Chrome/Chromium ya instalado, edita `capture.js` para pasar el `executablePath` al lanzar el navegador.
# flores
