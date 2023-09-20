Archivos recibidos de los ministerios públicos provinciales
========================================================

En este conjunto de datos se presentan los archivos recibidos de los ministerios públicos provinciales según lo establecido en el [Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia (tabla1, tabla1.1, tabla1.2, tabla2 y tabla2.1) y número de orden de la tabla dentro del envío.

http://datos.jus.gob.ar/dataset/archivos-recibidos-de-los-ministerios-publicos-provinciales


Características
---------------

-   **Fecha de Primera Publicación:** 23/04/2019

-   **Tags o Etiquetas:** Buenos Aires, Catamarca, Chaco, Chubut, Ciudad Autónoma de Buenos Aires, Corrientes Córdoba, Entre Ríos Formosa, Jujuy, La Pampa, La Rioja, Mendoza, Misiones, Neuquén, Río Negro, Salta, San Juan, San Luis, Santa Cruz, Santa Fe, Santiago del Estero, Tierra del Fuego, Tucumán, actos procesales, casos, causas, código penal, delitos, instituciones, investigación penal preparatoria, ministerios públicos

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Programa Justicia Abierta

-   **Autor:** Instituciones firmantes del Convenio Interjurisdiccional de Datos Abiertos de Justicia

-   **Responsable:** Instituciones firmantes del Convenio Interjurisdiccional de Datos Abiertos de Justicia

-   **Grupo:** Instituciones de Justicia

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Arcivos recibidos de los ministerios públicos provinciales - AAAA

-   **Nombre:** mp-archivos-recibidos-AAAA.zip

-   **Descripción del contenido:** Contiene los archivos remitidos por el ministerio público de cada provincia en el año AAAA. El nombre de cada archivo corresponde al nombre de provincia, institución, fecha de envío, nombre de las tablas remitidas según el Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia (tabla1, tabla1.1, tabla1.2, tabla2 y tabla2.1) y número de orden de la tabla dentro del envío.

-   **Formato:** ZIP

-   **Rango temporal:** archivos recibidos por los ministerios públicos de cada provincia en el año AAAA

### Archivos del recurso

### Tabla1 - CASOS

- **Nombre del recurso:** nombre-provincia-mp-AAAAMMDD-tabla1-casos-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso

-   **id_caso (string):** código que identifica el caso. Cada provincia usa su propio formato de identificación de caso

-   **id_circunscripcion (string):** indica la unidad geográfica en que está dividida la institución

-   **id_unidad_mp (string):** nombre de la unidad fiscal donde se inicia el caso

-   **fecha_inicio (date):** fecha en que se inicia el caso. Tiene el formato AAAA-MM-DD

-   **fecha_hecho (date):** fecha en que se produjo el hecho. Tiene el formato AAAA-MM-DD

-   **hora_hecho (string):** hora en que se produjo el hecho

-   **cantidad_autores_identificados (int):** cantidad numérica total de presuntos autores del hecho, tanto menores como adultos, que fueron denunciados y que han sido identificados

-   **cantidad_autores_no_identificados (int):** cantidad numérica total de presuntos autores del hecho, tanto menores como adultos, que fueron denunciados y que no han sido identificados

-   **cantidad_menores_involucrados_identificados (int):** cantidad numérica de presuntos autores del hecho, que son menores de edad (menores de 18 años)

### Tabla1.1 - DELITOS

- **Nombre del recurso:** nombre-provincia-mp-AAAAMMDD-tabla1-1-delitos-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso

-   **id_caso (string):** código que identifica el caso. Cada provincia usa su propio formato de identificación de caso

-   **id_unidad_mp (string):** nombre de la unidad fiscal donde se inicia el caso

-   **código_delito (string):** código del delito del caso

-   **tentativa (string):** indica si el delito se produjo en grado de tentativa correspondiente a ese denunciado y al acto procesal. Toma los valores SI/NO

### Tabla2 - DECISIONES

- **Nombre del recurso:** nombre-provincia-mp-AAAAMMDD-tabla2-decisiones-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso

-   **id_caso (string):** código que identifica el caso. Cada provincia usa su propio formato de identificación de caso

-   **id_unidad_mp (string):** nombre de la unidad fiscal donde se inicia el caso

-   **item_caso (string):** código que permite distinguir a las distintas personas denunciadas en un caso, las cuales sean objeto de una decisión. Las decisiones que afectan a los casos con autores no identificados, toma valor “0” (cero) como valor del campo

-   **código_delito (string):** código del delito del caso

-   **tentativa (string):** indica si el delito se produjo en grado de tentativa correspondiente a ese denunciado y al acto procesal. Toma los valores SI/NO

-   **flagrancia (string):** indica si el caso sigue el proceso de flagrancia, en relación al acto procesal. Aplica para todas las provincias que tengan reglamentado dicho proceso. Toma los valores SI/NO

-   **código_delito (string):** código del delito del caso

-   **fecha_decision (date):** fecha de la decisión del caso


### Tabla2.1 - PERSONAS

- **Nombre del recurso:** nombre-provincia-mp-AAAAMMDD-tabla2-1-personas-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

### Campos del recurso

-   **id_caso (string):** código que identifica el caso. Cada provincia usa su propio formato de identificación de caso

-   **id_unidad_mp (string):** nombre de la unidad fiscal donde se inicia el caso

-   **item_caso (string):** código que permite distinguir a las distintas personas denunciadas en un caso, las cuales sean objeto de una decisión. Las decisiones que afectan a los casos con autores no identificados, toma valor “0” (cero) como valor del campo

-   **persona_genero (string):** género del denunciado correspondiente al acto procesal. Toma los valores "M" para masculino y "F" para femenino

-   **persona_edad (string):** edad del denunciado correspondiente al acto procesal. Si el denunciado es mayor de 65 años toma el valor 65+

### Índice de datos recibidos de los ministerios públicos provinciales - AAAA

-   **Nombre:** indice-archivos-remitidos-ministerios-publicos-AAAA.csv

-   **Descripción del contenido:** índice de los archivos recibidos de los ministerios públicos en el año AAAA en el marco del Convenio Interjurisdiccional de Datos Abiertos de Justicia.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** archivos recibidos de los ministerios públicos en el año AAAA

### Campos del recurso

-   **provincia_id (string):** código de provincia del Ministerio Público que remitió datos para su publicación, según la codificación implementada por INDEC

-   **provincia_nombre (string):** nombre de provincia del Ministerio Público que remitió datos para su publicación

-   **institucion_nombre (string):** nombre de la institución que remitió datos para su publicación

-   **envio_fecha (string):** fecha en la que el ministerio público provincial realizó el envío de datos.la fecha de envío no está directamente relacionada con las fechas de casos informadas. Los períodos informados pueden ser mensuales o abarcar períodos más largos. Tiene el formato AAAA-MM-DD

-   **envio_tabla (string):** nombre de la tabla que fue enviada por el ministerio público provincial. Toma los valores:

	-   tabla1

	-   tabla1.1

   	-   tabla1.2	

	-   tabla2

	-   tabla2.1

-   **publicacion_nombre_csv (string):** nombre del archivo publicado en formato csv. Este corresponde al nombre de provincia, institución, fecha de envío, nombre de las tablas remitidas según el Protocolo de Implementación del Convenio Interjurisdiccional de Datos Abiertos de Justicia (tabla1, tabla1.1, tabla1.2, tabla2 y tabla2.1) y número de orden de la tabla dentro del envío

-   **publicacion_nombre_zip (string):** nombre del archivo publicado en formato zip. Este mantiene la siguiente estructura:mp-datos-recibidos-AAAA

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública](http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Convenio Interjurisdiccional de Datos Abiertos de Justicia](https://github.com/datos-justicia-argentina/Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión I](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión III](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-III/blob/main/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Inertjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20III.pdf)

[Código Penal de la Nación Ley - 11.179](http://servicios.infoleg.gob.ar/infolegInternet/anexos/15000-19999/16546/texact.htm)

[Código Procesal Penal de La Nación Ley - 23.984](http://www.saij.gob.ar/23984-nacional-codigo-procesal-penal-lns0003709-1991-08-21/123456789-0abc-defg-g90-73000scanyel)

[Código Procesal Penal de la provincia de Buenos Aires Ley - 11.922](http://www.saij.gob.ar/11922-local-buenos-aires-codigo-procesal-penal-provincia-buenos-aires-lpb0011922-1996-12-18/123456789-0abc-defg-229-1100bvorpyel)

[Código Procesal Penal de la provincia de Catamarca Ley - 5.097](http://www.saij.gob.ar/legislacion/ley-catamarca-5097-codigo_procesal_penal_catamarca.htm)

[Código Procesal Penal de la provincia de Córdoba Ley - 8.123](http://www.saij.gob.ar/8123-local-cordoba-codigo-procesal-penal-provincia-cordoba-lpo0008123-1991-12-05/123456789-0abc-defg-321-8000ovorpyel)

[Código Procesal Penal de la provincia de Corrientes Ley - 2.945](http://www.saij.gob.ar/2945-local-corrientes-codigo-procesal-penal-para-provincia-corrientes-lpw0002945-1971-02-19/123456789-0abc-defg-549-2000wvorpyel)

[Código Procesal Penal de la provincia de chaco Ley - 1.062](http://www.saij.gob.ar/legislacion/ley-chaco-1062-codigo_procesal_penal_provincia.htm)

[Código Procesal Penal de la provincia de Chubut Ley - XV - N° 9 (Antes Ley 5.478)](http://www.saij.gob.ar/9-local-chubut-codigo-procesal-penal-chubut-lpu1000009-2010-05-06/123456789-0abc-defg-900-0001uvorpyel?&o=13&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo&t=104)

[Código Procesal Penal de la provincia de Entre Ríos Ley - 9.754]( http://www.saij.gob.ar/9754-local-entre-rios-codigo-procesal-penal-entre-rios-nuevo-regimen-lpe0009754-2006-12-20/123456789-0abc-defg-457-9000evorpyel)

[Código Procesal Penal de la provincia de Formosa Ley - 696](http://www.saij.gob.ar/696-local-formosa-codigo-procesal-penal-formosa-lpp0000696-1987-10-21/123456789-0abc-defg-696-0000pvorpyel?)

[Código Procesal Penal de la provincia de Jujuy Ley - 3.584](http://www.saij.gob.ar/3584-local-jujuy-codigo-procesal-penal-jujuy-lpy0003584-1978-11-20/123456789-0abc-defg-485-3000yvorpyel)

[Código Procesal Penal de la provincia de La Pampa Ley - 2.617](http://www.saij.gob.ar/2617-local-pampa-modificando-articulos-ley-n-2287-codigo-procesal-penal-provincia-pampa-lpl0002617-2011-05-05/123456789-0abc-defg-716-2000lvorpyel)

[Código Procesal Penal de la provincia de La Rioja Ley - 1.574](http://www.saij.gob.ar/1574-local-rioja-codigo-procesal-penal-rioja-lpf0001574-1950-09-29/123456789-0abc-defg-475-1000fvorpyel)

[Código Procesal Penal de la provincia de Mendoza Ley - 6.730](http://www.saij.gob.ar/6730-local-mendoza-codigo-procesal-penal-mendoza-lpm1006730-1999-11-16/123456789-0abc-defg-037-6001mvorpyel)

[Código Procesal Penal de la provincia de Misiones Ley - XIV Nro. 13](http://www.saij.gob.ar/13-local-misiones-codigo-procesal-penal-provincia-misiones-lpn0005365-2013-10-10/123456789-0abc-defg-563-5000nvorpyel)

[Código Procesal Penal de la provincia de Neuquén Ley - 2.784](http://www.saij.gob.ar/2784-local-neuquen-codigo-procedimiento-penal-correccional-lpq0002784-2011-11-24/123456789-0abc-defg-487-2000qvorpyel)

[Código Procesal Penal de la provincia de Río Negro Ley - 5.192](http://www.saij.gob.ar/5192-local-rio-negro-modifica-ley-n-5020-codigo-procesal-penal-lpr1005192-2017-04-07/123456789-0abc-defg-291-5001rvorpyel?&o=22&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n/Local/R%EDo%20Negro%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley&t=1657)

[Código Procesal Penal de la provincia de Salta Ley - 7.690](http://inecip.org/wp-content/uploads/C%C3%B3digo-Procesal-Penal-Salta.pdf)

[Código Procesal Penal de la provincia de San Juan Ley - 754 - O](http://www.saij.gob.ar/754-local-san-juan-codigo-procesal-penal-provincia-san-juan-lpj1500754-2014-11-19/123456789-0abc-defg-457-0051jvorpyel?)

[Código Procesal Penal de la provincia de San Luis Ley - VI Nro. 152](http://www.saij.gob.ar/legislacion/ley-san_luis-152-codigo_procesal_criminal_provincia.htm)

[Código Procesal Penal de la provincia de Santa Cruz Ley - 2.424](http://www.saij.gob.ar/2424-local-santa-cruz-codigo-procesal-penal-provincia-santa-cruz-lpz0002424-1995-11-16/123456789-0abc-defg-424-2000zvorpyel)

[Código Procesal Penal de la provincia de Santa Fe Ley - 12.734](http://www.saij.gob.ar/12734-local-santa-fe-codigo-procesal-penal-santa-fe-nuevo-regimen-lps0012734-2007-08-16/123456789-0abc-defg-437-2100svorpyel?)

[Código Procesal Penal de la provincia de Santiago del Estero Ley - 6.941](http://www.jussantiago.gov.ar/jusnueva/Normativa/Ley6941.php)

[Código Procesal Penal de la provincia de Tucumán Ley - 6.203](http://www.saij.gob.ar/6203-local-tucuman-codigo-procesal-penal-tucuman-lpt0006203-2010-03-23/123456789-0abc-defg-302-6000tvorpyel?&o=12&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo&t=104)

[Código Procesal Penal de la provincia de Tierra del Fuego Ley - 168](http://www.saij.gob.ar/168-local-tierra-fuego-codigo-procesal-penal-provincia-tierra-fuego-antartida-islas-atlantico-sur-lpv0000664-1994-08-19/123456789-0abc-defg-466-0000vvorpyel)

