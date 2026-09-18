# Nueva York 2026 — Guía por Recorridos

Aplicación web de una sola página (`index.html`) para gestionar un viaje a Nueva York
del **18 al 26 de septiembre de 2026**, con 3 viajeros y base en Valley Stream, Long Island.

> **Nota para modelos de lenguaje:** este documento es autocontenido. Contiene el itinerario
> completo en texto plano, sin necesidad de leer el código. Toda la información de fechas,
> lugares, horarios y decisiones está aquí.

---

## 1. Contexto del viaje

| Dato | Valor |
|---|---|
| Fechas activas | 18 – 26 de septiembre de 2026 (9 días) |
| Viajeros | 3 personas |
| Base de alojamiento | Valley Stream, Long Island, NY |
| Transporte a Manhattan | LIRR (~35 min) a Penn Station o a Grand Central Madison |
| Aeropuerto | JFK (15 min en carro desde Valley Stream) |
| Idioma de la app | Español |
| Ya cumplido antes del 18 | Cataratas del Niágara · High Line · Chelsea Market · Empire State (fachada) · Flatiron · Little Island · Tanger Outlets |
| Pendiente de lo ya cumplido | The Vessel (Hudson Yards) — reprogramado al sábado 26 |

### Principio de diseño

El itinerario **no está organizado por días fijos**, sino por **recorridos reasignables**.
Cada recorrido es una unidad geográfica independiente con su propia sensibilidad al clima.
El calendario es una sugerencia editable: cualquier recorrido puede moverse a cualquier día,
salvo las anclas fijas.

### Prioridad declarada

Los **monumentos esenciales de Nueva York** tienen prioridad absoluta sobre las
localizaciones de cine y series. La capa de cine se conserva como información secundaria
que nunca consume tiempo del recorrido: solo se marca cuando cae de paso sobre la ruta.

---

## 2. Anclas fijas (no se mueven)

| Fecha | Compromiso | Motivo |
|---|---|---|
| **Viernes 18, 16:00-16:30** | **Entrada a SUMMIT One Vanderbilt** | Franja asignada por disponibilidad de tickets |
| Sábado 19, 14:30 | Free Tour de Bajo Manhattan | Reservado |
| **Domingo 20, 9:30** | **Ferry Statue City Cruises** | **Reservado, fecha no modificable** |
| **Domingo 20, 16:00** | **Misa en St. Patrick's Cathedral (en español)** | **Programada. Obliga a salir de Ellis Island a las 14:00** |
| Lunes 21, tarde | Encuentro familiar | Solo zona casa base |
| Jueves 24, ~19:05 | Yankees vs Tampa Bay Rays | Partido en casa |
| Viernes 25, noche | Cena de despedida | — |
| Sábado 26, noche | Vuelo de regreso | Salir de Valley Stream 20:00 |

---

## 3. Pronóstico del tiempo (NWS, Manhattan)

| Día | Cielo | Máx | Prob. lluvia | Veredicto |
|---|---|---|---|---|
| Vie 18 | Soleado | 28 °C | 0 % | Mejor día del viaje |
| Sáb 19 | Mayormente soleado | 22 °C | 0 % | Excelente |
| Dom 20 | Lluvias desde 8 am | 23 °C | 70 % | Peor día |
| Lun 21 | Nublado con chubascos | 22 °C | 40 % | Regular |
| Mar 22 | Nublado con chubascos | 21 °C | 40 % | Regular |
| Mié 23 | Parcialmente soleado | 21 °C | 30 % | Aceptable |
| Jue 24 – Sáb 26 | Fuera del alcance del pronóstico al momento de planificar | | | |

---

## 4. Itinerario asignado

### VIERNES 18 — Recorrido R1 · Midtown Icónico
*Exige sol · Día completo · 7 MUST*

