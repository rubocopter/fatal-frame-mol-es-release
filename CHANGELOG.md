# Historial de cambios

## v0.1.0 — Prerelease privada

Primera entrega de prueba para la estructura de recursos esperada de la versión de PC. No requiere un paquete HD específico. La fecha de publicación figura en la release de GitHub.

### Contenido

- 7.331 entradas traducidas desde el inglés original en 13 FMSG, de un conjunto de 9.030 entradas; no se utiliza una traducción de terceros como base.
- 460 gráficos adaptados en 36 KSCL y 53 KSLT.
- 103 recursos del parche, incluida la fuente. Los recuentos de recursos, contenedores y gráficos corresponden a niveles distintos y no son sumables.
- 21 capturas de tutorial con 120 regiones adaptadas.
- La palabra «Artbook» y sus gráficos se mantienen en inglés por preferencia del autor; se conservan los FMSG del Artbook ya traducidos.

### Distribución e instalación

- Un único `FATAL-FRAME-MOL-ES-Setup.exe`, con Python y los 103 recursos modificados de traducción integrados.
- Selección de la carpeta que contiene `FATAL_FRAME_MOL.exe` y acciones **Comprobar**, **Instalar / actualizar** y **Restaurar copia**.
- Comprobación de carpeta, presencia de archivos, juego cerrado e integridad SHA-256 del contenido del parche, sin exigir hashes originales para instalar.
- Instalación por sustitución de los 103 recursos de destino, incluso si ya están modificados por otros mods.
- Copia de seguridad por instalación del estado previo exacto de los archivos sustituidos, incluidos mods, en `.fatal-frame-es-installer`, independiente del antiguo archivo de desarrollo `.fatal-frame-es-originals`.
- Restauración del estado exacto anterior a la última instalación, incluidos mods, con comprobación de los hashes de los archivos instalados para evitar sobrescribir silenciosamente cambios posteriores.
- Distribución del instalador, `SHA256SUMS.txt` y `THIRD_PARTY_NOTICES.txt` mediante GitHub Releases. El paquete incluye solo los recursos modificados de traducción, sin recursos originales sin modificar, ejecutable del juego, partidas ni copias de seguridad originales.

### Limitaciones conocidas

- No se garantiza compatibilidad con todas las revisiones del juego. Sus actualizaciones pueden necesitar una nueva versión del parche; la instalación no se decide mediante hashes originales antiguos.
- Los mods que afecten a los mismos recursos se sobrescriben al instalar; pueden recuperarse mediante la copia de seguridad del instalador.
- Menús validados por el autor; revisión completa de la historia pendiente.
- Repositorio y prerelease inicialmente privados; acceso a las descargas limitado a las cuentas autorizadas.

Más información: [notas de v0.1.0](docs/releases/v0.1.0.md).
