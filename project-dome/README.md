# MoodVision AI / PlayFace

MoodVision AI, también conocido en el código como **PlayFace**, es una aplicación web educativa que utiliza inteligencia artificial para detectar emociones faciales en tiempo real desde la cámara del navegador.

La idea principal del proyecto es demostrar que una aplicación no solo puede recibir clics o texto del usuario, sino también interpretar señales visuales, como una sonrisa, una expresión neutral o un gesto facial, y reaccionar de forma interactiva.

Este README fue actualizado revisando lo que existe actualmente en:

- `uefn-frontend`: la aplicación visual hecha con React.
- `uefn-backend`: la API que guarda historial, estadísticas y capturas.
- `project-dome`: documentación general, requerimientos e idea del proyecto.

## Cómo Leer Este Documento

Para que sea fácil revisar el avance del proyecto, se usan estos símbolos:

| Símbolo | Significado |
|---|---|
| ✅ | Ya está implementado en el proyecto actual. |
| ⚠️ | Está parcialmente implementado o funciona de una forma distinta a la idea inicial. |
| ❌ | No está implementado, no está conectado o falta configurarlo. |

La intención no es ocultar lo que falta, sino dejarlo visible para poder revisarlo y mejorarlo.

## 1. Objetivo Del Proyecto

El objetivo de MoodVision AI es crear una plataforma interactiva capaz de reconocer emociones humanas usando la cámara web y modelos de inteligencia artificial.

En palabras simples:

> El usuario se coloca frente a la cámara, la aplicación analiza su rostro, identifica una emoción probable y muestra esa información en un dashboard visual.

El proyecto también guarda registros en el backend para poder consultar historial, estadísticas y capturas procesadas.

## 2. Problema Que Resuelve

Muchas aplicaciones actuales saben qué hace el usuario, pero no tienen ninguna idea de cómo se siente. Por ejemplo, una plataforma puede saber que una persona hizo clic en un botón, pero no puede saber si estaba feliz, aburrida, sorprendida o frustrada.

MoodVision AI intenta resolver esa limitación usando visión por computadora. La aplicación analiza expresiones faciales en tiempo real y convierte esa información en datos visuales fáciles de entender.

Esto puede aplicarse en áreas como:

- Educación online.
- Bienestar emocional.
- Experiencias interactivas.
- Juegos controlados con gestos.
- Análisis de comportamiento.
- Demostraciones académicas de inteligencia artificial.

## 3. Para Quién Es

El proyecto está pensado principalmente para estudiantes, docentes y personas que desean aprender cómo se puede integrar inteligencia artificial dentro de una aplicación web real.

También sirve como proyecto de exposición porque combina varias áreas importantes:

- Frontend moderno.
- Backend con API.
- Base de datos.
- Cámara web.
- Inteligencia artificial.
- Diseño visual.
- Estadísticas.
- Juego interactivo.
- Integración con servicios externos.

## 4. Qué Hace La Aplicación

Cuando el usuario abre la aplicación, puede activar la cámara. Después de eso, el sistema analiza el rostro y muestra información en tiempo real.

La aplicación puede:

- Detectar un rostro frente a la cámara.
- Reconocer emociones faciales.
- Mostrar la emoción dominante.
- Mostrar el porcentaje de confianza.
- Mostrar edad y género aproximados.
- Dibujar puntos faciales sobre el rostro.
- Guardar historial emocional.
- Mostrar estadísticas del día.
- Mostrar datos históricos.
- Capturar imágenes.
- Mostrar imágenes procesadas como "momentos divertidos".
- Permitir seleccionar un avatar.
- Ofrecer un juego controlado por gestos faciales.

## 5. Estado General Del Proyecto

