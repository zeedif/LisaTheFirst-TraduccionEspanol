# LISA: The First - Traducción al Español

Traducción al español de *LISA: The First* (RPG Maker 2003). Toma la traducción «La primeriza Lisa» de Pinypon (Horchata Scans, TraduSquare) y la adapta a la versión de Steam.

## Instalación

Extrae el zip de [Releases](../../releases/latest) en la carpeta `Lisa_1\Lisa_1` de la instalación de Steam, donde está `Lisa.exe`, reemplazando los archivos existentes, y juega con `Player.exe`.

Para lanzarlo desde Steam, renombra `Lisa.exe` (por ejemplo, a `Lisa_original.exe`) y copia `Player.exe` con el nombre `Lisa.exe`.

## Historial

1. **Estado base**: archivos originales (inglés, Steam) que toca la traducción.
2. **Traducción de Horchata Scans v1.0**: el parche tal cual, con `Player.exe` (EasyRPG Player). Solo se restaura en `RPG_RT.ldb` un campo sin texto que el programa de traducción omitió, para que el diff muestre únicamente lo traducido.
3. **Objetos y menú**: la traducción dejaba en inglés lo que se ve en el inventario y el menú.
   - `RPG_RT.ldb`: objetos (nombres y descripciones), título de la protagonista y vocabulario del menú, con los nombres que la traducción usa en los diálogos.
   - `Map0017.lmu` y `Map0019.lmu`: dos erratas.

## Licencia de EasyRPG Player

`Player.exe` es [EasyRPG Player](https://easyrpg.org/player/), software libre bajo licencia GPLv3. Su código fuente está en [github.com/EasyRPG/Player](https://github.com/EasyRPG/Player).

## Agradecimientos

- **Traducción y gráficos:** Pinypon, con la corrección y el betatesting de Diananyan (Horchata Scans, TraduSquare), hecha con [Translator++](https://dreamsavior.net/translator-plusplus/) de Dreamsavior. [Proyecto en TraduSquare](https://tradusquare.es/proyectos/la-primeriza-lisa/).
- **Reproductor:** [EasyRPG Player](https://easyrpg.org/player/).
- **Juego:** Dingaling, en [Steam](https://store.steampowered.com/app/2743030/LISA_The_First/).
