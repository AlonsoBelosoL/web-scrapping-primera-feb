Carpeta codigo:
01_capturar_equipos.py -> URL base para cada tupla [temporada, equipo]
02_capturar_plantillas.py -> Del índice de equipos generado en el paso anterior extrae la lista de jugadores de cada plantilla. URL para tripleta [temporada, equipo, jugador]
03_capturar_jugadores.py -> Utiliza el listado de plantillas para descargar las estadísticas individuales de cada partido. Estadísticas de cada jornada, de cada jugador, de cada plantilla, de cada temporada.

Carpeta datos. Organización:
datos/bruto/equipos/maestro_equipos.csv: URL base para cada tupla [temporada, equipo]
datos/bruto/plantillas/maestro_plantillas.csv: URL para tripleta [temporada, equipo, jugador]
datos/bruto/temporadas/: Directorio raíz que contiene las estadísticas detalladas.
Temporada (Ej: 2015-2016)
Equipo (Ej: Palencia_Baloncesto)
Archivos CSV: Cada archivo corresponde a un jugador de esa plantilla y contiene sus estadísticas desglosadas partido a partido.
