# PsiClinic Mac — Apple Silicon portable

Edición nativa de PsiClinic para Mac con chip M1 y posteriores. Requiere macOS 13 Ventura o posterior. No requiere Rosetta, instalador, Node.js ni SQLite instalados por separado.

Este es un producto independiente de la edición Windows: tiene nombre, identificador de macOS, carpeta de datos y canal de actualizaciones propios. Este repositorio se dedica exclusivamente a Mac.

## Descarga

[Descargar la última versión de PsiClinic Mac](https://github.com/eduardoperezpsic/psiclinic-mac/releases/latest)

La primera versión es 1.5.13, adaptada de PsiClinic Premium 1.5.13. Descarga el ZIP cuyo nombre termina en Apple-Silicon-Portable.zip; la suma SHA-256 y las instrucciones se incluyen en la publicación.

## Uso portable

1. Descomprime el ZIP y mueve PsiClinic Mac.app con Finder a una carpeta local con permisos de escritura, fuera de carpetas sincronizadas con la nube.
2. Abre PsiClinic Mac.app. El programa creará PsiClinic Mac Datos junto a la aplicación.
3. Para trasladarlo, cierra PsiClinic y copia juntos el .app y PsiClinic Mac Datos. No borres ni separes esa carpeta. Al cambiar de Mac puede ser necesario volver a iniciar sesión.

El programa usa firma ad hoc y no está notarizado por Apple. Si macOS bloquea la primera apertura, comprueba el origen de la descarga y usa Configuración del Sistema > Privacidad y seguridad > Abrir de todos modos. No requiere desactivar Gatekeeper. [Instrucciones de Apple](https://support.apple.com/es-mx/102445).

Para recuperar una sesión de Windows o de la edición Mac anterior, exporta un respaldo .psibackup desde el programa de origen y usa Restaurar una sesión en PsiClinic Mac. Conserva el original hasta comprobar la restauración.

## Actualizaciones independientes

PsiClinic Mac consulta exclusivamente las releases de eduardoperezpsic/psiclinic-mac y solo acepta paquetes Apple Silicon. Comprueba SHA-256, identidad, versión, arquitectura ARM64 y firma; espera al cierre antes de reemplazar el .app y conserva la aplicación anterior. Los datos permanecen en su carpeta.

Las publicaciones de Mac usan etiquetas mac-vX.Y.Z y su numeración propia. Windows conserva su repositorio y su canal habitual. No coloques aquí paquetes de Windows.

Este repositorio público contiene documentación y paquetes de distribución. No contiene expedientes, claves, credenciales ni el código fuente de la aplicación. El código de mantenimiento se conserva localmente. Se preservan la autoría y los términos de distribución incluidos en el programa.

El asistente local opcional requiere Ollama y un modelo local si deseas usar esa función; las funciones clínicas pueden ejecutarse sin ellos.
