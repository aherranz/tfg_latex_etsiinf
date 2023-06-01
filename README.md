# Plantilla LaTeX para Memoria de Trabajo Fin de Grado/Master de la ETSIINF / UPM

Para usar esta plantilla te recomendamos:

0. Descarga la última versión de la plantilla, puedes encontrar un
   archivo en https://github.com/aherranz/tfg_latex_etsiinf/tags o en
   la página web de la escuela. **Importante:** si quieres poner tu
   trabajo fin de estudios bajo control de versiones es mejor que **no
   clones** este repo.
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
6. A veces es bastante común tener que compilar varias veces el
   fichero para que LaTeX calcule las referencias correctamente.
7. Si usas bibliografía, tendrás que meter entradas con formato bibtex
   en el fichero `secciones/biblio.bib` y usar el programa bibtex para
   generar la bibliografía recompilando el fichero de nuevo.

Ahora ya puedes generar el PDF ejecutando los siguientes mandatos en tu terminal:

```bash
pdflatex tfg_etsiinf_LuisAmigo
bibtex tfg_etsiinf_LuisAmigo
pdflatex tfg_etsiinf_LuisAmigo
pdflatex tfg_etsiinf_LuisAmigo
```

## TODO

Quedan algunas cosas por mejorar en esta plantilla:

- Analizar la mejora en la accesibilidad al contenido de los
  documentos (etiquetado): explorar por ejemplo el paquete
  accesibility (cuidado que tiene algunos problemas reconocidos).
