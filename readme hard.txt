1. Descarga e Importación del Archivo
Se descargó el archivo "Copia de hurl.csv".

Se importó el archivo a Google Sheets utilizando la opción Archivo > Importar.

2. Configuración Regional
Se ajustó la configuración regional de la hoja de cálculo a Argentina (Archivo > Configuración > General > Argentina)

3. Copia de Formato del Modelo
Se aplicó el formato visual (con el rodillo de la barra de herramientas) del archivo "Modelo" a la lista de trabajo.

4. Corrección de Precios (Columna F y G)
Se insertó una nueva columna en la posición G.

Se copiaron los datos de la columna F a esta nueva columna G, y luego se borraron los datos originales de la columna F. Esto preparó la columna F para recibir los valores corregidos.

En la columna F (ahora vacía), se ingresó la fórmula =G2*1000 (ajustando la fila de inicio según los datos)

Esta fórmula se arrastró hacia abajo para aplicar la multiplicación por 1000 a todos los precios de la columna G, asegurando que los valores y la posición de la coma decimal fueran correctos en la columna F.

5. Conversión de Fórmulas a Valores
Para eliminar las fórmulas y dejar solo los valores numéricos, se copió toda la columna F (Ctrl+C).
Luego, se realizó un "Pegado especial" seleccionando "Solo valores" (Ctrl+Shift+V o Clic derecho > Pegado especial > Solo valores) en la misma columna F.

6. Aplicación de Formato Numérico
Se seleccionó la columna G (la que contiene los precios modelo, y que ahora contendría los precios correctos si la F original fue borrada o movida), y se aplicó el formato "Número" desde Formato > Número > Número.

7. Ordenamiento de Precios
Para ordenar los precios de mayor a menor.

Se hizo clic derecho y se eligió "Ordenar rango" > "Opciones avanzadas de ordenación de rango...".

Se seleccionó la columna "Precio" boton secundario elijo la opcion Ordenar Hoja De la Z a la A

8. Limpieza de Columnas
Se eliminaron todas las columnas que no eran pertinentes, dejando solo la información esencial y solicitada para los artículos:

EMPRESA
CODIGO
DESCRIPCION
DESCRIPCION2
ORIGINAL
PRECIO 
PRECIO FINAL
MARCA
LISTA
NOV