```
09:00  LIRR Valley Stream -> Grand Central Madison
09:30  Grand Central Terminal (techo de constelaciones, Galería de los Susurros)
10:30  TIMES SQUARE DE DÍA (caminando al oeste por la calle 42)
11:15  NY Public Library (leones, Rose Reading Room) + Bryant Park
12:00  Almuerzo — Los Tacos No. 1 (229 W 43rd St)
12:45  Rockefeller Center (Atlas, Prometeo, Channel Gardens) + Radio City Music Hall
       La fachada de St. Patrick's queda enfrente; el interior se cubre el domingo
14:00  Quinta Avenida (Apple Cubo, NBA Store, Nintendo, LEGO, FAO Schwarz) — 1 h 45
15:45  Caminata a One Vanderbilt (10 min)
16:00  SUMMIT ONE VANDERBILT — ENTRADA 16:00-16:30, se sale ~19:15
       El horario del ticket es solo la entrada: no hay límite de permanencia.
       18:30 estar ya en las terrazas altas · 18:56 atardecer · 19:00-19:15 hora azul
19:15  Cena en Midtown
20:30  TIMES SQUARE DE NOCHE
22:00  LIRR de regreso
```

**Razón de la asignación:** es el único día con 0 % de lluvia y cielo despejado confirmado.
El SUMMIT es la actividad más dependiente del clima de todo el viaje: con nubes bajas no se
ve nada. Además el SUMMIT está dentro de Grand Central y Times Square queda a 8 cuadras a pie,
lo que permite resolver Times Square de día y de noche el mismo día.

**Sobre la entrada de las 16:00:** el horario del ticket es únicamente la franja de **entrada**.
Una vez adentro no hay límite de tiempo y el mirador cierra a medianoche (última entrada 22:30).
Entrar a las 16:00 en lugar de a las 17:30 es una ventaja, no una limitación: cubre la ciudad
de día, la hora dorada, el atardecer, la hora azul y Manhattan encendido en una sola visita.

**Advertencia operativa:** el recorrido del SUMMIT es de **un solo sentido**. Una vez que se
sube a un piso superior no se puede volver a los anteriores. Conviene tomarse con calma los
pisos bajos (las salas de espejos) entre las 16:00 y las 18:00, y estar ya en las terrazas
altas a partir de las 18:30 para ver el atardecer desde el punto más alto.

---

### SÁBADO 19 — Recorrido R5 · Brooklyn: Puente & DUMBO
*Exige sol · Día completo · Ancla: Free Tour 14:30*

```
08:30  LIRR + Metro A/C a High St, Brooklyn
09:30  Brooklyn Heights Promenade (panorámica de Lower Manhattan)
10:30  DUMBO — Washington St esquina Water St (la foto del Manhattan Bridge)
11:30  Jane's Carousel + Empire Stores (azotea 360 gratuita)
12:15  Almuerzo — Time Out Market (55 Water St)
13:30  Jacques Torres Chocolate (66 Water St)
14:15  Brooklyn Bridge Park (Pier 1, Pier 2, Pebble Beach)
15:30  CRUCE DEL PUENTE DE BROOKLYN A PIE (1,8 km de pasarela de madera)
17:00  City Hall Park
18:00  Times Square Express (opcional, metro 2/3 desde Fulton St)
```
**Variante si se combina con el Free Tour:** Brooklyn de 8:30 a 13:00, cruce del puente
13:00-14:00, y el tour arranca a las 14:30 justo donde termina el puente.

---

### DOMINGO 20 — Recorrido R4 · Estatua de la Libertad, Ellis Island & Misa en St. Patrick's
*A prueba de lluvia · DOS anclas fijas: Ferry 9:30 y Misa 16:00*

