# API for Foods App **by Mr. Blue**

Api sobre recetas de comidas, en la que se puede :

| metodo/ruta | necesitas | Propósito                     |
| ----------- | --------- | ----------------------------- |
| GET/recipes    | n/a       | Consultar todas las recetas (DB / <a href="https://spoonacular.com/food-api" target="_blank" rel="noreferrer">API</a>)|
|GET/recipes?name=[NAME]|nombre de receta a buscar|Conseguir info de las recetas que coincidan con la busqueda|
|GET/recipes/[:id]|idRecipe|Encuentra una receta por su id|
|POST/recipes|info por body|Crear una nueva receta|
|GET/diets|n/a|Optener todas las dietas existentes|


## Arrancar el proyecto de manera local

0. Crear una nueva base de datos, en la consola de PostgreSQL ejecuta el comando `create database food` 

1. Instalar las dependencias, ejecuta el comando `npm install` 

2. Clonar el archivo `.env.template` y renombrarlo a `.env` 

3. Ejecutar el comando npm start 

4. Para visualizar el frontEnd descargar el repo <a href="https://github.com/MrBluegru/FoodApp-FrontEnd" target="_blank" rel="noreferrer">FoodApp-FrontEnd</a> 

## Tecnologias usadas

- JavaScript
- NodeJS
- Express
- PostgreSQL
- Sequelize
