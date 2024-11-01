# Mapa del sitio

(Primer intento)

## Objetivo

Desplegar toda la información relevante para utilizar el servicio de transporte público en modalidad autobús (por ahora) en Costa Rica, para un público amplio con cualquier nivel de conocimiento previo del sistema.

- Fuente de datos: GTFS Schedule (primera versión) y GTFS Realtime (segunda versión).

## Referencias (_benchmarking_)

Según un sondeo en sitios web de sistemas de transporte público de grandes ciudades alrededor del mundo, estos son los principales componentes comunes en casi todas las referencias.

### Componentes

- Rutas
- Buscador de rutas y paradas simple (por nombre y ubicación)
- Rutas y paradas cerca de mí / "Nearby" (TfL) despliega mapa 
- Diferentes tipos de servicio (bus, tren, metro, ferry, etc.)
- Planificador de viajes (_trip planner_) / búsqueda de conexiones y tarifas (Tokio)
- Horarios (_schedules_)
- Alertas
- Formas alternativas de desplazamiento ("ways to get around") (TfL)
- Encontrar ubicaciones: estaciones y parqueo
- Tarifas (`agency_fare_url`)
- Búsquedas de rutas/paradas/viajes visitadas recientemente (_cookies_)
- Favoritos personalizados (una "estrella" para guardar una ruta)
- Contacto (_feedback_)
- Mapa(s) / mapa del sistema / mapas y horarios (LA Metro)
- Guía para personas usuarias (MBTA) / consejos de uso (Tokio) / manual del usuario (CDMX)
- FAQ (Paris RATP)
- Información sobre accesibilidad / seguridad
- Noticias, comunicados de prensa, eventos
- Sobre (acerca de)
- Información del tiempo atmosférico (Tokio)
- Turismo en el TP (Tokio)
- Conexión del TP con los aeropuertos
- Ubicación en tiempo real (MBTA, LA Metro, TfL
- Información en PDF completa sobre una ruta (LA Metro)
- Actualizaciones de estado (TfL) con visualización bonita
- Blog (TfL)
- Reporte del tráfico (TfL) congestionamiento, incidentes, etc.
- Menú principal: Itinerary Timetables Maps Tickets and fares Visiting Paris (Paris RATP)
- Indicador de incidencias por ruta "Traffic overview" (Paris RATP) bonito visualmente
- Getting around: Your itinerary, Hours of operation, Maps, Traffic information, Travel passes and prices, Lines and stations, Help and contact information, Passenger services, Visiting Paris (RATP)
- Información general útil: Póliza de Seguro, ¿Qué hacer en caso de..., Reglamento de la Ley de Movilidad, Uso correcto de las escaleras..., Módulos de orientación e información, Días inhábiles, Unidad de Transparencia, Lugares de interés de la CDMX cercanos al..., Operativo por temporada de lluvias

### Características deseables

- i18n (español e inglés, y más)

infobus.cr

## Páginas

### Rutas `/rutas`

Información general de las rutas

### Cada ruta `/rutas/<route_id>`

### Paradas `/paradas`

### Cada parada `/paradas/<stop_code>`

Incorporar en el sitio: Cosevi, ICT
