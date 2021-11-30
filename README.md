# Informe de Laboratorio 3
### Fundamento de circuitos Eléctricos 
#### Ing. Darwin Omar Alulema Flores
#### Integrantes: Padilla Kevin, Samueza David, Avilés Kevin
 
 ## 1. OBJETIVOS
***Objetivo General***

- Comprobar experimental y analiticamente como encontrar los valores de corriente mediante el Análisis de Mallas.

***Objetivos Específicos***

- Comprender e identificar la utilidad de los instrumentos y equipos dentro del laboratorio.
- Comparar la diferencia que existe entre los valores medidos con los valores calculados, atraves del calculo de error.
- Comparar el metodo de mallas con el metodo de nodos, para saber cual escoger.
- Diferenciar correctamente lo que es una malla y una trayectoria.

 ## 2. MARCO TEÓRICO 
 
![Diagrama en blanco (8)](https://user-images.githubusercontent.com/94129932/143957610-2fe856aa-5935-48ad-983e-ef808e5ba044.png)

 
 ## 3. EXPLICACIÓN DEL PROCEDIMIENTO
 *Materiales*

1. Laboratorio vitual. (Tinkercad)
2. Simulador. (Proteus)
3. Calculadora Básica.
4. Suministro de energía
5. Protoboard
6. Resistencia
7. Multímetro
 
 *Procedimiento Experimental*
 
 [![Imagen1.png](https://i.postimg.cc/J44Jtmbw/Imagen1.png)](https://postimg.cc/dDpDSbHn)
 
 primero se ponen todos los componentes con su respectivas medidas las 5 resistencias, las dos fuentes de poder con el respectivo voltaje, el protoboard y el multimetro
 
 [![Imagen2.png](https://i.postimg.cc/HscY6hmc/Imagen2.png)](https://postimg.cc/2VYN6TVr)
 
 a continuacion se ponen las resistencias de manera respectiva a como nos pide el diagrama
 
 [![Imagen3.png](https://i.postimg.cc/L4q5WXB8/Imagen3.png)](https://postimg.cc/V58zrzVx)
 
 procedemos a conectar las fuentes de poder, al lado izquierdo la que cuenta con 12 volts y al lado derecho la de 8 volts

[![Imagen4.png](https://i.postimg.cc/JhnMB6pz/Imagen4.png)](https://postimg.cc/DStt9gV9)

por ultimo para revisar que se encuentre bien hecho el circuito probamos y ya esta listo para proceder con las medidas de voltaje en los nodos

 
 *Procedimiento del Simulador*
 *Procedimiento del cálculo*
 
  1. Tedremos que diferenciar entre nodos los nodos principales cual es nuestro nodo de referencia, una vez entendido eso, definimos por la LCK las ecuaciones bases. 
  
 ![image](https://user-images.githubusercontent.com/93794279/143958945-77e1ccaf-bb4b-49bb-874d-1d43d9479eb6.png)
 
  2. Ahora calculamos las ecuaciones para cada intensidad de las ecuaciones bases.
 
![image](https://user-images.githubusercontent.com/93794279/143965596-6a99ac1e-a17d-4daf-be01-ea3b3e46c6b3.png)

![image](https://user-images.githubusercontent.com/93794279/143959577-cfaaa6fc-476c-4cce-9742-f47d565c3ece.png)

 ![image](https://user-images.githubusercontent.com/93794279/143959520-c3c74f0e-213d-45d4-aa7e-90f01c1d8f03.png)

![image](https://user-images.githubusercontent.com/93794279/143959829-f8674882-50a8-41c9-8272-b73fe2ebb15f.png)

![image](https://user-images.githubusercontent.com/93794279/143967311-bea0d955-3934-45ce-bd77-58fb70b0097f.png)

![image](https://user-images.githubusercontent.com/93794279/143965463-d7600459-ab2a-4cf2-8d96-505a8f98432a.png)

 3. Reeemplar los valores obtenidos en los ateriores calculos.

![image](https://user-images.githubusercontent.com/93794279/143965225-2a1f53d1-f9a7-4462-a35f-7fec4d5bc51f.png)

 4. Resolvemos el sistema de ecuaciones mediante symbolab.
 
![image](https://user-images.githubusercontent.com/93794279/143965251-ff7d1a68-94a2-4193-87c2-135ae4d833d5.png)

 5. Reemplazamos lo valroes obtenido en las ecuaciones para encontrar cada incognita de corriente.
  
![image](https://user-images.githubusercontent.com/93794279/143967126-fabb6c9a-1d38-4467-ad71-4f5752d3c8c7.png)

  ## 4. RESPUESTA A INTERROGANTES Y CÀLCULO DEL ERROR
***Tabla 1***

![image](https://user-images.githubusercontent.com/94129932/143973131-572ae7f4-b1d7-4dbb-b9d7-910ff3b9d145.png)

***Tabla 2***
*Analítico*

![image](https://user-images.githubusercontent.com/93794279/143968136-d227ea3e-a761-4b45-830c-a43303f2a754.png)

***Tabla 3***
*Simulado*

![image](https://user-images.githubusercontent.com/94129932/143973030-0efb113d-fa46-4929-8bc6-b48ca452ea91.png)


## 5. VIDEO

https://youtu.be/-zopiJ3p-1s

## 6. CONCLUSIONES
- Concluimos que el análisis de mallas es un método que utiliza la Ley de Voltajes de Kirchhoff para obtener un conjunto de ecuaciones simultáneas que permitan determinar los valores de las corrientes que pasan por las ramas del circuito en estudio.
- Generalmente para elegir el mejor método suele ser el que tenga menos ecuaciones simultáneas. Si el número de nodos y de mallas son iguales o casi iguales, elige el método que entiendas mejor.
## 7. BIBLIOGRAFÍA
1. FLOYD, THOMAS L. (2007) Principios de circuitos eléctricos (8ª ed.). México:PEARSON EDUCACIÓN
2. (N.d.). Khanacademy.Org. Retrieved November 29, 2021, from https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-node-voltage-method
3. (N.d.-b). Edu.Co. Retrieved November 29, 2021, from http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_Analisis_por_Nodos_y_Mallas.pdf
## 8. ANEXOS
Anexo1: Simulación de intensidades en los nodos A y B
![image](https://user-images.githubusercontent.com/94129932/143972600-6f85c77b-9d64-42cc-ba17-f3ec808eb006.png)

Anexo2: Simulación de voltajes en los nodos A y B
![image](https://user-images.githubusercontent.com/94129932/143972854-59b08c11-de56-4804-bcd7-c09b0ff83048.png)


