### Proyecto_Pandas_Tiburones


![imagina a un panda caneando a un tiburon](https://github.com/pizornpy/Proyecto_Pandas_Tiburones/blob/main/fotos/pandas%20vs%20tiburones.jpg
)


El objetivo de este trabajo era limpiar una base de datos siguiendo una serie de criterios distintos. En primer lugar, las dimensiones finales del dataframe no podían ser inferiores a 6000 filas x 24 columnas. En segundo lugar están las consideraciones relativas cualquier limpieza de un dataset, no debería haber valores nulos y deberíamos tener en consideración el uso de la memoria. Estos datos no eran excesivamente extensos, pero nos parece una práctica interesante para tener en cuenta. Hemos ejercitado esta consideración reduciendo al mínimo posible el tipo de dato de aquellas columnas que lo admitieran, es  decir, aquellas columnas que no hemos utilizado han quedado como int de 8 bits.

Con respecto al criterio que hemos utilizado para llenar valores nulos debe decirse que ha ido cambiando y ha sido una cuestión de ajuste. Le hemos dedicado especial cariño a la columna de especies de tiburón, la cual hemos rellenado buscando información de un artículo el cual queda adjuntado en la carpeta "fuentes". Hemos encontrado más artículos interesantes que podrían haber servido como base para una investigación más profunda, al final las referencias a estos otros artículos han sido más bien pocas, pero como tampoco molestan pues los hemos añadido a su vez a la carpeta "fuentes". 

El objetivo con la búsqueda de información externa, en este caso las especies de tiburón que más frecuentemente atacan a humanos, ha servido para establecer los filtros y se ha pretendido reducir su influencia a la hora de añadir información nueva, pero a buen seguro que han saltado falsos positivos.
