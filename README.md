# Cuestionario TAI
Aplicación hecha basada en la solución del usuario polme5 en el grupo de telegram preparatai https://sites.google.com/view/preparataiage/inicio?authuser=0

Página online https://artulance.github.io/astrocuestion/

## 🚀 Organización del proyecto

Se ha realizado la siguiente estructura

En src/data guardamos un ejemplo de json test como ejemplo si quieres subir tu propio cuestionario. 
En src/data/test/ guardamos todos los test en formato json, todos tienen o no una pista en caso de error para mostrarla en pantalla.
Si se desea que el cuestionario tenga las preguntas con orden aleatorio, se recomienda usar la propiedad "shuffle": true, de lo contrario se pone como valor false o no se pone. (Recomendable poner en false para examenes y pastillas). Para examenes en caso de que una pregunta sea anulada, dejar todas a false

### ¿Cómo puedo aportar un cuestionario?

Puedes aportar agregando ficheros json con una pull request. Será aceptada siempre y cuando respete el formato de json necesario.
Desde la versión 1.3.0 se ha agregado la posibilidad de que los cuestionarios se puedan agrupar por carapeta, la aplicación se encargará de mostrarlos.

```


## 🧞 Commandos

Aquí te dejo los comandos esenciales para correr este proyecto en tu máquina local

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |



