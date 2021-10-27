# Plantilla LaTeX para Memoria de Trabajo Fin de Grado de la ETSIINF / UPM

Para usar esta plantilla te recomendamos:

1. Cambiar el nombre del documento principal (`tfg_etsiinf_plantilla.tex`) para
   que incluya el nombre del alumno (ej. `tfg_etsiinf_LuisAmigo.tex`).
2. Modifica los datos de tu TFG en `datos_tfg.tex`.
3. Observa el fichero documento principal y cómo se van incluyendo los
   contenidos de la memoria a partir de los ficheros en el directorio
   `secciones`.
4. Por supuesto puedes modificar la estructura de secciones propuestas
   para adecuarla al tipo de trabajo que realices.
5. Si no sabes LaTeX te recomendamos explorar el contenido de los
   ficheros para aprender un uso básico y algunas buenas prácticas.

## TODO

Quedan algunas cosas por mejorar en esta plantilla:

- Convertir el preámbulo en un `sty` en vez de un fichero latex y así
  poder usar \usepackage{tfg_etsiinf} en vez de \input{preambulo}.
- Mejorar el crash-course de LaTeX en la intro de la plantilla.
