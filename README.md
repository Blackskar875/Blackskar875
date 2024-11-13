Pequeña bandera de EE.UU.
Un sitio web oficial del gobierno de EE. UU.
Aquí te explicamos cómo saberlo

Logotipo de Datos Fiscales

Menú
Hogar/
Búsqueda de conjunto de datos/
Transacciones electrónicas de valores
Transacciones electrónicas de valores
Introducción
Vista previa y descarga
Propiedades del conjunto de datos
Guía rápida de API
Introducción
31/01/2000 — 31/10/2024Publicado mensualmenteÚltima actualización 16/10/2024
El conjunto de datos de Transacciones Electrónicas de Valores detalla cuántos bonos del Tesoro de cada tipo se emitieron, se canjearon o se encuentran en circulación desde el año fiscal 2002 hasta el presente. Los bonos en circulación se refieren a aquellos que aún están en circulación y aún no se han canjeado. La cantidad de bonos del Tesoro en circulación se determina tomando la diferencia entre la cantidad de bonos del Tesoro emitidos y canjeados. Este conjunto de datos no contiene ninguna información sobre los valores o los rendimientos de los bonos del Tesoro.
Vista previa y descarga
Seleccione la tabla de datos:
Tabla de datos

Ventas
Rango de fechas (Fecha de registro) :
Octubre de 20241 año5 años10 añosTodoCostumbre
Tabla de datos:
Ventas
Rango de fechas:
01/11/2019 - 31/10/2024
CSVJSONXML
Descargar archivo CSV
Descargar Diccionario de Datos ( 22 KB )
Ventas
Ocultar opciones de pivote
Vista pivote:

Tabla completa
Valor pivote:

- N / A -
Seleccionar columnas

Restablecer filtros
Fecha de registro
mm/dd/aaaa
-
mm/dd/aaaa
Descripción del tipo de seguridad

Descripción de la clase de seguridad

Recuento de valores vendidos

Monto de ventas brutas

Importe de venta devuelto

Monto de ventas netas

Mes de las Transacciones

Número de línea de origen

Año fiscal

Número del trimestre fiscal

Año calendario

Número de trimestre del calendario

Número de mes del calendario

Número de día del calendario

31/10/2024	Bono de ahorro	EE	5,568	$1,386,778.47	$63,855.18	$1,322,923.29	202410	1	2025	1	2024	4	10	31
31/10/2024	Bono de ahorro	I	24.430	$19,193,895.16	$297,893.73	$18,896,001.43	202410	2	2025	1	2024	4	10	31
31/10/2024	Vendible	
44.179	$3,289,296,300.00	$0.00	$3,289,296,300.00	202410	3	2025	1	2024	4	10	31
Mostrando 1 - 3 filas de 3 filas
Filas por página
Propiedades del conjunto de datos

Restablecer filtros
Data Table Name

Field Name

Display Name

Description

Data Type

Is Required

Ventas	fecha de registro	Fecha de registro	La fecha en que se publicaron los datos.	FECHA	1
Ventas	descripción del tipo de seguridad	Descripción del tipo de seguridad	Nivel uno de una jerarquía de dos niveles para categorizar los valores del Tesoro. Indica si un valor es negociable o un bono de ahorro.	CADENA	1
Ventas	descripción de clase de seguridad	Descripción de la clase de seguridad	Segundo nivel de una jerarquía de dos niveles para categorizar los valores del Tesoro. Indica si un valor negociable es una letra, un pagaré, un bono o un título del Tesoro protegido contra la inflación (TIPS), o si un bono de ahorro es de la serie E, EE o I.	CADENA	1
Ventas	valores_vendidos_cnt	Recuento de valores vendidos	La cantidad de valores vendidos en TreasuryDirect durante un mes determinado.	NÚMERO	1
Ventas	Importe bruto de ventas	Monto de ventas brutas	Valor bruto en dólares de los valores vendidos en TreasuryDirect durante un mes determinado.	DIVISA	1
Mostrando 1 - 5 filas de 103 filas
Filas por página

123421

Guía rápida de API
Consulte nuestra documentación API más detallada.
Documentación API
Mostrar más
Puntos finales
URL BASE:
https://api.fiscaldata.treasury.gov/services/api/fiscal_service/
Nombre de la tabla	Punto final
Ventas	/v1/contabilidad/od/ventas_de_valores
Ventas por término	/v1/contabilidad/od/términos_de_venta_de_valores
Transferencias de valores negociables	/v1/contabilidad/od/transferencias_de_valores
Conversiones de Bonos de Ahorro en Papel	/v1/contabilidad/od/conversiones_de_valores
Redenciones	/v1/contabilidad/od/redenciones_de_valores
Pendiente	/v1/contabilidad/od/valores_en_pendiente
Certificados de deuda	/v1/contabilidad/od/valores_c_of_i
Cuentas	/v1/contabilidad/od/cuentas_de_valores
Mostrando 1 - 8 filas de 8 filas
Filas por página
URL COMPLETA:
https://api.fiscaldata.treasury.gov/services/api/fiscal_service/v1/accounting/od/securities_sales
Campos
Consulte Propiedades del conjunto de datos más arriba para obtener un diccionario de datos con nombres de campos y descripciones, así como notas y limitaciones conocidas. limitaciones conocidas.
Nombre del campo	Nombre para mostrar	Tipo de datos	Nombre de la tabla de datos
fecha de registro	Fecha de registro	FECHA	Ventas
descripción del tipo de seguridad	Descripción del tipo de seguridad	CADENA	Ventas
descripción de clase de seguridad	Descripción de la clase de seguridad	CADENA	Ventas
valores_vendidos_cnt	Recuento de valores vendidos	NÚMERO	Ventas
Importe bruto de ventas	Monto de ventas brutas	DIVISA	Ventas
Mostrando 1 - 5 filas de 103 filas
Filas por página

123421

Tipos de datos
Todos los datos se devuelven como una cadena , incluidos los valores nulos. Consulta el cuadro anterior para conocer el tipo de datos previsto para cada campo.
Conjuntos de datos relacionados
Logotipo de Datos Fiscales
Ayuda
Preguntas frecuentes
Contáctenos
Sobre nosotros
Acerca de los datos fiscales
Calendario de lanzamientos
Suscríbete a nuestra lista de correo
Nuestros sitios
Gastos en EE.UU.
© 2024 Transparencia de datos
Accesibilidadpolítica de privacidadLey de Libertad de Información
Navegado a Transacciones Electrónicas de Valores
-2.5%
Blackskar875/Blackskar875 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