| Estado | Área | Explicación sencilla |
|---|---|---|
| ✅ | Dashboard principal | Existe una pantalla principal donde se ve la cámara, la emoción actual y estadísticas. |
| ✅ | Cámara web | El navegador puede pedir permiso para usar la cámara. |
| ✅ | Detección facial | El sistema detecta el rostro usando inteligencia artificial en el navegador. |
| ✅ | Reconocimiento emocional | Se detectan emociones como feliz, triste, enojado, sorprendido, neutral y disgusto. |
| ✅ | Historial emocional | El frontend envía registros al backend para guardar detecciones. |
| ✅ | Estadísticas | Hay consultas para mostrar resumen del día y estadísticas generales. |
| ✅ | Capturas | La aplicación puede enviar fotos al backend. |
| ✅ | Momentos divertidos | Existe una galería para ver imágenes procesadas. |
| ✅ | Juego facial | Hay un juego en Phaser controlado con movimientos del rostro. |
| ✅ | Backend | Existe una API en Node.js y Express. |
| ✅ | Base de datos | Se usa MySQL para guardar datos. |
| ⚠️ | Perfil de usuario | Hay modal de perfil y avatares, pero no se guarda como usuario real en base de datos. |
| ⚠️ | Identificación por rostro | Existe un identificador facial temporal llamado `faceUser`, pero no es una cuenta de usuario formal. |
| ⚠️ | Procesamiento con n8n | El backend está preparado, pero el procesamiento depende de un flujo externo. |
| ❌ | Login | No hay inicio de sesión. |
| ❌ | Roles | No existen roles como administrador o usuario. |
| ❌ | Exportar reportes | No hay exportación CSV o PDF. |
| ❌ | Modo privado | No hay opción real para usar la app sin guardar historial. |
| ❌ | Pantalla 404 | No hay pantalla para rutas inexistentes. |

## 6. Flujo Del Usuario

Este es el recorrido normal de una persona usando la aplicación:

1. El usuario entra a la página web.
2. La aplicación muestra una pantalla inicial de carga.
3. El usuario llega al dashboard principal.
4. El navegador solicita permiso para usar la cámara.
5. El usuario acepta el permiso.
6. La inteligencia artificial analiza el rostro desde el navegador.
7. La pantalla muestra la emoción detectada y su porcentaje de confianza.
8. La aplicación registra información emocional en el backend.
9. El usuario puede abrir modales de historial, estadísticas, perfil o configuración.
10. Si hay capturas procesadas, puede verlas en "Momentos divertidos".
11. Si entra al juego, puede controlar el personaje con gestos faciales.

## 7. Diseño Visual

La aplicación tiene una estética moderna, oscura y futurista. La idea visual es que parezca un panel inteligente de análisis emocional.

El diseño incluye:

- Dashboard con tres columnas.
- Cámara en el centro.
- Tarjetas con información emocional.
- Indicadores de confianza.
- Reloj en tiempo real.
- Menú lateral.
- Modales para información detallada.
- Galería de imágenes procesadas.
- Vista especial para el juego.

El cambio de colores según la emoción existe en varias partes visuales, pero no cambia completamente todo el tema de la aplicación.

Estado:

| Estado | Elemento visual | Comentario |
|---|---|---|
| ✅ | Diseño oscuro | La interfaz usa un estilo oscuro y moderno. |
| ✅ | Dashboard | Existe la pantalla principal con cámara y datos. |
| ✅ | Menú lateral | Permite navegar entre secciones. |
| ✅ | Modales | Se usan para historial, estadísticas, perfil y configuración. |
| ⚠️ | Cambio dinámico completo | Cambian algunos elementos, pero no todo el tema global. |
| ❌ | Sonidos | No hay sonidos conectados a las emociones. |
| ❌ | Mensajes motivacionales | No existe un sistema real de mensajes por emoción. |

## 8. Frontend Explicado De Forma Simple

El frontend es la parte que ve y usa el usuario. Está construido con React, Vite y Mantine.

Su trabajo es:

- Mostrar la interfaz.
- Encender y apagar la cámara.
- Ejecutar la inteligencia artificial en el navegador.
- Mostrar emociones y estadísticas.
- Enviar datos al backend.
- Mostrar modales.
- Ejecutar el juego facial.

