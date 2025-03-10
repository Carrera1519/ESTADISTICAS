# Sistema de Estadísticas de Capacitación y Movilidad Laboral

## Descripción
Sistema web para gestionar y visualizar estadísticas de atendidos y colocados en cursos de capacitación y movilidad laboral. Diseñado para servidores públicos que necesitan manejar información estadística segregada por género y otras categorías relevantes.

## Funcionalidades

- **Carga de datos**: Mediante formularios o archivos Excel
- **Generación de informes**: 
  - Informes de gobierno
  - Estadísticas mensuales
  - Reportes para la Plataforma Nacional de Transparencia
  - Reportes para el Sistema de Integración Programática y Presupuestal de SEFIPLAN Quintana Roo
- **Visualización de datos**: Dashboards con gráficos y métricas clave
- **Repositorio de enlaces**: Acceso directo a plataformas relacionadas

## Tecnologías utilizadas

- HTML5, CSS3, JavaScript
- Bootstrap 5 para el diseño responsivo
- Font Awesome para iconos
- Chart.js para visualizaciones de datos
- Firebase (opcional) para almacenamiento de datos

## Instalación

1. Clona este repositorio
```
git clone https://github.com/TU-USUARIO/sistema-estadisticas-capacitacion.git
```

2. Abre el archivo `index.html` en tu navegador para una versión básica

3. Para la funcionalidad completa con base de datos:
   - Crea una cuenta en Firebase
   - Configura un proyecto nuevo
   - Actualiza las credenciales en el archivo de configuración

## Estructura del proyecto

```
sistema-estadisticas-capacitacion/
├── index.html          # Página principal
├── css/                # Estilos adicionales
├── js/                 # Scripts de JavaScript
│   ├── app.js          # Lógica principal
│   ├── charts.js       # Configuración de gráficos
│   └── firebase.js     # Configuración de Firebase
└── assets/             # Imágenes y recursos
```

## Uso

El sistema permite:
1. Registrar nuevos datos de capacitaciones y colocaciones
2. Consultar estadísticas y generar informes
3. Exportar datos en diferentes formatos
4. Visualizar métricas de desempeño

## Contribuciones

Las contribuciones son bienvenidas. Para contribuir:
1. Haz fork del proyecto
2. Crea una rama para tu funcionalidad (`git checkout -b feature/nueva-funcionalidad`)
3. Haz commit de tus cambios (`git commit -m 'Añadir nueva funcionalidad'`)
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

## Contacto

Para preguntas o soporte, contacta a [tu-correo@ejemplo.com](mailto:tu-correo@ejemplo.com)
Last edited just now
