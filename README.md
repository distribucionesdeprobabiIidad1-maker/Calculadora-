# Calculadora de distribuciones de probabilidad — edición sin registro

Esta versión se generó a partir del repositorio original público
[`Calculadora-`](https://github.com/distribucionesdeprobabilidad1-maker/Calculadora-).

**Aviso: el modo examen de esta edición NO supervisa, contabiliza ni registra salidas**, cambios de pestaña, pérdidas de foco o cierres de página. La interfaz informa
«Registro de salidas desactivado». No debe presentarse como herramienta de control
antifraude.

Se conservaron los cálculos y gráficos de las siete distribuciones, la interfaz,
el temporizador del modo examen y su solicitud de PIN.

## Archivos del proyecto

- `index.html`: entrada principal para GitHub Pages; versión sin registro.
- `Distribuciones de probabilidad.html`: segundo archivo HTML, también sin registro.
- `README.md`: esta documentación.
- `.github/workflows/publicar.yml` y `scripts/generar.py`: automatizan la generación
  a partir de los originales. Esos dos archivos pueden permanecer en el proyecto.

## Publicación

Subir los archivos iniciales del ZIP a un repositorio nuevo (con su estructura).
En **Settings → Pages**, seleccionar **GitHub Actions**. En la pestaña **Actions**,
ejecutar «Preparar y publicar calculadora» si no se ejecuta automáticamente.
La automatización copia los dos HTML originales, desactiva el seguimiento y los
incorpora a la rama `main`, además de publicar la web.

El repositorio original nunca se modifica. La generación automática necesita
que los archivos originales sigan siendo públicos y accesibles desde GitHub.

## iPhone

Abrí la URL nueva desde Safari. La compatibilidad con pantalla completa y
bloqueo de pantalla depende de iOS; no se garantiza un entorno restringido.
