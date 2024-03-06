# Contenidos

### Preguntas frecuentes
1. Abro los _notebooks_, hago cambios para ver cómo funcionan, y a la semana siguiente al hacer `git pull` me sale un error que dice:
   > `Your local changes to the following files would be overwritten by merge`
   
   ¿Qué puedo hacer? 🤔
   
   Siempre puedes clonar el repositorio otra vez, pero no es la idea. Lo más correcto es: guardar los cambios en alguna otra parte, hacer `pull`, y luego volver a aplicar tus cambios. Para eso, utiliza los siguientes comandos:
   ```bash
   git stash     # Guarda los cambios hechos en otra parte. Desaparecen del working directory.
   git pull      # El pull que queríamos hacer en un principio.
   git stash pop # Regresa los cambios hechos por ti al working directory.
   ```


### Desglose contenidos

| Semana | Fechas      | Contenido                   | Detalle                 |
| ------ | ----------- | --------------------------- | ----------------------- |
| 0      | 04/3 - 10/3 | Introducción                |                         |
| 1      | 11/3 - 17/3 | Entorno de trabajo          |                         |
| 2      | 18/3 - 24/3 | *Built in*                  |                         |
| 3      | 25/3 - 31/3 | -                           | Feriado el jueves       |
| 4      | 01/4 - 07/4 | OOP Avanzado                |                         |
| 5      | 08/4 - 14/4 | Theading                    |                         |
| 6      | 15/4 - 21/4 | -                           | Sala de ayuda el jueves |
| 7      | 22/4 - 28/4 | Interfaz Gráfica 1          |                         |
| 8      | 29/4 - 05/5 | -                           | Receso                  |
| 9      | 06/5 - 12/5 | Programación Funcional      |                         |
| 10     | 13/5 - 19/5 | Interfaz Gráfica 2          |                         |
| 11     | 20/5 - 26/5 | Serialización y excepciones |                         |
| 12     | 27/5 - 02/6 | Networking                  |                         |
| 13     | 03/6 - 09/6 | Aplicaciones en Python      |                         |
