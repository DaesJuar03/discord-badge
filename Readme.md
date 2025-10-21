


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
1. Ingresamos al portal [.dev](https://discord.com/developers/applications)
   - En este sitio nos logueamos con nuestra cuenta de discord, el sitio es seguro.
   - Logueados en el apartado de Applications le daremos al boton de New Application, le ponemos un nombre a nuestro bot, aceptamos terminos y le damos a create.
   - Ya creado nos dirigimos a la opcion de Bot, buscamos el apartado de **PRECENSE INTENT**,**SERVER MEMBERS INTENT**,**MESSAGE CONTENT INTENT**. Esas 3 Opciones les activamos sus persmiso, damos a **Save Changes**.
2. Ingresar al sitio web [replt](https://replit.com/) 
   - En este sitio web tenemos que registarnos, ya sea con nuestra cuenta de github o con un correo electronico, es importante mencionar que esta cuenta de este sitio web la linkearemos a nuestro discord.
   - Una vez creada la cuenta, damos click en el apartado de app y damos click en el boton de **create**
   - En esta parte bautizamos a nuestro bot con el nombre que gusten, de ahi les puede salir un chat de la ia de la pagina, pueden explicarle ahi mismo que necesitan un bot para discord o si les sale la opcion de **Developer Frameworks** y buscar el template de **Node.js**, le ponen un nombre al proyecto y listo.
   - Despues de que el proyecto se haya creado les saldra un archivo JavaScript, el index.js. Copiamos y pegamos lo del repositorio, el mismo archivo que se llama index.js toman lo que contiene y lo pegan en la pagina.
   - En la vista de archivos en la pagina, buscamos 3 puntitos y le damos click, le damos a create file y llamamos el nuevo archivo como **".env"**. Creado tambien repetimos el paso anterior, buscamos en el repositorio el archivo .env y copiamos su contenido y lo pegamos en la pagina.
3. Buscar cada ID correspondiente.
   - Como ven. en el .env necesitamos tomar los id de nuestro discord, en estos lugares conseguiran cada uno.
4. Token Bot
   - [Token](https://discord.com/developers/applications/1429576649409691709/bot)
   - En la pagina buscan el titulo de **Token** y le dan boton de reset, les pedire la autenticacion de dos pasos, despues de realizarla les soltara el token. Copian y pegan en el archivo.
5. CLIENT_ID
   - [CLIENT_ID](https://discord.com/developers/applications/1429576649409691709/information)
   - En la pagina buscan el titulo de **APPLICATION ID** y le dan al boton de copy y lo pegan en el archivo .env.
6. GUILD_ID
   - En este apartado deberemos de tener activado en nuestra cuenta de discord el **Modo Desarrollador**.
   - Una vez activado le damos click derecho a nuestro servidor y le damos a la opcion de **copiar id del servidor** y lo pegan al archivo .env.
### Paso 2. Darle permisos.
1. Permisos.
   - En el apartado de [OAuth2](https://discord.com/developers/applications/1429576649409691709/oauth2). Buscamos y le damos permiso en **application.commands** y **bot** tambien mas abajo le damos a **send message**.
   - En la misma pagina hasta abajo hay un apartado llamado **Generated URL**. Le damos a copy, lo pegamos en nuestro navegador, es una invitacion, buscamos nuestro servidor y lo agregamos ahi.
2. Encender el bot.
   - Nos devolvemos a [replt](https://replit.com/) y damos click al boton de Run, pueden checar en su servidor si el bot esta Encendido.


