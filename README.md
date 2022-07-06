# INFORME LABORATORIO 5

## OBJETIVOS

### OBJETIVO GENERAL

Resolver el circuito eléctrico por medio del análisis y aplicación del Teorema de Thévenin con la finalidad de obtener los valores solicitados.

### OBJETIVOS ESPECIFICOS

-	Elaborar el circuito eléctrico en base al esquema otorgado para correcta medición de valores.
-	Aplicar el Teorema de Thévenin en el circuito elaborado para encontrar los valores solicitados.

## MARCO TEÓRICO

El teorema de Thévenin, es lograr que un circuito complejo se convierta en uno más simple, es decir, al existir dos terminales A y B dentro de la estructura de un circuito lineal, es posible convertirlo a un circuito más simple, en donde a través de la resistencia del circuito transformado la corriente seguirá circulando. (Xnomid, 2019)

La forma Thévenin equivalente de cualquier circuito resistivo de dos terminales consta de una fuente de voltaje equivalente y una resistencia equivalente, como se aprecia en la siguiente imagen.

![image](https://user-images.githubusercontent.com/105565683/177606411-0f3d912a-9482-4c60-9e0d-2b904ee17624.png)

![image](https://user-images.githubusercontent.com/105565683/177606422-eea8e659-756d-4bf1-9900-118459865b6a.png)

![image](https://user-images.githubusercontent.com/105565683/177606490-4955748c-07a6-4759-9d1a-ec66804b80d2.png)

### Proceso

Los pasos para aplicar el Teorema de Thévenin son:

### Paso 1

Abrir las dos terminales (eliminar cualquier carga) entre las que se desea encontrar el circuito equivalente de Thévenin.

#### Paso 2

Determinar el voltaje (VTH) entre las dos terminales abiertas.

#### Paso 3

Determinar la resistencia (RTH) entre las dos terminales abiertas con todas las fuentes reemplazadas por sus resistencias internas (fuentes de voltaje ideales en cortocircuito y fuentes de corriente ideales abiertas).

#### Paso 4

Conectar Vth y Rth en serie para producir el equivalente de Thévenin completo del circuito original.

#### Paso 5

Reemplazar la carga eliminada en el paso 1 entre las terminales del circuito equivalente de Thévenin. Ahora se pueden calcular la corriente y el voltaje que haya en la carga utilizando solamente la ley de Ohm. Tienen el mismo valor que la corriente y el voltaje presentes en la carga del circuito original. (Thomas, 2007)

### Ventajas de aplicar el Teorema de Thévenin

Las ventajas de aplicar este teorema son:

-	Al crear un circuito equivalente simple de uno más complejo, se puede calcular en menor tiempo el valor de voltajes, resistencias, corriente o incluso la potencia de un circuito una vez conectado a una carga.
-	Se puede aplicar a cualquier elemento del circuito, siempre y cuando cuente con una fuente independiente.
-	Es posible encontrar un circuito equivalente simple hasta del circuito más complejo. (Xnomid, 2019)

## EXPLICACIÓN DEL PROCEDIMIENTO

### ELABORACIÓN DEL CIRCUITO

#### MATERIALES

![image](https://user-images.githubusercontent.com/105565683/177607985-667f85f8-2f89-489f-9fe5-ecd4b163aa43.png)

![image](https://user-images.githubusercontent.com/105565683/177608021-78e9639e-6dd5-4592-9f10-75fa158f2b91.png)

#### PROCESO

1. Ubicamos las resistencias como se muestra en el esquema del circuito.

![image](https://user-images.githubusercontent.com/105565683/177608348-551b0238-9be0-40c3-96ec-50efbb2abea1.png)

2. Conectar las resistencias por medio de los cables de acuerdo con el esquema, que cumpla con el circuito mixto.

![image](https://user-images.githubusercontent.com/105565683/177608476-b3a94026-56ab-4b2a-a1af-f74ad8e27be6.png)

3. Conectamos las fuentes de voltaje C.D. (en caso de simulador), de acuerdo al esquema, en los polos positivo y negativo de las resistencias.

![image](https://user-images.githubusercontent.com/105565683/177608672-618ea149-35d6-4be3-9e7d-f74dd5b24709.png)

#### CIRCUITO FISICO

Siguiendo el mismo proceso, armamos el circuito físico:

### TEOREMA DE THÉVENIN 

![image](https://user-images.githubusercontent.com/105565683/177608764-58f0b8db-be60-489a-a7ee-ce959832b5bd.png)

Para encontrar R_TH y V_TH, seguimos los siguientes pasos:

![image](https://user-images.githubusercontent.com/105565683/177608894-12b4b43a-364f-493e-9018-8f80f3ebae09.png)

![image](https://user-images.githubusercontent.com/105565683/177608958-fb20301c-4c8d-4252-8945-816ae117e266.png)

![image](https://user-images.githubusercontent.com/105565683/177609074-d84607cb-0073-4df5-83a3-9117f7b4b2a7.png)

![image](https://user-images.githubusercontent.com/105565683/177609118-33d6350d-ccad-4208-a47b-d6e010c8ba09.png)

![image](https://user-images.githubusercontent.com/105565683/177609159-91f01f16-70c3-47b3-9959-cfd51fbaa64c.png)

![image](https://user-images.githubusercontent.com/105565683/177609188-d9ab61fd-6755-4ed3-a997-432521940117.png)

## RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

### MEDICIONES DE VOLTAJE Y CORRIENTE

1. Medir el voltaje y corriente en R5 en el circuito original.

![image](https://user-images.githubusercontent.com/105565683/177609781-a8c07374-b2f8-49e0-a4c0-d1df328bb41c.png)

2. Medir el voltaje del circuito abierto con R5 desconectado.

![image](https://user-images.githubusercontent.com/105565683/177610052-c7c28ac5-a84e-4749-9059-327868e89d89.png)

3. Medir la corriente resultante con R5 desconectado y anulando el efecto de las fuentes.

![image](https://user-images.githubusercontent.com/105565683/177610445-ef7b76d2-9455-4593-b939-23c3c1bb1739.png)

4. Medir el voltaje y corriente en R5 en el circuito de Thévenin.

![image](https://user-images.githubusercontent.com/105565683/177610775-1c96c377-8f0f-449e-9fdb-2fd287782496.png)

5.Comparar los resultados obtenidos de voltaje, corriente y resistencia.

Para el circuito físico se utilizaron baterías y pilas para las fuentes de voltaje, siendo de 3 V y 9 V, por ende, existirá una ligera diferencia entre los resultados, también se tomarán en cuenta los resultados obtenidos en ambos circuitos del grupo.

Valores del Circuito Equivalente de Thévenin



### RESULTADOS

Los valores calculados y simulados, son casi exactamente iguales, respecto al margen de error, se reduce a milésimas, puesto que el simulador TINKERCAD, tiende a redondear los resultados a dos decimales, pero en un espectro general, los valores tanto calculados como medidos, son los mismos.

En cuanto a los resultados experimentales si existe un margen de diferencia considerable puesto que para los circuitos físicos se utilizo fuentes de voltaje muy distintas siendo de 9 V y 3 V, de forma que existe una diferencia, también hay que tener en cuenta que existe un margen de error entre ambos circuitos dependiendo de las resistencias y fuentes puesto que sus valores no son 100% iguales y por ende las medidas no son 100% iguales, existiendo una margen de diferencia.

## VIDEO


## CONCLUSIONES

-	Se utilizó un análisis y comprensión adecuado del esquema proporcionado para la correcta elaboración del circuito eléctrico en donde se respeta su polaridad y materiales para poder obtener correctamente los valores requeridos.
-	El Teorema de Thévenin es de gran utilidad para la resolución de circuitos complejos, convirtiendo un circuito complejo a uno más sencillo facilitando los cálculos y análisis del circuito.

## BIBLIOGRAFÍA

Thomas, F. (2007). Principios de Circuitos elétricos. Octava edición. México: Pearson Educación.

Xnomid. (7 de Noviembre de 2019). Teorema. Obtenido de https://www.teorema.top/teorema-de-thevenin/