Estructura real del frontend:

```text
uefn-frontend/
├── public/
│   ├── models/                 # Modelos de inteligencia artificial
│   └── assets/avatars/          # Avatares del perfil
├── src/
│   ├── App.jsx                  # Pantalla principal
│   ├── AppRoot.jsx              # Carga inicial de la app
│   ├── components/              # Componentes visuales
│   ├── context/                 # Estado compartido del dashboard
│   ├── data/                    # Datos como emociones y avatares
│   ├── game/                    # Juego facial
│   ├── hooks/                   # Lógica reutilizable
│   ├── services/                # Comunicación con backend
│   └── utils/                   # Funciones auxiliares
```

Importante:

- La aplicación no usa páginas separadas con React Router.
- Funciona como una sola aplicación con modales y cambios de vista.
- La sección de juego reemplaza la vista principal cuando se selecciona.

## 9. Secciones Del Frontend

| Estado | Sección | Qué hace |
|---|---|---|
| ✅ | Inicio | Muestra el dashboard principal. |
| ✅ | Historial reciente | Muestra detecciones guardadas recientemente. |
| ✅ | Emociones de hoy | Muestra cuántas veces apareció cada emoción durante el día. |
| ✅ | Datos históricos | Muestra estadísticas generales de emociones. |
| ✅ | Momentos divertidos | Muestra imágenes procesadas. |
| ✅ | Perfil | Permite elegir nombre y avatar visual. |
| ✅ | Configuración | Permite ajustar parámetros de la aplicación. |
| ✅ | Juego | Abre un juego controlado por la cara. |
| ❌ | Página 404 | No existe una página para rutas inválidas. |
| ❌ | Rutas independientes | No hay URLs separadas por página. |

## 10. Inteligencia Artificial

La inteligencia artificial se ejecuta principalmente en el navegador usando `face-api.js`.

Esto significa que el análisis del rostro se hace en la computadora del usuario, sin enviar video constante al servidor. El backend recibe registros y capturas, pero no procesa el video en vivo.

La IA se usa para:

- Detectar si hay un rostro.
- Reconocer expresiones faciales.
- Calcular porcentajes de confianza.
- Estimar edad aproximada.
- Estimar género aproximado.
- Dibujar puntos faciales.
- Reconocer de forma aproximada si aparece el mismo rostro durante el día.
- Controlar acciones dentro del juego.

Emociones visibles:

| Estado | Emoción | Comentario |
|---|---|---|
| ✅ | Feliz | Se muestra en la interfaz. |
| ✅ | Triste | Se muestra en la interfaz. |
| ✅ | Enojado | Se muestra en la interfaz. |
| ✅ | Sorprendido | Se muestra en la interfaz. |
| ✅ | Neutral | Se muestra en la interfaz. |
| ✅ | Disgusto | Se muestra en la interfaz. |
| ❌ | Asustado como emoción propia | La IA puede detectarlo, pero la app lo agrupa con neutral. |

## 11. Backend Explicado De Forma Simple

El backend es la parte que no ve directamente el usuario. Su función es recibir y guardar información.

Está construido con Node.js, Express y MySQL.

El backend se encarga de:

- Comprobar si la API está funcionando.
- Recibir emociones detectadas.
- Guardar historial emocional.
- Calcular estadísticas.
- Recibir capturas de imágenes.
- Guardar imágenes en carpetas.
- Mostrar imágenes al frontend.
- Entregar capturas nuevas a n8n.
- Recibir confirmación cuando n8n procesa una captura.

Estructura real del backend:

```text
uefn-backend/
├── index.js                 # Inicia el servidor
├── routes/                  # Rutas de la API
├── repositories/            # Consultas a MySQL
├── db/                      # Conexión y esquema de base de datos
├── utils/                   # Funciones auxiliares
├── uploads/                 # Imágenes originales
├── procesed/                # Imágenes procesadas
└── n8n/                     # Flujo externo de procesamiento
```

