# Hi there, I´m Leandro ! 👋
## About me 👀


English
Welcome to my GitHub!
I'm Full-Stack Web Developer passionate about Front-End development!
I love creating new things in a creative way, I am also interested in learning new languages, traveling and gaining new experiences.
Do you want to contact me or get to know me better? I leave my contact networks below.

Español
Bienvenido a mi GitHub!
Soy Full-Stack Web Developer con una gran pasión por el desarrollo Front-End!
Me encanta crear cosas nuevas de forma creativa, tambien me interesa aprender nuevos idiomas, viajar y ganar nuevas experiencias.
Queres contactarme o conocerme más? Te dejo mis redes de contacto más abajo.

## My Skills: 
<li> React</li>
<li> Redux </li>
 <li> JavaScript </li>
 <li> Node.js</li>
 <li> Express </li>
 <li> SQL </li>
 

## My Proyects

  - Paso a paso
- [ ] Posibilidad de seleccionar/agregar uno o más tipos de dietas
- [ ] Botón/Opción para crear una nueva receta

<img src='./client/src/img/formPage.png' />

#### Base de datos

El modelo de la base de datos fue creado con las siguientes entidades:

- [ ] Receta con las siguientes propiedades:
  - ID: *
  - Nombre *
  - Resumen del plato *
  - Puntuación
  - Nivel de "comida saludable"
  - Paso a paso
- [ ] Tipo de dieta con las siguientes propiedades:
  - ID
  - Nombre

#### Backend

Fue desarollado con un servidor en Node/Express con las siguientes rutas:

- [ ] __GET /recipes?name="..."__:
  - Obtiene un listado de las primeras 9 recetas que contengan la palabra ingresada como query paraeter
  - Si no existe ninguna receta nos muestra un mensaje adecuado
- [ ] __GET /recipes/{idReceta}__:
  - Obtiene el detalle de una receta en particular
  - Trae solo los datos pedidos en la ruta de detalle de receta
  - Incluye los tipos de dieta asociados
- [ ] __GET /types__:
  - Obtiene todos los tipos de dieta posibles
  - En una primera instancia, cuando no exista ninguno, precarga en la base de datos con los tipos de datos indicados por spoonacular [acá](https://spoonacular.com/food-api/docs#Diets)
- [ ] __POST /recipe__:
  - Recibe los datos recolectados desde el formulario controlado de la ruta de creación de recetas por body
  - Crea una receta en la base de datos
