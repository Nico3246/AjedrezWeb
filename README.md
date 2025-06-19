# Documentación del Proyecto AjedrezWeb

AjedrezWeb es una aplicación web para jugar ajedrez directamente desde el navegador, desarrollada utilizando JavaScript, Vite, chess.js y chessboard.js. El objetivo del proyecto es proporcionar una experiencia de ajedrez interactiva, moderna y fácilmente extensible, tanto para jugadores como para desarrolladores interesados en contribuir.

---

## Tabla de Contenidos

* [Características](#características)
* [Instalación](#instalación)
* [Uso](#uso)
* [Estructura del Proyecto](#estructura-del-proyecto)
* [Scripts Disponibles](#scripts-disponibles)
* [Futuras Mejoras](#futuras-mejoras)
* [Contribuciones](#contribuciones)
* [Licencia](#licencia)

---

## Características

* Lógica de ajedrez validada y robusta mediante la biblioteca `chess.js`.
* Visualización del tablero y piezas mediante `chessboard.js`.
* Interfaz responsiva y dinámica desarrollada sobre Vite.
* Partidas entre dos jugadores locales en el mismo dispositivo.
* Próximamente: gestión de rating ELO, emparejamiento de jugadores y modo en línea.

## Instalación

Sigue estos pasos para instalar y ejecutar la aplicación en tu entorno local:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/Nico3246/AjedrezWeb.git
   cd AjedrezWeb
   ```
2. Instala las dependencias:

   ```bash
   npm install
   ```
3. Ejecuta la aplicación en modo desarrollo:

   ```bash
   npm run dev
   ```
4. Accede a la aplicación desde tu navegador en `http://localhost:3000`.

## Uso

* Mueve las piezas arrastrando y soltando sobre el tablero.
* Todos los movimientos se validan automáticamente conforme a las reglas oficiales del ajedrez.
* El juego está orientado inicialmente a partidas locales entre dos jugadores.
* Próximamente: funcionalidades para registro de usuarios y partidas en línea.

## Estructura del Proyecto

* `index.html`: Página principal de la aplicación.
* `src/main.js`: Inicialización de la aplicación y configuración de bibliotecas.
* `src/components/`: Componentes de la interfaz de usuario (tablero, controles, etc.).
* `src/lib/`: Integración y lógica relacionada con chess.js.
* `package.json`: Definición de scripts y dependencias del proyecto.
* (Opcional) `server/`: Backend y base de datos (en desarrollo).

## Scripts Disponibles

* `npm run dev`: Inicia el servidor de desarrollo con Vite.
* `npm run build`: Genera una versión optimizada para producción.
* `npm run preview`: Sirve la versión generada para revisión local.

## Futuras Mejoras

* Integración con API para partidas en línea y emparejamiento automático.
* Registro y autenticación de usuarios con sistema de ELO.
* Historial y análisis de partidas jugadas.
* Implementación de modo de juego contra inteligencia artificial.
* Mejora de compatibilidad con dispositivos móviles y diseño responsive.

## Contribuciones

Las contribuciones al proyecto son bienvenidas. Para colaborar, sigue estos pasos:

1. Realiza un fork del repositorio.
2. Crea una nueva rama para tu funcionalidad o corrección:

   ```bash
   git checkout -b feature/nueva-funcion
   ```
3. Realiza tus cambios y haz commit.
4. Envía tu rama al fork y abre un Pull Request, explicando claramente la mejora o corrección propuesta.

## Licencia

Este proyecto se distribuye bajo la licencia [MIT](LICENSE). Consulta el archivo `LICENSE` para más información.

---


