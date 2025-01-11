![image](https://github.com/user-attachments/assets/50fd5865-006d-40ad-a81a-9d907192acee)
![image](https://github.com/user-attachments/assets/ac298bbe-e3c5-4f64-8489-fe8c5d625ba2)


# 📊 INFORME DE DATOS DE TWITCH: Semana del 7 al 13 de Noviembre de 2022

## Descripción del Proyecto
Este panel interactivo proporciona una visión detallada del comportamiento de los espectadores y streamers en Twitch durante la semana del 7 de noviembre de 2022 al 13 de noviembre de 2022. Los datos fueron capturados en intervalos de 30 minutos en la zona horaria UTC+0 (Londres). Un evento destacado de esta semana fue el lanzamiento del juego "God of War Ragnarök", el 9 de noviembre a las 5am UTC-0.

## Datos Utilizados en el Dashboard

### Archivos del Dataset
1. **StreamsInfo**: Incluye información de cada juego que se estuvo jugando cada 30 minutos, junto con el número de canales transmitiendo el juego y el número de espectadores viendo esos canales. La hora viene en zona horaria UTC-0.
2. **GamesInfo**: Contiene información sobre cada juego incluido en StreamsInfo, como ID del juego, nombre, rating, género, modo de juego, consola, perspectiva del jugador y fecha de lanzamiento.

Estos datos fueron utilizados como parte de la primera edición de los datdata games, un torneo de Power BI que forma a mejores analistas y profesionales de datos. Para más información, visita [datdata games](https://datdata.com/torneo).

## Terminología Utilizada en el Dashboard
- **Stream**: Un canal que transmite contenido en Twitch.
- **Espectador**: Persona que visualiza un stream en específico.
- **Medias de Espectadores y Streams**: Promedio concurrente de las capturas de datos, reflejando cuántos espectadores o streams habría en un momento específico basándose en los filtros aplicados.
- **EPS (Espectadores por Stream)**: Estimado de cuantos espectadores se podrían esperar por cualquier categoría o videojuego transmitido, calculado como Media Espectadores / Media Streams.

## Ideas para Explorar Más
- Número de juegos, espectadores o streamers por hora.
- Promedio de streams por día, hora, género, consola.
- Promedio de espectadores por día, hora, género, consola.
- Promedio de espectadores por stream.
- Máximo de espectadores al mismo tiempo durante la semana.
- Revisar cuántos juegos se están jugando en cada horario.
- ¿A qué hora es el máximo de espectadores por día y para qué juego?
- Streamers o juegos por género, consola, rating, modo de juego.
- Porcentaje de personas viendo cada juego del total de personas en Twitch en ese momento.

**Nota**: No se pueden sumar los datos de diferentes días u horas. Solo se pueden usar promedios o máximos debido a la posible duplicidad de espectadores.