```
07:30  Ponchos puestos, calzado antideslizante, bolsa hermética para el celular
08:00  LIRR + Metro 1 a South Ferry
09:00  Castle Clinton — canje de tickets y control de seguridad (llegar 30 min antes)
09:30  FERRY — cubierta inferior techada, lado derecho al salir
10:00  Liberty Island — fotos + Museo de la Estatua (interior, antorcha original de 1886)
11:45  Ferry de enlace a Ellis Island
12:05  ELLIS ISLAND IMMIGRATION MUSEUM — 3 pisos techados, audioguía gratis, Great Hall
14:00  SALIDA OBLIGATORIA — ferry de regreso a Battery Park
       Estar en el muelle a las 13:50. Los ferries salen cada 25-40 min y un domingo
       lluvioso pueden espaciarse. Perder este ferry compromete la misa.
14:30  Llegada a Battery Park
14:35  Metro 4/5 expreso Bowling Green -> Grand Central-42 St (13 min)
15:00  Caminata por la 5ta Avenida hasta la calle 50 (12 min)
15:20  Llegada a St. Patrick's — tomar puesto en la nave central
16:00  MISA EN ST. PATRICK'S CATHEDRAL — en español
17:00  Interior de la catedral con calma: La Pietà, Capilla de la Virgen, vitrales
17:45  Rockefeller Center de noche (cruzando la calle) + Apple Cubo 24/7
19:15  Cena en Midtown
20:30  TIMES SQUARE BAJO LLUVIA (a 8 cuadras a pie)
22:00  LIRR de regreso
```

**Estrategia anti-lluvia:** el ferry cae en el día con 70 % de probabilidad de lluvia y no se
puede mover. La solución es invertir la proporción de tiempo: menos horas al aire libre en
Liberty Island y más horas dentro del museo de Ellis Island, que es enorme y en un día
soleado se recorre con prisa. Con lluvia el ferry va medio vacío, lo que es una ventaja real.
Por la tarde, la catedral, Rockefeller y las megatiendas de Times Square son todos refugio.

**Sobre la misa:** la misa dominical de las 16:00 en St. Patrick's es **la hispana de la
catedral**. Es el ancla que reorganiza toda la tarde del domingo: el día pasa de terminar en
el Bajo Manhattan a mudarse a Midtown. Eso resulta conveniente, porque la catedral,
Rockefeller Center y Times Square quedan en un radio de 8 cuadras.

**Consecuencia sobre el viernes 18:** como el interior de St. Patrick's queda cubierto el
domingo, el viernes se elimina esa parada dedicada y esa hora se devuelve a la Quinta
Avenida, que había quedado comprimida por la entrada al SUMMIT a las 16:00.

---

### LUNES 21 — Recorrido R9 · Green Acres & Familia
*A prueba de lluvia · Medio día · Ancla: encuentro familiar*

```
09:30  Green Acres Mall (Sunrise Hwy, Valley Stream — 5 min en carro)
       Macy's, Target, Primark, Sephora, Zara, Pandora, JCPenney
11:00  COMPRAR 3 PONCHOS para el ferry del domingo (Target, $5-10 c/u)
13:00  Regreso a la casa base
13:30  ENCUENTRO FAMILIAR — sin agenda
```

---

### MARTES 22 — Recorrido R6 · Village, SoHo & Chinatown
*Tolerante al clima · Día completo*

```
09:00  LIRR + Metro A/C/E a West 4th St
09:45  Washington Square Park y su Arco
10:45  Joe's Pizza (7 Carmine St) + The Cage (cancha de streetball)
11:30  Edificio de Friends (90 Bedford esquina Grove)
12:15  Hook & Ladder 8 (14 N Moore St, Tribeca) — Cazafantasmas
13:00  SoHo Cast-Iron District (Spring, Prince, Broadway, Lafayette)
14:30  KATZ'S DELICATESSEN (205 E Houston St) — pastrami desde 1888
15:45  Little Italy (Mulberry St) + Ferrara Bakery (195 Grand St)
17:00  Chinatown (Mott St, Doyers St, Columbus Park)
19:00  TIMES SQUARE HORA AZUL (metro N/Q/R desde Canal St)
```

---

### MIÉRCOLES 23 — Recorrido R2 · Central Park Completo
*Exige sol · Día completo*

```
09:30  LIRR + Metro a 59 St-Columbus Circle
10:00  Columbus Circle + fachada del Hotel Plaza
10:30  Gapstow Bridge y Wollman Rink
11:00  The Mall & Literary Walk (túnel de olmos)
11:45  BETHESDA TERRACE & FOUNTAIN (techo de azulejos Minton)
12:45  Bow Bridge
13:15  Almuerzo en el parque
14:00  Strawberry Fields + mosaico IMAGINE (frente al edificio Dakota)
14:45  Belvedere Castle (mirador gratuito sobre Turtle Pond)
15:30  Escalinatas del MET (solo la foto, no se entra al museo)
16:30  ROOSEVELT ISLAND TRAM (60 y 2da Ave) — $2.90 con OMNY
18:00  TIMES SQUARE HORA AZUL
```

