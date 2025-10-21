


<p>
  <h1 align="center"><b>Como Obtener Tu Insignia De Desarrollador De Discord</b></h1>
</p>


<p align="center">
    <img align="center" alt="Discordev" height="160px" src="https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/66e3d80db9971f10a9757c99_Symbol.svg" />
</p>

<p align="center">
Este tutorial esta hecho para instruir y educar a los nuevos y experimentados desarrolladores. <br>
Discord lleva tiempo dando esta insignia a aquellos que logren crear su primer bot para tu discord/servidor
</p>

<p >
<h2  align="center"> Pasos </h2>
</p>


<img align="right" height="270px" alt="GIF" src="https://upload.wikimedia.org/wikipedia/commons/b/b5/Discord_Active_Developer_Badge.svg" />
 
### Paso 1. Crear el bot
1. Ingresar al portal [.dev](https://discord.com/developers/applications)
   - En este sitio iniciamos sesión con nuestra cuenta de Discord (el sitio es seguro).
   - Una vez dentro, en el apartado **Applications**, hacemos clic en **New Application**, asignamos un nombre al bot, aceptamos los términos y presionamos **Create**.
   - Ya creado, vamos a la opción **Bot**, y en el apartado de **PRESENCE INTENT**, **SERVER MEMBERS INTENT** y **MESSAGE CONTENT INTENT**, activamos los tres permisos.
   - Finalmente, damos clic en **Save Changes** para guardar.

2. Ingresar al sitio web [Replit](https://replit.com/)
   - En este sitio debemos registrarnos (con GitHub o correo electrónico). Esta cuenta se vinculará a nuestro bot de Discord.
   - Una vez creada la cuenta, hacemos clic en **Create** dentro del apartado de aplicaciones.
   - Asignamos un nombre al proyecto. Si aparece el chat de IA, podemos indicarle que deseamos crear un bot de Discord.
   - Si se muestra la opción **Developer Frameworks**, seleccionamos la plantilla **Node.js** y asignamos un nombre al proyecto.
   - Cuando el proyecto esté creado, se mostrará el archivo `index.js`. Copiamos y pegamos en él el contenido del archivo `index.js` del repositorio.
   - Luego, en la vista de archivos, damos clic en los tres puntos y seleccionamos **Create File**, nombrándolo **.env**.
   - Abrimos este archivo y copiamos en él el contenido del `.env` del repositorio.

3. Buscar cada ID correspondiente.
   - Como se observa en el archivo `.env`, necesitaremos obtener algunos identificadores de Discord.

4. Token del Bot
   - [Token](https://discord.com/developers/applications/1429576649409691709/bot)
   - En la página buscamos el apartado **Token**, damos clic en **Reset Token**, completamos la autenticación de dos pasos y copiamos el nuevo token.
   - Pegamos este token en el archivo `.env`.

5. CLIENT_ID
   - [CLIENT_ID](https://discord.com/developers/applications/1429576649409691709/information)
   - En la página buscamos el apartado **APPLICATION ID**, damos clic en **Copy** y lo pegamos en el archivo `.env`.

6. GUILD_ID
   - Para obtener este ID, debemos tener activado el **Modo Desarrollador** en Discord.
   - Una vez activado, hacemos clic derecho en nuestro servidor y seleccionamos **Copiar ID del servidor**.
   - Pegamos el valor en el archivo `.env`.

---

### Paso 2. Darle permisos
1. Permisos.
   - En el apartado [OAuth2](https://discord.com/developers/applications/1429576649409691709/oauth2), activamos los permisos **application.commands** y **bot**.
   - Más abajo, en los permisos del bot, marcamos **Send Messages**.
   - En la parte inferior de la página, encontraremos un apartado llamado **Generated URL**. Damos clic en **Copy**, pegamos la URL en el navegador y seleccionamos nuestro servidor para agregar el bot.

2. Encender el bot.
   - Regresamos a [Replit](https://replit.com/) y hacemos clic en el botón **Run**.
   - Verificamos en nuestro servidor de Discord que el bot esté en línea.

---

### Paso 3. Conseguir insignia
1. Ir a la página de desarrolladores de Discord.
   - Accedemos a [DiscordDev](https://discord.com/developers/active-developer)
   - Seguimos las instrucciones en el sitio para reclamar la insignia de **Desarrollador Activo**.

La insignia toma tiempo en que te llegue, de 24 a 48 horas, asi que deben de visitar seguido la pagina, despues de cierto tiempo les aparecera y es todo.