Importante:

- El backend real no usa Prisma.
- El backend real no usa PostgreSQL.
- El backend real sí guarda imágenes.
- El backend real no tiene login ni usuarios registrados.

## 12. Rutas Del Backend

Las rutas son las direcciones que usa el frontend para comunicarse con el backend.

| Estado | Ruta | Para qué sirve |
|---|---|---|
| ✅ | `GET /health` | Revisar si la API y la base de datos están funcionando. |
| ✅ | `POST /api/history` | Guardar una emoción detectada. |
| ✅ | `GET /api/history/recent` | Consultar historial reciente. |
| ✅ | `GET /api/history/stats` | Consultar estadísticas generales. |
| ✅ | `GET /api/history/summary/today` | Consultar resumen del día. |
| ✅ | `GET /api/history/today/by-emotion` | Consultar conteo por emoción del día. |
| ✅ | `POST /api/captures` | Subir una captura con datos de emoción. |
| ✅ | `GET /api/captures/processed` | Ver capturas procesadas. |
| ✅ | `GET /api/captures/new` | Ver capturas pendientes para n8n. |
| ✅ | `PATCH /api/captures/:id/processed` | Marcar captura como procesada. |
| ✅ | `GET /media/*` | Mostrar imágenes guardadas. |

Rutas que estaban en la idea inicial, pero no existen actualmente:

| Estado | Ruta faltante | Comentario |
|---|---|---|
| ❌ | `/api/users` | No hay CRUD de usuarios. |
| ❌ | `/api/avatars` | Los avatares están en frontend, no en backend. |
| ❌ | `/api/settings` | No hay configuración guardada por usuario. |
| ❌ | `/api/exports` | No hay exportación CSV o PDF. |
| ❌ | `/api/auth` | No hay autenticación. |

## 13. Base De Datos

La base de datos guarda información para que el proyecto no dependa solo de lo que ocurre en pantalla.

Actualmente se usa MySQL y existen dos tablas principales.

| Tabla | Qué guarda |
|---|---|
| `emotion_recent_history` | Registros rápidos de emociones detectadas. |
| `emotion_captures` | Capturas de imágenes junto con emoción, confianza y estado de procesamiento. |

Explicado de forma simple:

- `emotion_recent_history` funciona como una libreta de detecciones.
- `emotion_captures` funciona como un álbum de capturas emocionales.

Entidades que todavía no existen:

| Estado | Entidad | Comentario |
|---|---|---|
| ❌ | Usuario real | No hay tabla `User`. |
| ❌ | Avatar en base de datos | Los avatares existen como archivos del frontend. |
| ❌ | Configuración por usuario | No hay tabla para guardar preferencias. |
| ❌ | Estadísticas precalculadas | Las estadísticas se calculan consultando los datos existentes. |
| ❌ | Mensajes motivacionales | No hay tabla ni sistema conectado. |

## 14. Capturas E Imágenes

En la idea original se mencionaba que el backend no debía guardar imágenes. Pero el código actual funciona de otra manera: sí guarda imágenes.

Esto es importante aclararlo para no explicar algo incorrecto en la exposición.

Estado real:

| Estado | Elemento | Explicación |
|---|---|---|
| ✅ | Imagen original | Se guarda en la carpeta `uploads`. |
| ✅ | Imagen procesada | Se espera en la carpeta `procesed`. |
| ✅ | Galería | El frontend muestra capturas procesadas. |
| ✅ | Endpoint de medios | `/media/*` permite ver imágenes guardadas. |
| ⚠️ | Privacidad | Si se guardan imágenes, se debe explicar el consentimiento del usuario. |
| ❌ | Backend solo con datos numéricos | Esto ya no representa el proyecto actual. |

## 15. Integración Con n8n

n8n se usa como un proceso externo para trabajar con capturas.

El flujo esperado es:

1. El frontend envía una captura al backend.
2. El backend guarda la captura como nueva.
3. n8n consulta capturas nuevas.
4. n8n procesa la imagen usando una IA externa.
5. n8n devuelve el resultado al backend.
6. El frontend muestra la imagen en "Momentos divertidos".

Estado:

| Estado | Parte | Comentario |
|---|---|---|
| ✅ | Backend preparado | Existen rutas para capturas nuevas y procesadas. |
| ✅ | Frontend preparado | Existe galería de momentos divertidos. |
| ⚠️ | Procesamiento externo | Depende de que n8n esté configurado correctamente. |

## 16. Juego Facial

El proyecto también incluye un juego 2D usando Phaser.

Lo especial del juego es que no depende principalmente del teclado. La idea es controlar el personaje con movimientos faciales detectados por la cámara.

Acciones esperadas:

| Estado | Acción | Explicación |
|---|---|---|
| ✅ | Mirar izquierda/derecha | Sirve para mover el personaje. |
| ✅ | Abrir la boca | Sirve para saltar. |
| ✅ | Sonreír | Sirve para correr o aumentar velocidad. |
| ✅ | Levantar cejas | Puede usarse para disparar. |
| ✅ | Calibración | Existe una etapa para preparar el control facial. |
| ✅ | Pantallas de juego | Hay inicio, victoria y game over. |
| ⚠️ | Sonidos | El requerimiento los menciona, pero no deben darse por terminados sin validación. |

## 17. Seguridad Y Privacidad

Como el proyecto usa cámara y capturas, la privacidad es muy importante.

Lo que ya existe:

- La detección facial ocurre principalmente en el navegador.
- El backend usa CORS.
- El backend usa Helmet.
- El backend usa límites de peticiones.
- Las imágenes tienen límite de tamaño.

Lo que falta:

| Estado | Seguridad faltante | Comentario |
|---|---|---|
| ❌ | Login | No hay autenticación. |
| ❌ | Roles | No hay permisos por tipo de usuario. |
| ❌ | Modo privado | No hay opción para evitar guardar datos. |
| ❌ | Borrar datos desde UI | No hay flujo completo para eliminar historial y capturas. |
| ❌ | Consentimiento formal | Sería recomendable agregar una pantalla clara antes de guardar imágenes. |

Frase recomendada:

> La aplicación analiza el rostro en tiempo real desde el navegador. Cuando se activa la función de capturas, algunas imágenes sí se guardan en el backend, por lo que una versión final debe incluir consentimiento y opciones para eliminar datos.

## 18. Tecnologías Usadas

| Tecnología | Para qué se usa |
|---|---|
| React | Construir la interfaz. |
| Vite | Ejecutar y construir el frontend. |
| Mantine | Crear componentes visuales modernos. |
| face-api.js | Detectar rostro, emociones y puntos faciales. |
| TensorFlow.js | Ejecutar modelos de IA en el navegador. |
| Phaser | Crear el juego 2D. |
| Node.js | Ejecutar el backend. |
| Express | Crear la API. |
| MySQL | Guardar historial y capturas. |
| multer | Recibir imágenes en el backend. |
| n8n | Procesar capturas de forma externa. |
| Docker | Preparar despliegue por contenedores. |

Tecnologías mencionadas en la idea inicial pero no usadas realmente:

| Estado | Tecnología | Comentario |
|---|---|---|
| ❌ | Prisma | El backend usa SQL directo con `mysql2`. |
| ❌ | PostgreSQL | El proyecto usa MySQL. |
| ❌ | JWT | No hay autenticación con tokens. |
| ❌ | Recharts | Está instalado, pero los gráficos reales usan otros recursos visuales. |

## 19. Qué Está Terminado Y Qué Falta

### Implementado

