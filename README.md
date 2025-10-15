# GitHub Pages Deployment Project

## 📖 Descripción

Este proyecto demuestra cómo usar **GitHub Actions** para desplegar automáticamente un sitio web estático a **GitHub Pages**.

## 🎯 ¿Qué hace este proyecto?

Cada vez que modificas el archivo `index.html` y haces push a la rama `main`, GitHub Actions automáticamente:
1. Detecta el cambio
2. Ejecuta el workflow de despliegue
3. Publica los cambios en GitHub Pages

## 🚀 Características

- ✅ Despliegue automático con GitHub Actions
- ✅ Solo se despliega cuando `index.html` cambia
- ✅ Sitio web accesible públicamente
- ✅ Sin necesidad de configuración manual

## 🛠️ Tecnologías Utilizadas

- HTML
- GitHub Actions
- GitHub Pages

## 📂 Estructura del Proyecto

```
gh-deployment-workflow/
├── .github/
│   └── workflows/
│       └── deploy.yml      # Workflow de despliegue
├── index.html              # Página web principal
└── README.md               # Este archivo
```

## 🔧 Cómo Funciona

1. **Trigger**: El workflow se activa solo cuando hay un push a `main` que modifica `index.html`
2. **Checkout**: Descarga el código del repositorio
3. **Deploy**: Publica los archivos en GitHub Pages

## 🌐 Ver el Sitio Web

El sitio está disponible en:
```
https://<tu-usuario>.github.io/gh-deployment-workflow/
```

## 📝 Cómo Usar

1. Clona este repositorio
2. Modifica `index.html` como desees
3. Haz commit y push a la rama `main`
4. ¡El sitio se actualiza automáticamente!

## 🎓 Aprendizaje

Este proyecto enseña:
- Conceptos de CI/CD (Integración y Despliegue Continuo)
- Cómo usar GitHub Actions
- Automatización de despliegues
- Configuración de GitHub Pages

## 👨‍💻 Autor

Creado como proyecto de aprendizaje de GitHub Actions

## 📄 Licencia

MIT License - Siéntete libre de usar este código