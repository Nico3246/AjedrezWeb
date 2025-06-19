# AjedrezWeb

AjedrezWeb es una aplicación web para jugar ajedrez desde el navegador, desarrollada utilizando JavaScript, Vite, chess.js y chessboard.js. El proyecto busca ofrecer una experiencia de ajedrez interactiva, moderna y fácilmente extensible.

## Características

* Lógica de ajedrez validada y robusta mediante la biblioteca `chess.js`.
* Visualización del tablero y piezas con `chessboard.js`.
* Interfaz responsiva y dinámica gracias al entorno Vite.
* Partidas entre dos jugadores locales en el mismo dispositivo.
* Próximamente: gestión de rating ELO, emparejamiento de jugadores y modo online.

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/Nico3246/AjedrezWeb.git
cd AjedrezWeb
```

2. Instalar dependencias:

```bash
npm install
```

3. Ejecutar la aplicación en modo desarrollo:

```bash
npm run dev
```

4. Acceder a la aplicación desde el navegador en `http://localhost:3000`.

## Uso

* Los usuarios pueden mover piezas arrastrando y soltando en el tablero.
* Los movimientos se validan automáticamente de acuerdo con las reglas oficiales del ajedrez.
* El juego está diseñado inicialmente para partidas locales entre dos jugadores.
* Próximamente se implementarán el registro de usuarios y las partidas en línea.

## Estructura del Proyecto

* `index.html`: Página principal.
* `src/main.js`: Inicialización de la aplicación y configuración de las bibliotecas.
* `src/components/`: Componentes de la interfaz de usuario (tablero, controles, etc.).
* `src/lib/`: Integración y lógica relacionada con chess.js.
* `package.json`: Definición de scripts y dependencias del proyecto.
* (Opcional) `server/`: Backend y base de datos (en desarrollo).

## Scripts Disponibles

* `npm run dev`: Inicia el servidor de desarrollo con Vite.
* `npm run build`: Genera una build optimizada para producción.
* `npm run preview`: Sirve la build generada para revisión local.

## Futuras Mejoras

* Integración con API para partidas en línea y emparejamiento automático.
* Registro y autenticación de usuarios con sistema de ELO.
* Historial y análisis de partidas jugadas.
* Modo de juego contra inteligencia artificial.
* Mejora de compatibilidad con dispositivos móviles y diseño responsive.

## Contribuciones

Las contribuciones al proyecto son bienvenidas. Para colaborar:

1. Realiza un fork del repositorio.
2. Crea una nueva rama para tu funcionalidad o corrección:
   `git checkout -b feature/nueva-funcion`
3. Realiza tus cambios y haz commit.
4. Envía tu rama al fork y abre un Pull Request explicando claramente la mejora o corrección propuesta.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Revisa el archivo `LICENSE` para más información.

la licencia tiene que ser enlace
