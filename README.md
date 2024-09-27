# TP ICS -- *Alegre, Bracalenti, Gaggiotti Bussi, Kerps*
## Datos que consideramos que deberían estar incluídos en un archivo README.md
1. informacion acerca del proyecto y utilidad del mismo
2. informacion acerca de como iniciarlo o utilizarlo
3. donde encontrar ayuda (manuales, paginas, etc)
4. autores, responsables de mantenimiento y contribuyentes
5. tecnologias utilizadas
   
*Otra información que podría ser útil*
1. FAQ o preguntas frecuentes
2. Registro de cambios
3. Tipo de licencia

## Respuestas al enunciado del TP
### Consignas:

2-b- Para no subir cambios de configuraciones locales se debe agregar en el gestor de versiones un archivo denominado .gitignore, y dentro de éste se debe indicar los diferentes archivos, carpetas que no se deseen controlar. Además, es importante destacar que sólo se ignoraran aquellos archivos que nunca fueron agregados previamente al gestor de configuraciones, si los mismos ya fueron incorporados el .gitignore no tendrá efecto.

2-e- Para llevar al entorno productivo a Release 1, se debe primeramente realizar un Pull Request (PR) hacia Main, una vez aceptado el mismo, se realiza el tag de la nueva versión, seguido de la eliminación de la rama Release 1 y, por último y con otro pull request, se debe hacer un backport hacia la rama Develop para mantener las mismas consistentes y actualizadas.

2-f- Para corregir un error en la versión productiva, se crea una rama llamada Hotfix, se realizan los cambios necesarios, luego se hace un PR hacia Main para incorporar los cambios. Luego del mismo, se realiza un tag para cambiar el número de versión, se elimina la rama Hotfix y por último se realiza otro PR en sentido de backport hacia Develop.

2-j- Luego de crear la rama Feature y agregar las nuevas funcionalidades, se realiza un PR hacia Develop y se elimina la rama Feature, luego se crea una nueva rama Release en base a develop, se realizan las pruebas que se consideren pertinentes y se realiza un PR hacia la rama Main, una vez aceptado el mismo se elimina la rama Release y cómo último paso se crea un nuevo Tag para cambiar el número de versión.

3-a- Respondida anteriormente

3-b- Datos que se le pedirían a la persona que crea el PR:
Título claro y conciso del PR
Descripción detallada del PR
Instrucciones para pruebas
Capturas de pantalla
Referencias a issues
Además, GitHub ofrece herramientas como plantillas de PR, etiquetas para categorizar, opciones de comentarios en el código y un historial de cambios que facilitan la revisión y comprensión de las modificaciones.
