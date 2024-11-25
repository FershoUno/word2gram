# word2gram

Esta herramienta permite obtener nuevas entradas de un sitio web con WordPress y enviar la información usando un bot de Telegram a un grupo especifico

## Dependencias

* curl
* xmlstarlet
* Linux

  
## Implementacion

* Cree un bot de Telegram en `@BotFather`, personalice el bot, agreguelo en el grupo deseado y obtenga: el API KEY, ID del chat donde fue agregado
* Renombre el archivo `.env.example` a `.env`
* Rellene los datos solicitados del archivo .env
* Utilice crontab para configurar el tiempo de ejecución de la herramienta, ejemplo de crontab:  
>     */10 * * * * /PATH/word2gram/word2gram 
* Configure los ajustes del feed en la siguiente sección: **Ajustes del feed** y limitar a una sola entrada para que la herramienta pueda lecturar la entrada
* Listo!

