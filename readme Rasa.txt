Descargué el archivo TXT, lo abrí en el Bloc de notas, lo guardé y luego lo importé directamente desde Google Sheets.

Para asegurar que el Código fuera un Número Entero, utilicé la fórmula =REGEXEXTRACT(TO_TEXT(A1), "\d+"), eliminando así los caracteres que no correspondían a un número.

Para eliminar espacios en blanco, fui a Datos > Limpieza de datos > Cortar espacios en blanco. Luego, para unir la información de ambas columnas, empleé la fórmula =CONCATENAR(A5," ",B5).

Para Eliminar Caracteres Específicos:Fui a Editar > Buscar y reemplazar.
En el campo "Buscar", pegué los caracteres \xe2\x86\x92, 伃, 厲.Dejé el campo "Reemplazar por" vacío.
Finalmente, hice clic en "Reemplazar todo".

Para Controlar Cabeceras, verifiqué manualmente y edité las celdas de la primera fila para que coincidieran con el modelo.

Creé una Nueva Columna Combinada (A y B) en la columna C.

Moví la columna G a la D para que coincidiera con el modelo.