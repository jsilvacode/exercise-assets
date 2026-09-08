# 📚 Exercise Assets

Repositorio centralizado de recursos utilizados en ejercicios, ejemplos y materiales educativos de [4Geeks Academy](https://github.com/4GeeksAcademy).

El objetivo de este repositorio es mantener en un único lugar archivos y recursos reutilizables que pueden ser utilizados desde distintos ejercicios y proyectos, evitando duplicar los mismos archivos en múltiples repositorios.

## 📦 Contenido del repositorio

El repositorio contiene distintos tipos de recursos utilizados durante los ejercicios:

```text
exercise-assets/
├── img/            # Imágenes y recursos gráficos
├── javascripts/    # Archivos JavaScript
├── json/           # Datasets y archivos JSON
├── live-demos/     # Recursos utilizados en demostraciones
├── sound/          # Archivos de audio
├── stylesheets/    # Hojas de estilo CSS
├── txt/            # Archivos de texto
├── index.html      # Página principal del repositorio
└── params.json     # Datos y parámetros de configuración
```

## 🎯 Propósito

Este repositorio proporciona una ubicación centralizada y estable para los recursos necesarios en diferentes ejercicios de **4Geeks Academy**.

En lugar de copiar los mismos archivos dentro de cada proyecto, los ejercicios pueden utilizar directamente los recursos almacenados aquí.

Entre ellos se pueden encontrar:

* Imágenes para ejercicios de HTML y CSS.
* Archivos JSON con datos de ejemplo.
* Archivos de texto para ejercicios de procesamiento de datos.
* Recursos de audio.
* Archivos JavaScript y CSS.
* Recursos utilizados en demostraciones y actividades prácticas.

## 🚀 Cómo utilizar los recursos

Los archivos pueden utilizarse directamente mediante su URL correspondiente.

Por ejemplo, si un recurso se encuentra en:

```text
img/example.jpg
```

puede accederse a su versión `raw` mediante:

```text
https://raw.githubusercontent.com/4GeeksAcademy/exercise-assets/master/img/example.jpg
```

De esta manera, los recursos pueden utilizarse desde páginas HTML, aplicaciones JavaScript, notebooks u otros proyectos educativos.

### Ejemplo en HTML

```html
<img
  src="https://raw.githubusercontent.com/4GeeksAcademy/exercise-assets/master/img/example.jpg"
  alt="Imagen de ejemplo"
/>
```

### Ejemplo con JavaScript

```javascript
fetch(
  "https://raw.githubusercontent.com/4GeeksAcademy/exercise-assets/master/json/example.json"
)
  .then((response) => response.json())
  .then((data) => console.log(data));
```

> Los nombres utilizados en los ejemplos son ilustrativos. Debes reemplazarlos por la ruta real del recurso que quieras utilizar.

## 🗂️ Organización de los recursos

Al agregar nuevos archivos, se recomienda mantener la estructura existente:

| Tipo de recurso              | Directorio     |
| ---------------------------- | -------------- |
| Imágenes                     | `img/`         |
| JavaScript                   | `javascripts/` |
| Datos JSON                   | `json/`        |
| Audio                        | `sound/`       |
| Hojas de estilo              | `stylesheets/` |
| Archivos de texto            | `txt/`         |
| Recursos para demostraciones | `live-demos/`  |

Mantener esta organización facilita la búsqueda y reutilización de los recursos.

## 🤝 Contribuciones

Si necesitas agregar o actualizar algún recurso:

1. Realiza un **fork** del repositorio.
2. Crea una nueva rama para tus cambios.
3. Agrega o modifica los archivos necesarios.
4. Utiliza nombres descriptivos y ubica cada recurso en el directorio correspondiente.
5. Realiza un commit con una descripción clara del cambio.
6. Abre un **Pull Request** explicando brevemente el propósito del recurso.

Se recomienda evitar archivos duplicados, innecesarios o excesivamente pesados.

## ⚠️ Importante

Algunos ejercicios pueden utilizar directamente los archivos almacenados en este repositorio.

Por esta razón, **no se recomienda renombrar, mover o eliminar recursos existentes sin verificar previamente dónde están siendo utilizados**.

Modificar la ruta de un archivo podría provocar que otros ejercicios o proyectos dejen de funcionar correctamente.

## 🏫 Acerca de 4Geeks Academy

Este repositorio forma parte de los recursos educativos utilizados por **4Geeks Academy** para apoyar ejercicios, proyectos y actividades prácticas de programación.

* GitHub: [github.com/4GeeksAcademy](https://github.com/4GeeksAcademy)
* Sitio web: [4geeksacademy.com](https://4geeksacademy.com)

---

**Recursos para aprender, practicar y construir.**
