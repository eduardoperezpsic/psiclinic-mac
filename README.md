# PsiClinic Mac — Apple Silicon portable

Edición nativa de PsiClinic para Mac con chip M1 y posteriores. Requiere macOS 13 Ventura o posterior. No requiere Rosetta, instalador, Node.js ni SQLite instalados por separado.

## Descarga

[Descargar la última versión de PsiClinic Mac](https://github.com/eduardoperezpsic/psiclinic-mac/releases/latest)

La primera versión es 1.5.13, adaptada de PsiClinic Premium 1.5.13. Descarga el ZIP cuyo nombre termina en Apple-Silicon-Portable.zip; la suma SHA-256 y las instrucciones se incluyen en la publicación.

## Uso portable

1. Descomprime el ZIP y mueve PsiClinic Mac.app con Finder a una carpeta local con permisos de escritura, fuera de carpetas sincronizadas con la nube.
2. Abre PsiClinic Mac.app. El programa creará PsiClinic Mac Datos junto a la aplicación.
3. Para trasladarlo, cierra PsiClinic y copia juntos el .app y PsiClinic Mac Datos. No borres ni separes esa carpeta. Al cambiar de Mac puede ser necesario volver a iniciar sesión.

El programa usa firma ad hoc y no está notarizado por Apple. Si macOS bloquea la primera apertura, comprueba el origen de la descarga y usa Configuración del Sistema > Privacidad y seguridad > Abrir de todos modos. No requiere desactivar Gatekeeper. [Instrucciones de Apple](https://support.apple.com/es-mx/102445).

Para recuperar una sesión de Windows o de la edición Mac anterior, exporta un respaldo .psibackup desde el programa de origen y usa Restaurar una sesión en PsiClinic Mac. Conserva el original hasta comprobar la restauración.
