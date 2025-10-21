


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
 
# 🤖 Guía para Crear un Bot de Discord y Obtener la Insignia de Desarrollador Activo

---

## 🚀 **Paso 1. Crear el bot**

### 1️⃣ Ingresar al portal de desarrolladores
1. Dirígete a [Discord Developers](https://discord.com/developers/applications).  
2. Inicia sesión con tu cuenta de Discord (el sitio es seguro).  
3. En el apartado **Applications**, haz clic en **New Application**.  
4. Asigna un nombre a tu bot, acepta los términos y selecciona **Create**.  
5. En la barra lateral, entra en la sección **Bot** y activa los siguientes permisos:  
   - ✅ **PRESENCE INTENT**  
   - ✅ **SERVER MEMBERS INTENT**  
   - ✅ **MESSAGE CONTENT INTENT**  
6. Guarda los cambios con **Save Changes**.

---

### 2️⃣ Crear el entorno en Replit
1. Ingresa a [Replit](https://replit.com/) y regístrate (puedes usar tu cuenta de GitHub o correo electrónico).  
2. Esta cuenta será la que vincules con tu bot de Discord.  
3. Haz clic en **Create** para crear un nuevo proyecto.  
4. Escribe el nombre que desees para tu bot.  
5. Si se muestra un chat con la IA de Replit, puedes decirle que necesitas crear un bot para Discord.  
6. Si aparece el apartado **Developer Frameworks**, selecciona la plantilla **Node.js**.  
7. Cuando el proyecto esté creado, abre el archivo `index.js`.  
8. Copia el contenido del archivo `index.js` del repositorio correspondiente y pégalo ahí.  
9. En la vista de archivos, haz clic en los tres puntos (`⋮`), selecciona **Create File** y nómbralo **.env**.  
10. Copia y pega en este archivo el contenido del `.env` del repositorio.

---

### 3️⃣ Obtener los ID necesarios

#### 🔹 Token del bot  
- Ve a [Bot Settings](https://discord.com/developers/applications/1429576649409691709/bot).  
- En el apartado **Token**, haz clic en **Reset Token**.  
- Completa la autenticación en dos pasos.  
- Copia el token generado y pégalo en tu archivo `.env`.

#### 🔹 CLIENT_ID  
- Ve a [Application Information](https://discord.com/developers/applications/1429576649409691709/information).  
- Copia el valor de **APPLICATION ID** y pégalo en tu archivo `.env`.

#### 🔹 GUILD_ID  
- Activa el **Modo Desarrollador** en tu cuenta de Discord:  
  `Configuración → Avanzado → Modo Desarrollador`.  
- En tu servidor, haz clic derecho sobre el nombre del servidor y selecciona **Copiar ID del servidor**.  
- Pega este valor en tu archivo `.env`.

---

## ⚙️ **Paso 2. Darle permisos al bot**

### 1️⃣ Configurar permisos
1. Dirígete a [OAuth2](https://discord.com/developers/applications/1429576649409691709/oauth2).  
2. Marca las casillas:  
   - ✅ **application.commands**  
   - ✅ **bot**
   - ✅ **Send Messages**  
4. Desplázate hasta la parte inferior, copia la **Generated URL**.  
5. Pega la URL en tu navegador: se abrirá una invitación para agregar el bot a tu servidor.

---

### 2️⃣ Encender el bot
1. Regresa a [Replit](https://replit.com/).  
2. Haz clic en el botón **Run** para iniciar el bot.  
3. Verifica en tu servidor de Discord que el bot esté **en línea** ✅.

---

## 🏅 **Paso 3. Obtener la insignia de Desarrollador Activo**
1. Dirígete a [Discord Active Developer](https://discord.com/developers/active-developer).  
2. Sigue las instrucciones del portal para reclamar tu insignia 🪶.  

---

### 💡 Consejos finales
- Mantén tu **token** en secreto (nunca lo compartas públicamente).  
- Si tu bot no se conecta, revisa que tu archivo `.env` esté correctamente configurado.  
- Puedes agregar más comandos o eventos al bot modificando el archivo `index.js`.

---

✨ **¡Listo! Tu bot de Discord está en funcionamiento y estás a un paso de obtener tu insignia de desarrollador activo.**
