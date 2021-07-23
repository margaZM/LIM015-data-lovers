# Olympia 

## Índice :page_facing_up:

* [1. Definición del producto](#1-resumen-del-proyecto)
* [2. Definición de usuarios](#2-objetivos-de-aprendizaje)
* [3. Plan de acción](#3-plan-de-accion)
* [4. Diseño](#3-diseño)
* [5. Tecnologías empleadas](#5-tecnologias-empleadas)
* [6. Checklist](#9-checklist)

***

## 1. Definición del producto :pencil:

Olympia es una página web donde podrás encontrar los datos más resaltantes de los Juegos Olímpicos celebrados el año 2016 en la ciudad de Río de Janeiro de Brazil. En ella además de ver la imágenes más resaltantes del evento podrás filtrar por diferentes categorás como género, edad y medallas ganadas o realizar una búsqueda personalizada desde el input de buscar, también podrás ordenar de manera ascendente y descendente y observar el ranking de medallas obtenidas de acuerdo a cada pais y hacemos una espeial consideración en destacar la participación de las mujeres y sus logros.


## 2. Definición de usuarios :woman: :man:

Los usuarios de Olympia son personas aficionadas a los deportes que quieren obtener información de sus atletas favoritos o los representantes de sus paises, tambíen es usado por periodistas ya que pueden hacer búsquedas inmediatas de un atleta en particular o pueden obtener información de acuerdo a filtros como genero por ejemplo así como verificar las estadisticas para analizar y hacer sus notas periodísticas en un corto tiempo.

- [ ] **Historias de usuario**

> **Historia 1**  
*Yo como  usuario quiero:* Ver las imágenes más impactantes de los Juegos OLimpicos y un resumen del evento.

> **Historia 2**  
*Yo como  usuario quiero:* Un buscador para encontrar fácilmente la información de mi atleta favorito o grupos de atletas por pais y disciplina deportiva.

> **Historia 3**  
*Yo como investigador quiero:* Un botón para ordenar la información por orden alfabético y por la edad de los participantes.

> **Historia 4**  
*Yo como investigador quiero:* Un botón para filtrar por categorías y poder agrupar por género y medallas ganadas. 

> **Historia 5**  
*Yo como investigador quiero:* Un botón para filtrar por estadísticas y  poder ver los paises con el total de medallas ganadas. 

> **Historia 6**  
*Yo como investigador quiero:* Ver el porcentaje de medallas ganadas por mujeres. 

##.Criterios Minimos de aceptación del proyecto :wrench:
- [x] Mostrar la data en una interfaz: puede ser un card, una tabla, una lista,
   etc.
- [x] Permitir al usuario interactuar para obtener la infomación que necesita.
- [x]Ser _responsive_, es decir, debe visualizarse sin problemas desde distintos
   tamaños de pantallas: móviles, tablets y desktops.
- [x]Que la interfaz siga los fundamentos de _visual design_.

## 3. Plan de acción: :writing_hand:

El plan de acción lo manejamos desde la plataforma Trello en este [link](https://trello.com/b/RwY7grMN/sprint-4) se puede ver a detalle la ejecución del mismo.

## 4. Diseño :sparkles: 

### Uso de la aplicación  
- Se presenta una ventana con un input de tipo texto que permite buscar por nombre de atletas, pais y deportes.
- Se presenta un botón de Atletas que lleva hacia la data de atletas participantes.
- Se presenta un botón de Deportes que lleva hacia la data filtrada de las disciplinas deportivas que se llevaron a cabo y los atletas segun cada caso.
- Se presenta un botón de Estadísticas que muestra las medallas ganadas por cada país participante.

### Prototipo de baja fidelidad
![sitemap](https://github.com/margaZM/LIM015-data-lovers/blob/main/src/images/prototipo-baja.png?raw=true)

### Testeos de usabilidad
-Para mejorar la forma de interactuar en la aplicación agregamos un botón de inicio para volver hacia la Home Page que no estuvo considerado en el prototipo inicial.
- Para una mejor vision de los card de atletas ocultamos la lista de categorías de filtrado que se activará solo cuando se le da click al botón ubicado en la parte superior izquierda.

### Prototipo final en figma

-El diseño completo se puede ver con más detalle en el siguiente [link](https://www.figma.com/file/Y8I0JNiADsrKFwaJxwscMH/Untitled?node-id=0%3A1)

![diseñofinal](https://github.com/yesireth/LIM015-data-lovers/blob/main/src/images/Prototipo%20de%20alta%20fidelidad.JPG?raw=true)

## 5. Tecnologías empleadas :hammer:

- [ ] [HTML:](https://developer.mozilla.org/es/docs/Web/HTML) Siguiendo las reglas del HTML semántico se estructuró con un `header` que contiene el logo y barra de navegación y el input de busqueda, el `main` para englobar el contenido principal y en el `footer` se detalla los derechos de autor y barra de navegación.

- [ ] [CSS:](https://developer.mozilla.org/es/docs/Web/CSS) Usada para definir el estilo visual del proyecto.

- [ ] [Javascript:](https://developer.mozilla.org/es/docs/Web/JavaScript) Para dar la funcionalidad a la aplicación en donde se crearon las siguientes archivos:

- `src/main.js`: Engoba todo el código relacionado con la interacción con el DOM.

- `src/data.js`: Contiene toda la funcionalidad que corresponde a obtener, procesar y manipular datos donde se crearon las siguientes funciones:

> - `function filterData()` Para filtrar la información de acuerdo a medallas, género y edades y para remover datos repetidos en la data.
> - `function orderData()` Para ordenar la información de acuerdo a orden alfabético ascendente y descendente y también por edades de los participantes.
> - `function statisticsData()` Para mostrar los datos estadísticos.

- [ ]  [Jest:](https://jestjs.io/docs/es-ES/getting-started) Framework para realizar los testing unitarios.

- [ ]  [Eslint:](https://jestjs.io/docs/es-ES/getting-started) Herramienta de linting para analizar el codigo en busca de errores.

## 6. Checklist
* [x] Usa VanillaJS.
* [x] No hace uso de `this`.
* [ ] Pasa linter (`npm run pretest`)
* [x] Pasa tests (`npm test`)
* [x] Pruebas unitarias cubren un mínimo del 70% de statements, functions y
  lines y branches.
* [x] Incluye un _plan de acción_ de tus objetivos de aprendizaje prioritizado en `README.md` (o otro archivo).
* [x] Incluye _Definición del producto_ clara e informativa en `README.md`.
* [x] Incluye historias de usuario en `README.md`.
* [x] Incluye _sketch_ de la solución (prototipo de baja fidelidad) en
  `README.md`.
* [x] Incluye _Diseño de la Interfaz de Usuario_ (prototipo de alta fidelidad)
  en `README.md`.
* [x] Incluye link a Zeplin en `README.md`.
* [x] Incluye el listado de problemas que detectaste a través de tests de
  usabilidad en el `README.md`.
* [x] UI: Muestra lista y/o tabla con datos y/o indicadores.
* [x] UI: Permite ordenar data por uno o más campos (asc y desc).
* [x] UI: Permite filtrar data en base a una condición.
* [x] UI: Es _responsive_.