---

### JUEVES 24 — Recorrido R7 · Harlem & Yankee Stadium
*Tolerante al clima · Día completo · Ancla: partido*

```
10:00  LIRR + Metro A/B/C/D a 125 St, Harlem
11:00  Apollo Theater (253 W 125th St) — marquesina y Walk of Fame
12:00  Malcolm Shabazz Harlem Market (52 W 116th St)
13:00  Almuerzo soul food — Sylvia's (328 Lenox Ave) o Amy Ruth's (113 W 116th)
14:15  Strivers' Row (calles 138 y 139)
15:00  Rucker Park (155th y Frederick Douglass Blvd)
17:30  Metro 4/B/D a 161 St-Yankee Stadium
       Monument Park CIERRA 45 MIN ANTES del primer lanzamiento
19:05  YANKEES vs TAMPA BAY RAYS
22:00  Times Square Express de regreso (el metro D para en 42 St)
```

---

### VIERNES 25 — Recorrido R8 · Hudson Yards & Despedida
*Tolerante al clima · Día completo · Ancla: cena de despedida*

```
10:00  LIRR a Penn Station + caminata al oeste
11:00  THE VESSEL (Hudson Yards) — 154 escaleras, 2.500 escalones
12:00  The Shops at Hudson Yards (7 pisos)
13:00  Starbucks Reserve Roastery (61 9th Ave) — 3 pisos con tostadoras a la vista
14:30  Meatpacking District + Google Store Chelsea
16:00  Smorgasburg Central Park (36 Central Park W, vie-dom 12:00-20:00)
18:30  CENA DE DESPEDIDA
21:00  Times Square de noche post-cena
```

---

### SÁBADO 26 — Recorrido R10 · Times Square sin Afán & Cierre
*Tolerante al clima · Día completo · Ancla: vuelo nocturno*

```
09:00  Cierre de maletas y pesaje
10:30  LIRR a Penn Station con el equipaje
11:30  CONSIGNA DE EQUIPAJE (Bounce o Vertoe, ~$7 por maleta)
12:00  Times Square parte 1 — escaleras rojas de TKTS, One Times Square
13:00  Times Square parte 2 — M&M's World, Hershey's, Krispy Kreme, Disney Store
14:30  Almuerzo sin afán
15:30  Times Square parte 3 — marquesinas de Broadway (calles 41 a 54)
16:30  Grand Central Market — souvenirs comestibles
17:30  Recoger equipaje + LIRR a Valley Stream
20:00  Uber a JFK (15 min)
```

---

## 5. Times Square como ancla recurrente

Times Square no es un paso dentro de un recorrido: es un **módulo con 5 dosis** que se activa
en cualquier día. Está a 10 minutos a pie de Penn Station y de Grand Central, las dos
terminales del LIRR, por lo que queda de camino a casa casi todos los días.

| Dosis | Duración | Cuándo |
|---|---|---|
| Express | 20-30 min | El día vino pesado |
| Hora Azul | 45 min | 19:00-19:45 — la mejor foto |
| Noche | 1-1.5 h | Después de cenar |
| Completo | 3-4 h | Sin afán, con tiempo de sobra |
| Bajo lluvia | 1-1.5 h | Cuando llueve (a propósito: el asfalto refleja las pantallas) |

**Asignación actual:** Vie 18 completo + noche · Sáb 19 express · Dom 20 bajo lluvia ·
Mar 22 hora azul · Mié 23 hora azul · Jue 24 express · Vie 25 noche · Sáb 26 completo.

**Times Square aparece en 8 de los 9 días.** El único día sin Times Square es el lunes 21,
dedicado a la familia en Long Island.

---

## 6. Comodines flotantes (sin día asignado)

