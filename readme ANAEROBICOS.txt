1 Crear Columnas Nuevas:

Inserte  Columna A para el Código

Inserte Columna C para la Descripción

2 Extraer Código (en Columna A):
usé la formula =REGEXEXTRACT(B2, "^\d+") arrastrandola en toda la columna

3 Extraer Descripción (en Columna C):
use la formula =REGEXREPLACE(B2, "^\d+\s*", "")
arrastrandola en toda la columna

4 Convertir Fórmulas a Valores:
Usé Copiar (Ctrl+C) y con las celdas seleccionadas, hice clic derecho y elegí "Pegado especial" > "Solo valores" (Ctrl+mayus+V)

5 Limpiar Espacios en Blanco:
Seleccione toda la tabla de datos.
Desde Datos > Limpieza de datos > Cortar espacios en blanco, quite los espacios en blanco de toda la hoja. 

5 Elimine Columnas y Filas Innecesarias
utilice las opciones de la barra de herramientas (color de relleno, color de texto, negritas) para dar formato a los encabezados y al texto según necesites.






