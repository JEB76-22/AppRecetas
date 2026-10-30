<div align="center">

# 🍽️ AppRecetas

### Descubre qué cocinar. Guarda lo que te encanta.

Una aplicación web ligera para explorar recetas por categoría, consultar sus ingredientes e instrucciones y conservar tus favoritas en el navegador.

<br />

![HTML5](https://img.shields.io/badge/HTML5-estructura-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-estilos-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=111)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

</div>

---

## Sobre el proyecto

**AppRecetas** facilita la búsqueda de ideas para cocinar mediante categorías y fichas de recetas con información práctica. La experiencia está pensada para ser directa: explora, revisa los detalles y guarda los platos que quieras preparar más tarde.

La aplicación obtiene las categorías y recetas desde [TheMealDB](https://www.themealdb.com/) y guarda los favoritos en el almacenamiento local del navegador.

## Funcionalidades

- **Explorar por categoría:** selecciona una categoría para consultar recetas disponibles.
- **Consultar cada receta:** abre una ficha con imagen, instrucciones, ingredientes y cantidades.
- **Guardar favoritos:** agrega o elimina recetas de tu lista personal.
- **Volver a tus recetas:** consulta los favoritos desde una página dedicada.
- **Interfaz adaptable:** componentes de Bootstrap para una experiencia cómoda en distintos tamaños de pantalla.

## Tecnologías

| Tecnología | Uso |
| --- | --- |
| HTML5 | Estructura de las páginas |
| Bootstrap 5 | Componentes y estilos responsivos |
| JavaScript | Interacción, renderizado y consumo de la API |
| TheMealDB API | Categorías y datos de recetas |
| `localStorage` | Persistencia local de favoritos |

El proyecto no requiere un proceso de compilación ni gestores de paquetes: sus archivos estáticos se pueden servir directamente.

## Estructura

```text
AppRecetas/
├── css/
│   └── bootstrap.min.css
├── js/
│   ├── app.js
│   └── bootstrap.bundle.min.js
├── favoritos.html
├── index.html
└── README.md
```

## Puesta en marcha

### Requisitos

- Un navegador moderno.
- Conexión a internet para consultar TheMealDB.
- Python 3 (solo para la opción de servidor local indicada abajo).

### Ejecutar localmente

Desde la carpeta del proyecto, inicia un servidor estático:

```bash
python -m http.server 8000
```

Abre [http://localhost:8000](http://localhost:8000) en el navegador. También puedes abrir `index.html` directamente; el servidor local suele ofrecer un comportamiento más consistente.

## Uso

1. En **Inicio**, elige una categoría.
2. Explora las tarjetas y selecciona **Ver Receta** para abrir el detalle.
3. Usa el botón de favoritos para guardar o quitar la receta.
4. Entra en **Mis Favoritos** para volver a consultar tus recetas guardadas.

## Datos y privacidad

- Las categorías y los datos de las recetas se solicitan a TheMealDB; su disponibilidad depende de ese servicio y de la conexión a internet.
- Los favoritos se guardan en `localStorage` en el navegador actual. No se envían a una cuenta ni se sincronizan entre navegadores o dispositivos.
- Borrar los datos del sitio en el navegador también puede borrar los favoritos guardados.


📞 Contacto
Para más información sobre el proyecto o servicios de desarrollo web:
Proyecto: AppRecetas
Desarrollador: **JEB$DEV**
Correo: j.e.b.inter@gmail.com
Tecnologías: HTML5, CSS3, JavaScript Vanilla


## Autor

**JEB$DEV —  Desarrollador FrontEnd - Javier Berchtold**

- [GitHub](https://github.com/JEB76-22)
- [LinkedIn](https://www.linkedin.com/feed/)
- [Contacto](mailto:j.e.b.inter@gmail.com)

## Licencia

Actualmente, el repositorio no incluye un archivo de licencia. Si deseas reutilizar o distribuir el proyecto, define primero los términos de uso correspondientes.

---

<div align="center">
Hecho con JavaScript ☀️· Una idea sencilla para inspirar tu próxima comida
</div>