| Comodín | Estado | Notas |
|---|---|---|
| Show de Broadway | **Descartado — confirmado que no hay invitación** | Fuera del plan. Si se decide comprar por cuenta propia: quiosco TKTS, Broadway con calle 47, hasta 50 % de descuento el mismo día. Lun-vie 15:00-20:00; mié, jue, sáb y dom 11:00-20:00. Noches libres: martes 22 y miércoles 23. Conviene un musical visual (El Rey León, Aladdin, Wicked, MJ) que no dependa del inglés |
| Comodín Nocturno de Midtown | Siempre disponible | Times Square 24/7 · Apple Fifth Avenue 24/7/365 · Grand Central hasta las 2:00 · Rockefeller Plaza · Bryant Park hasta las 22:00 |
| Intrepid Sea, Air & Space | Reserva | Portaaviones en Pier 86 con el transbordador Enterprise y un Concorde |
| Williamsburg & Smorgasburg | Reserva, solo sábados | Marsha P. Johnson State Park, 90 Kent Ave, 11:00-18:00 |
| Coney Island | Descartado del plan principal | 1 hora de metro por trayecto; Luna Park solo abre fines de semana en septiembre |

---

## 7. Acciones pendientes

**Urgentes:**
1. SUMMIT One Vanderbilt: entrada confirmada para el viernes 18 en la franja 16:00-16:30.
   Sin límite de permanencia una vez adentro. Estar en las terrazas altas a las 18:30.
2. Comprar 3 ponchos en Green Acres ($5-10 c/u; en el muelle cuestan $15-20).
3. Confirmar la hora del partido de los Yankees del jueves 24 y comprar grada (~$20-40).

4. Misa en St. Patrick's, domingo 20 a las 16:00 (en español). Obliga a tomar el ferry de
   las 14:00 desde Ellis Island: estar en el muelle a las 13:50.

**No urgentes:**
5. Reservar mesa para la cena de despedida del viernes 25.
6. Reservar consigna de equipaje cerca de Penn Station para el sábado 26.
7. Llevar descargada la confirmación del ferry del domingo 20.
8. Activar OMNY o tarjeta contactless en el celular.

---

## 8. Cobertura de monumentos esenciales

Todos los MUST de Nueva York quedan cubiertos:

**Cubiertos en este itinerario (18-26 sept):** Times Square · Central Park y Bethesda Terrace ·
Estatua de la Libertad · Ellis Island · Puente de Brooklyn · DUMBO · Rockefeller Center ·
Radio City · St. Patrick's · Grand Central · SUMMIT One Vanderbilt · 9/11 Memorial · Oculus ·
Wall Street · Charging Bull · Federal Hall · Trinity Church · Battery Park · Quinta Avenida ·
Bryant Park · NY Public Library · Washington Square Park · Bow Bridge · Strawberry Fields ·
Belvedere Castle · Escalinatas del MET · Roosevelt Island Tram · Brooklyn Heights Promenade ·
Little Italy · Chinatown · Katz's Delicatessen · Apollo Theater · Yankee Stadium · The Vessel.

**Cubiertos antes del 18 de septiembre:** Empire State (fachada) · High Line · Chelsea Market ·
Flatiron Building · Little Island · Cataratas del Niágara.

**Excluidos conscientemente:** Top of the Rock, Edge y One World Observatory (un solo mirador
basta, y el SUMMIT es el elegido) · AMNH y el MET por dentro (el grupo no es de museos;
solo se visitan las escalinatas del MET) · Staten Island Ferry (redundante con el ferry de la
Estatua) · Coney Island (costo de oportunidad demasiado alto).

---

## 9. Arquitectura técnica

### Archivos

```
index.html            Aplicación completa: HTML, datos y lógica en un solo archivo
assets/tailwind.css   CSS compilado desde src/input.css
src/input.css         Directivas de Tailwind
tailwind.config.js    Configuración (escanea index.html)
package.json          Script de build: npm run build:css
```

**Sin framework ni backend.** Es un archivo HTML autónomo que se abre directamente en el
navegador. El único paso de construcción es recompilar el CSS si se añaden clases nuevas.

```bash
npm install
npm run build:css     # recompila assets/tailwind.css tras editar index.html
```

### Estructuras de datos principales

