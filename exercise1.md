## Java

Algunos pasos comunes en una configuración de CI incluyen**linting**, **testing** y **building**.

### ¿Cuáles son las herramientas específicas para llevar a cabo estos pasos en el ecosistema del lenguaje que has elegido?

- **Checkstyle**: para definir reglas de estilo, formatos, indentación, etc.  
- **JUnit**: para la ejecución de pruebas unitarias y de integración.  
- **Maven**: para la compilación, gestión de dependencias y empaquetado del proyecto.  

### ¿Qué alternativas hay para configurar la CI además de Jenkins y GitHub Actions?

- **GitLab CI/CD**  
- **AWS CodePipeline**  
- **CircleCI**  
- **Bitbucket Pipelines**

### ¿Sería mejor esta configuración en un entorno autohospedado o en uno basado en la nube? ¿Por qué? ¿Qué información necesitarías para tomar esa decisión?

Para un equipo pequeño de 6 personas que recién comienza y no maneja datos críticos, un servicio **cloud-based** es la mejor opción por su facilidad de uso y bajo costo inicial.

Sin embargo, si el proyecto crece o surgen requisitos estrictos de privacidad y seguridad, en el futuro podría migrarse a un entorno **self-hosted**, lo que daría mayor control sobre la infraestructura y los datos.
