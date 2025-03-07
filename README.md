# Minimalist Portfolio JSON

Este es un proyecto de portafolio minimalista creado con Astro como primer contacto con el framework. El portafolio es fácil de editar modificando un archivo JSON, y tiene un diseño limpio y claro con la posibilidad de descargarlo en PDF.

## 🚀 Estructura del Proyecto

Dentro de tu proyecto Astro, verás las siguientes carpetas y archivos:

/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── icons/
│   │   │   ├── [GitHub.astro]
│   │   │   ├── [LinkedIn.astro]
│   │   │   ├── [Mail.astro]
│   │   │   ├── [Phone.astro]
│   │   │   ├── [Printer.astro]
│   │   │   ├── [WorldMap.astro]
│   │   │   └── [X.astro]
│   │   ├── sections/
│   │   │   ├── [About.astro]
│   │   │   ├── [Education.astro]
│   │   │   ├── [Experience.astro]
│   │   │   ├── [Hero.astro]
│   │   │   ├── [Projects.astro]
│   │   │   └── [Skills.astro]
│   │   ├── [KeyboardManager.astro]
│   │   └── [Section.astro]
│   ├── layouts/
│   │   └── [Layout.astro]
│   ├── pages/
│   │   └── [index.astro]
│   └── [cv.json]
├── .astro/
├── .vscode/
│   ├── [extensions.json]
│   └── [launch.json]
├── .gitignore
├── [astro.config.mjs]
├── [package.json]
├── [README.md]
└── [tsconfig.json]

🧞 Comandos
Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

Comando	Acción
npm install	Instala las dependencias
npm run dev	Inicia el servidor de desarrollo en localhost:4321
npm run build	Construye el sitio de producción en ./dist/
npm run preview	Previsualiza tu construcción localmente
npm run astro ...	Ejecuta comandos CLI como astro add, astro check
npm run astro -- --help	Obtén ayuda usando el CLI de Astro

📄 Configuración
cv.json
El archivo cv.json contiene toda la información del portafolio, como el nombre, la etiqueta, la imagen, la ubicación, los perfiles sociales, la experiencia laboral, la educación, las habilidades, etc. Puedes editar este archivo para actualizar la información mostrada en el portafolio.

🛠️ Componentes
Los componentes están organizados en la carpeta src/components. Cada sección del portafolio es un componente separado en la carpeta sections. Los íconos están en la carpeta icons.

💻 Layout
El archivo src/layouts/Layout.astro define el diseño general del sitio.


📄 Inspiraciones
Este proyecto está inspirado en la idea de <a href="https://jsonresume.org/schema/">jsonresume.org</a>

Este proyecto utiliza las bases de <a href="https://github.com/midudev/minimalist-portfolio-json">Midudev</a>