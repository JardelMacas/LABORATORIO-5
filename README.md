# LABORATORIO-5

AUTORES: JERSON CHAMBA-JARDEL MACAS - ESTEFANY RAMOS

**1 . OBJETIVOS**

Objetivos Generales

* Conocer las ventajas presentes en el Teorema de Thevenin sobre cualquier circuito Resistivo.

Objetivos Especificos

* Analizar el proceso de conversion de un circuito complejo en un circuito equivalente de thevenin.

* Demostrar la eficiencia de la conversion de circuitos resistivos complejos en circuitos equivalentes de thevenin.

* Verificar la relacion existente entre el teorema de thevenin con otros metodos de solucion de redes resistivas.


**2.MARCO TEORICO**


![RESUMEN_LAB5](https://user-images.githubusercontent.com/84357979/126941925-1091538c-1d93-4af5-9faf-34bf6663c1b8.jpeg)


**3.EXPLICACIÓN DEL PROCEDIMIENTO**

1. Para comenzar con la practica correspondiente al laboratorio #5 es necesario tener conocimiento de cómo funciona el teorema de Thévenin como se muestra en el siguiente diagrama de un circuito.

![image](https://user-images.githubusercontent.com/84357979/126941966-364d3a8d-c721-49f7-a6cb-0ad449d5abc9.png)

2. Al haber realizado un previo análisis del circuito se observa que está dividido en tres mallas además consta de cinco resistencias (dos en serie y tres en paralelo), y dos fuentes de voltaje. 
3. Continuando con el desarrollo de la práctica se procede a la revisión del valor de cada componente presente en el circuito.

![image](https://user-images.githubusercontent.com/84357979/126941998-39b44fe6-1a01-458a-9869-36ad416e94c0.png)

4. Una vez realizado lo anteriormente mencionado procedemos a armar el circuito conforme se indica en la figura 5.1.
5. Procedemos a ubicar el valor de las fuentes de voltaje y de las resistencias conforme a lo planteado en el diagrama de la práctica, y procedemos a colocarlas en el protoboard de la siguiente manera: 

![image](https://user-images.githubusercontent.com/84357979/126942035-6a692f1b-5c7c-4e03-aa68-d01e3df2df7c.png)

6.	Ya concluido el armado del circuito se procede a iniciar la simulación y con la ayuda de un multímetro obtenemos tanto el voltaje y la corriente en la resistencia R5 como se muestra a continuación. 

![image](https://user-images.githubusercontent.com/84357979/126942051-90292a5f-886a-4efa-857c-067c8cbe8cda.png)

![image](https://user-images.githubusercontent.com/84357979/126942078-3fd6403b-583f-414f-b294-3745eb58058c.png)

7. Luego desconectamos la resistencia R5 y tomamos la respectiva medición del circuito abierto calculando el voltaje y la corriente presente en la resistencia R3. 

![image](https://user-images.githubusercontent.com/84357979/126942108-32ecc5cc-e99a-40c5-867e-fce7b7ff88a3.png)

![image](https://user-images.githubusercontent.com/84357979/126942118-e47ec866-08f2-4b1d-b0e2-a0734b6462e8.png)

8. Continuamos anulando la fuente de 12 V y desconectamos la resistencia R5 resultando asi un circuito abierto para luego proceder a calcular la resistencia equivalente del mismo. 

![image](https://user-images.githubusercontent.com/84357979/126942134-427a0b48-856b-4f6b-9ef1-13e47cc6132a.png)

![image](https://user-images.githubusercontent.com/84357979/126942138-f9eded59-3815-4883-bd1c-00cd8010aeba.png)

9. Para finalizar la práctica procedemos a implementar el circuito equivalente de Thévenin y calculamos tanto el voltaje como la corriente, y concluyendo con la práctica comparamos los resultados obtenidos en la simulación con los resultados del proceso matemático.

![image](https://user-images.githubusercontent.com/84357979/126942162-704e0280-158e-418f-a5a9-5c17c5ad87af.png)

![image](https://user-images.githubusercontent.com/84357979/126942173-78103d51-fb04-42b3-a1bb-59a53ebd04e7.png)

10.	Finalmente procedemos a medir el circuito analiticamente en el proceso matematico y a comparar resultados. 

**4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

Empezamos analizando el circuito propuesto, Determinando la carga que se va a retirar y el numero de fuentes presentes en el circuito complejo:

![image](https://user-images.githubusercontent.com/84357979/126942307-272ee931-14cb-4e34-aec8-a9a43c65db89.png)

Calculo de la Resistencia Equivalente de Thevenin:

![image](https://user-images.githubusercontent.com/84357979/126942342-b173a921-ef9f-4ce5-94f5-af68cc001a4f.png)

![image](https://user-images.githubusercontent.com/84357979/126942353-fc8e0f38-1baf-4c68-9906-6189e9f8371e.png)


![imagen3](https://user-images.githubusercontent.com/84357979/126942887-ff2927d6-6eb6-444f-99f3-267fa4ca9755.png)

Calculo del Voltaje entre terminales:
Para calcular el voltaje entre los Nodos A y B aplicamos el teorema de superposicion.

**Análisis Circuito A:**

![image](https://user-images.githubusercontent.com/84357979/126942593-2b6b3984-b5b1-4267-8965-ff20b07c05bb.png)

![image](https://user-images.githubusercontent.com/84357979/126942605-3bac8adf-035d-4e9b-b8d3-9a8e0c782a5b.png)

![image](https://user-images.githubusercontent.com/84357979/126942616-e293f1d9-b023-4220-ac84-a8995aae79d0.png)

![imagen4](https://user-images.githubusercontent.com/84357979/126943064-7c518e7a-e94e-4a4f-8774-8b4d0fd224f3.png)

**Análisis del Circuito B:**

![image](https://user-images.githubusercontent.com/84357979/126942635-5c9137ec-66d3-4ac8-a54a-491d5b50f172.png)

![image](https://user-images.githubusercontent.com/84357979/126942644-cf739371-e8f2-44a4-a97c-dbd58b12fe16.png)

![imagen5](https://user-images.githubusercontent.com/84357979/126943246-28e05e02-dc67-4e1a-bfe2-53589220baee.png)


Finalmente construimos el circuito equivalente de thevenin y calculamos la corriente y voltaje que pasa por la resistencia de interes:

![image](https://user-images.githubusercontent.com/84357979/126942689-e5673d26-5bef-4fca-b559-cf9a0816a369.png)

![imagen6](https://user-images.githubusercontent.com/84357979/126943323-f39f91e2-a0b0-4d9c-a208-3673986b9967.png)


Ahora procedemos a llenar la tabla de valores con los datos medidos y calculados.


![imagen7](https://user-images.githubusercontent.com/84357979/126943442-3c8f65e1-b9d2-473a-b38b-fd8a90ce4300.png)


**5.VIDEO**

Link del Video: https://youtu.be/choD_2AHwkE

[![Circuitos Eléctricos || Guía de Laboratorio 4|| Teorema de Superposición](https://img.youtube.com/vi/choD_2AHwkE/0.jpg)](https://youtu.be/choD_2AHwkE)

**5. CONCLUSIONES**

* Cualquier circuito resistivo complejo, puede reducirse a un circuito simplificado con una fuente de voltaje en serie con una resistencia equivalente.

* El teorema de Thevenin permite calcular directamente la corriente o voltahe sobre una carga determinada, incluso si este resistor es variable.

* La Aplicación del Teorema de Thevenin contiene aplicaciones de otros métodos de análisis de circuitos como el teorema de superposición o la reducción en serie-paralelo.

**6.BIBLIOGRAFÍA**

•  Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega, https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/

•  Robbins, A. H. (2008). Análisis de Circuitos Teoria y Practica. Santa Fe-Mexico: Cengage Learning.