- ✅ Cámara web.
- ✅ Detección facial.
- ✅ Emociones en tiempo real.
- ✅ Porcentaje de confianza.
- ✅ Edad y género aproximados.
- ✅ Puntos faciales.
- ✅ Dashboard.
- ✅ Historial reciente.
- ✅ Estadísticas del día.
- ✅ Datos históricos.
- ✅ Capturas.
- ✅ Momentos divertidos.
- ✅ Perfil visual con avatares.
- ✅ Configuración visual.
- ✅ Juego facial.
- ✅ Backend con Express.
- ✅ Base de datos MySQL.
- ✅ Servicio de imágenes.

### Parcial

- ⚠️ Identificación por rostro.
- ⚠️ Perfil del usuario.
- ⚠️ Estadísticas filtradas por rostro.
- ⚠️ Procesamiento con n8n.
- ⚠️ Cambio visual según emoción.
- ⚠️ Flujo de despliegue completo.

### Falta Por Hacer

- ❌ Login.
- ❌ Roles.
- ❌ Usuarios reales en base de datos.
- ❌ Guardar perfil de usuario.
- ❌ Configuración por usuario.
- ❌ Exportar reportes.
- ❌ Modo privado.
- ❌ Borrar historial desde la interfaz.
- ❌ Borrar capturas desde la interfaz.
- ❌ Pantalla 404.
- ❌ Mensajes motivacionales.
- ❌ Sonidos.
- ❌ Consentimiento formal para capturas.

## 20. Roadmap Recomendado

Para continuar el proyecto, se recomienda trabajar en este orden:

1. Agregar una pantalla clara de consentimiento para cámara y capturas.
2. Permitir borrar historial y capturas desde la interfaz.
3. Guardar el perfil del usuario de forma permanente.
4. Conectar mejor el identificador `faceUser` con estadísticas e historial.
5. Revisar y probar el flujo completo de n8n.
6. Agregar modo privado.
7. Agregar exportación simple de reportes.
8. Agregar mensajes motivacionales por emoción.
9. Agregar sonidos opcionales.
10. Agregar autenticación solo si el proyecto necesita usuarios reales.

## 21. Cómo Explicar El Proyecto En La Exposición

No conviene decir solamente:

> Mi proyecto detecta emociones.

Una forma más completa sería:

> MoodVision AI es una plataforma web que usa inteligencia artificial y visión por computadora para analizar expresiones faciales en tiempo real. La aplicación muestra la emoción dominante del usuario, guarda historial, genera estadísticas, permite capturas procesadas y además incluye un juego controlado con gestos faciales.

## 22. Qué Mostrar En La Demo

Durante la exposición, lo más importante es mostrar el proyecto funcionando.

Orden recomendado:

1. Abrir la aplicación.
2. Activar la cámara.
3. Mostrar cómo detecta el rostro.
4. Sonreír o cambiar expresión para que cambie la emoción.
5. Explicar el porcentaje de confianza.
6. Activar o mostrar puntos faciales.
7. Abrir historial reciente.
8. Abrir emociones de hoy.
9. Mostrar momentos divertidos.
10. Entrar al juego facial.
11. Explicar que el backend guarda información real.

## 23. Cómo Explicar La IA Sin Ser Muy Técnico

Explicación recomendada:

> La inteligencia artificial analiza puntos importantes del rostro, como ojos, boca y cejas. Con esos puntos y expresiones, estima qué emoción es más probable. Por eso la aplicación no dice que una emoción sea absoluta, sino que muestra un porcentaje de confianza.

Si la detección falla:

> La detección emocional depende de la luz, la cámara, el ángulo del rostro y la expresión del usuario. Por eso puede variar y se maneja como una estimación.

## 24. Cómo Explicar El Backend

Explicación recomendada:

> El backend funciona como el lugar donde la aplicación guarda información. Recibe emociones detectadas, guarda historial, calcula estadísticas y almacena capturas. Gracias a eso, el usuario puede revisar lo que ocurrió después y no solo ver información en vivo.

## 25. Frase Final Recomendada

MoodVision AI demuestra cómo una aplicación web puede usar inteligencia artificial para interpretar emociones humanas en tiempo real y convertirlas en una experiencia visual, educativa e interactiva.