| Constante | Contenido |
|---|---|
| `TRIP_DAYS` | Los 9 días del viaje con fecha ISO y etiqueta |
| `RECORRIDOS` | Catálogo de 10 recorridos. Cada uno: `id`, `nombre`, `zona`, `dur`, `clima`, `musts`, `ancla`, `pasos`, `comida`, `cine`, `checklist`, `lluviaPlan`, `mapsUrl` |
| `TS_DOSIS` | Las 5 dosis de Times Square |
| `COMODINES` | Recorridos flotantes sin día asignado |
| `AGENDA_DEFAULT` | Asignación sugerida: fecha -> `{ruta, ts, lock, nota}` |
| `MAP_POINTS` | Puntos del mapa Leaflet, clasificados por tipo |
| `PREP`, `TIPS`, `MOVIES`, `BINGO`, `FOOD_FULL` | Contenido de la pestaña EXTRAS |

### Campo `clima` de cada recorrido

| Valor | Significado | Umbral de aprobación |
|---|---|---|
| `sol` | Exige cielo despejado | Aprueba con ≤30 % de lluvia; advierte hasta 50 %; rechaza por encima |
| `mixto` | Tolerante | Aprueba con ≤60 % de lluvia |
| `lluvia` | A prueba de lluvia | Aprueba siempre |

### Motor de clima

- Consulta **Open-Meteo** (`api.open-meteo.com`, sin clave de API) con coordenadas de Manhattan.
- Traduce los códigos WMO a categorías legibles.
- `veredicto(rutaId, fecha)` cruza la sensibilidad del recorrido con el pronóstico del día.
- `sugerirCambio(fecha)` busca otro día libre cuyo recorrido encaje mejor hoy y propone el
  intercambio. Nunca propone mover una fecha marcada con `lock`.
- Selector manual de respaldo (`state.climaManual`) para cuando no hay conexión. El ajuste
  manual **solo afecta al día activo**, para no invalidar el pronóstico del resto de la semana.

### Persistencia

Todo el estado vive en `localStorage` bajo la clave `nyrec2026`:

```js
{
  done: {},        // pasos completados, clave "<rutaId>s<indice>"
  chk: {},         // checklists por recorrido
  bingo: {},       // bingo del viajero
  prep: {},        // preparativos
  agenda: {},      // reasignaciones de recorrido, clave = fecha ISO
  ts: {},          // dosis de Times Square por fecha
  ruta: null,      // último recorrido abierto
  climaManual: null
}
```

### Pestañas

| Pestaña | Función |
|---|---|
| HOY | Recorrido del día, clima en vivo, veredicto, sugerencia de intercambio, dosis de Times Square y los pasos con progreso |
| RUTAS | Asignación editable de los 9 días + catálogo filtrable de los 10 recorridos y los comodines |
| MAPA | Leaflet con todos los puntos, filtrables por tipo |
| EXTRAS | Preparativos, gastronomía, capa de cine y bingo del viajero |

---

## 10. Fuentes

- Pronóstico meteorológico: [National Weather Service — Manhattan, NY](https://forecast.weather.gov/MapClick.php?lat=40.758&lon=-73.9855)
- API de clima en vivo: [Open-Meteo](https://open-meteo.com/)
- Calendario de los Yankees: [Yahoo Sports](https://sports.yahoo.com/mlb/teams/ny-yankees/schedule/)
- Horarios y ubicaciones de TKTS: [TDF — TKTS Live](https://www.tdf.org/discount-ticket-programs/tkts-by-tdf/tkts-live/)
- Horario de misas de St. Patrick's: [Saint Patrick's Cathedral — Masses & Sacraments](https://saintpatrickscathedral.org/masses)
- Política de entrada y permanencia del SUMMIT: [SUMMIT One Vanderbilt — FAQ](https://info.summitov.com/faq/What-is-SUMMIT-One-Vanderbilts-Late-Entry-Policy/) y [guía de FAQs 2026](https://decks-nyc.com/summit-one-vanderbilt/summit-one-vanderbilt-faqs/)
- Sedes y horarios de Smorgasburg: [Smorgasburg New York](https://smorgasburg.com/new-york)
