
# templateFrontAWS

Este es un template personalizado base para desarrollos FrontEnd con NextJS,typescript para iniciar rápidamente nuevos proyectos con la configuración requerida y pipelines de CI/CD ya configurados con despliegue en Amplify.

## Características

- Estructura de carpetas organizada para proyectos
- Configuración de linting y formateo de código
- Tests unitarios configurados
- Pipelines de CI/CD para GitHub Actions
- Configuraciones comunes (.gitignore, .editorconfig, etc.)

## Cómo usar este template

1. En GitHub, navega a la página principal de este repositorio
2. Haz clic en el botón "Use this template" (Usar esta plantilla)
3. Elige un nombre para tu nuevo repositorio
4. Selecciona si deseas que sea público o privado
5. Haz clic en "Create repository from template" (Crear repositorio a partir de la plantilla)

## Configuración inicial

Una vez que hayas creado un nuevo repositorio a partir de este template, necesitarás:

1. Actualizar la información en el archivo `package.json`
2. Revisar y ajustar los workflows de GitHub Actions según tus necesidades
3. Modificar este README con la información específica de tu proyecto

## Estructura de carpetas

```bash
├── .github/
│   └── workflows/       # Configuraciones de GitHub Actions
├── src/                 # Código fuente
├── tests/               # Tests
├── .editorconfig        # Configuración del editor
├── .gitignore           # Archivos ignorados por Git
├── package.json         # Dependencias y scripts
└── README.md            # Este archivo
```

## Pipelines de CI/CD

Este template incluye dos workflows principales:

1. **CI Pipeline**: Se ejecuta en cada push y pull request para verificar la calidad del código
2. **Deploy Pipeline**: Se ejecuta cuando se hace push a la rama main para desplegar el proyecto

## Personalización

Sientete libre de modificar cualquier parte de este template para adaptarlo a tus necesidades específicas.
