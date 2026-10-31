# AURORA: Awakening

**Aventura 2D de ciencia ficción, exploración, acción y misterio**, desarrollada en **GDevelop** para el Trabajo Práctico Integrador de *Resoluciones Lógicas*.

## Descripción

AURORA es un robot experimental desarrollado por la empresa tecnológica **NorthBio**, en un futuro cercano. Durante una serie de pruebas en sus instalaciones, comienza a experimentar anomalías: imágenes de una casa, una voz y recuerdos que no consigue explicar.

Convencida de que su propósito va más allá de las órdenes de la corporación, AURORA escapa del complejo. NorthBio envía robots para recuperarla, mientras ella atraviesa bosques e instalaciones abandonadas, resuelve mecanismos y recupera fragmentos de memoria.

Con cada recuerdo se acerca a una verdad inesperada. Este juego continúa el universo narrativo de *AURORA: The Truth*.

## Objetivo del juego

Escapar de NorthBio, sobrevivir a las unidades de captura, superar los obstáculos de cada escenario y recuperar los recuerdos necesarios para reconstruir la identidad de AURORA.

## Jugabilidad y controles

El juego utiliza una **vista 2D desde arriba (*top-down*)**, con desplazamiento libre en cuatro direcciones; **no es un plataformas lateral**.

| Acción | Control |
| --- | --- |
| Moverse hacia Arriba | `W` o `↑` |
| Moverse hacia Abajo | `S` o `↓` |
| Moverse hacia la Izquierda | `A` o `←` |
| Moverse hacia la Derecha | `D` o `→` |
| Disparo de Iones (Ligero) | `Click Izquierdo` |
| Cañón de Plasma (Pesado) | `Click Derecho` |

**Otras acciones:** desarrolladas a lo largo del juego.

### Mecánicas

- **Movimiento y dash:** desplazamiento en cuatro direcciones e impulso lateral rápido para esquivar amenazas.
- **Combate:** disparos de energía contra robots de NorthBio.
- **Interacción y hackeo:** uso de terminales, interruptores y códigos para modificar sistemas.
- **Puzzles:** apertura de puertas mediante cajas, botones, baterías y generadores; desactivación de peligros.
- **Exploración:** recuperación de fragmentos de memoria y consulta de registros.
- **Vida y checkpoints:** daño, derrota y puntos de reaparición.

## Niveles

| Nivel | Escenario | Objetivo principal |
| --- | --- | --- |
| **1. Prólogo — NorthBio: La fuga** | Laboratorio y fábrica tecnológica | Aprender las mecánicas, superar la seguridad y escapar del complejo. |
| **2. Bosque** | Naturaleza e instalaciones abandonadas | Explorar, resolver mecanismos y encontrar nuevos recuerdos. |
| **3. Ruinas de NorthBio** | Instalación deteriorada | Acceder a los archivos, enfrentar al robot jefe y descubrir la verdad. |

La aventura concluye con una **secuencia narrativa de revelación**.

## Personajes y enemigos

**AURORA:** protagonista robótica que intenta comprender el origen de sus recuerdos.

| Enemigo | Comportamiento |
| --- | --- |
| **Robot buscador** | Rápido, patrulla o persigue a AURORA y realiza disparos básicos. |
| **Robot artillero** | Más lento, resistente y con disparos de mayor potencia. |
| **Robot jefe** | Tiene más vida, utiliza ataques potentes y cuenta con secuaces. |

## Elementos interactivos

Las escenas pueden incluir **puertas normales y de seguridad, terminales de hackeo, paneles de códigos, botones, cajas móviles, baterías, generadores, láseres, checkpoints y fragmentos de memoria**. Estos elementos se combinan para crear desafíos en NorthBio.

## Tecnología

- **Motor:** [GDevelop](https://gdevelop.io/).
- **Formato:** videojuego 2D top-down (vista cenital).
- **Lógica:** eventos, condiciones, variables y funciones reutilizables de GDevelop.
- **Organización y control de versiones:** GitHub y GitHub Projects.

## Cómo ejecutar el juego

### Desde GDevelop (proyecto editable)

1. Instalar o abrir [GDevelop](https://gdevelop.io/).
2. Obtener los archivos del proyecto desde este repositorio.
3. Abrir en GDevelop el archivo principal del proyecto (`.json`).
4. Ejecutar la **vista previa** desde el editor.

### Desde el Navegador (proyecto jugable)

1. Abrir [GD Games](https://gd.games/).
2. Buscar AURORA: Awakening o en [este enlace](https://gd.games/games/8117ce1b-7fdf-4440-a7e0-8deff9d63db3).
3. Comenzar a **jugar.**

## Requisitos del Integrador

El proyecto está planificado para implementar y poder demostrar:

- [ ✔ ] Al menos tres niveles o escenas jugables.
- [ ✔ ] Sistema de vidas o puntaje mediante variables.
- [ ✔ ] Enemigos con comportamiento propio mediante eventos y condiciones.
- [ ✔ ] Una función o bloque personalizado reutilizable.
- [ ✔ ] Condiciones de victoria y derrota.
- [ ✔ ] Pantalla de inicio o instrucciones, y sonido o música.
- [ ✔ ] Juego completo y comprobado de principio a fin.

## Equipo

| Integrante | Rol |
| --- | --- |
| Valentino Carribale | _Líder - Responsable de Lógica y Documentación_ |
| Agustín Bianchi | _Responsable de Lógica_ |
| Iván Radoeff | _Responsable de Animación, Arte y Sonido_ |
| Ramiro Herrera | _Responsable de Lógica_ |

## Planificación y Seguimiento

- [Documento de Planificación (GDD)](https://colegiodelcarmenedu-my.sharepoint.com/:w:/g/personal/valentino_carribale_delcarmen_edu_ar/IQApg-5NxZwRSb8dV0f_7s1xAb-EatEkyz7HT3xIbMPW5a4?e=HiGvvn)
- [Tablero de Tareas (GitHub Projects)](https://github.com/users/Valentino-Carribale/projects/1)
- Los avances se registraron mediante commits y tareas en el backlog.

## Uso de Inteligencia Artificial

Se utilizó **ChatGPT** como apoyo para desarrollar ideas narrativas, definir mecánicas y planificar los niveles, además de generar propuestas visuales para los escenarios. El uso exacto de herramientas, recursos y cualquier asistencia adicional se registró en el documento de planificación, de acuerdo con las pautas del trabajo integrador.

## Créditos y Recursos de Terceros

Los recursos externos utilizados (sprites, imágenes, sonidos, música) se extrajeron de:

| Recurso | Autor / herramienta | Fuente |
| --- | --- | --- |
| _Música/Efectos de Sonido_ | Pixabay | https://pixabay.com/ |
| _Diseño de Sprites_ | Piskel | https://www.piskelapp.com/ |
| _Diseño de Sprites por IA_ | ChatGPT | https://chatgpt.com/ |

---

*AURORA: Awakening — Proyecto Integrador de Resoluciones Lógicas — 4to Informático — Colegio PS-029 "Del Carmen"*