![image](https://user-images.githubusercontent.com/84390820/125390304-46459000-e368-11eb-97a1-8142574b7df7.png)

# Informe  Tarea 

1. OBJETIVOS

General

* Analizar circuitos eléctricos complejos en una combinación de conexiones en serie y en paralelo, mediante métodos de análisis de corriente y voltaje de Kirchhoff, en la cual se puedan aclarar los conceptos del comportamiento de la corriente en esta clase de circuitos, para entender y las características de un circuito electrónico.

Específicos

* Estudiar la relación que existe entre las diferentes magnitudes dentro de un circuito eléctrico.
* Simplificar correctamente un circuito serie - paralelo para utilizar la Ley de Kirchhoff en el análisis de circuitos y ver el comportamiento de su funcionamiento.
* Interpretar la relación entre voltaje y corriente en un circuito con elementos pasivos, las convenciones de referencia, potencia, enegría y eficiencia.

2. MARCO TEÓRICO

CAPÍTULO VII

![image](https://user-images.githubusercontent.com/85137398/125575750-efc3bcf1-901a-4a9d-aa84-59e12c509ce7.png)

![image](https://user-images.githubusercontent.com/84390820/125562592-efad86d2-7652-442e-90eb-a4a0486c6510.png)

3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

EJERCICIOS CAPÍTULO VII


1.	Para las redes de la figura 7-46, determine cuales resistores y ramas están en serie y cuales en paralelo. Escriba una expresión para la resistencia total, RT.

![image](https://user-images.githubusercontent.com/85137398/125575803-c2469b8d-dd42-4e9d-a2e1-c69c252286c6.png)

a)	RT = R1+[(R2+R3)||R4]+R5

b)	RT = [(R1||R2)+(R3||R4)]

3.	Escriba una expresión para RT1 y RT2 para las redes de la figura 7-48

![image](https://user-images.githubusercontent.com/85137398/125575910-3a57a69c-bb6d-4d40-9494-07f24e2229d3.png)

a)	R1 + [R2||(R3+R4)]+R5

b)	R1+R2(R3||R5)+R4

5.	Las redes de resistores tienen las resistencias totales que se muestran a continuación.

Dibuje un circuito que corresponda a cada expresión.

a.	RT = (R1||R2||R3) + (R4||R5)

![image](https://user-images.githubusercontent.com/85137398/125575961-cb075f9a-74df-4243-a417-d2e70097cdf6.png)

b.	RT = (R1||R2) + R3 + [(R4+R5)||R6]

![image](https://user-images.githubusercontent.com/85137398/125576005-97ff8cd1-6a33-40e9-966a-b16e099f42b8.png)

7.	Determine la resistencia total para cada red de la figura 7-50.

![image](https://user-images.githubusercontent.com/85137398/125576029-d78383ef-0e26-4908-8af5-242ada2cb8cf.png)

a)	Transformamos la R2 a ohm

R2 = 4 Kohm -- 4000 ohm

Req (R2 Y R4) = 4000*300/4000+300 = 279.06 ohm

ReqT = R1 + R3 + Req (R2 Y R4) + R5 + R6

ReqT = 1679.06 ohm

b)	Operamos las resistencias en paralelo

Req (R3,R4,R5) = (1/5.1 + 1/4.7 + 1/5.6)^-1

Req (R3,R4,R5) = 1.70 Kohm

Ahora sacamos la ReqT

ReqT = R1 + R2 + Req (R3,R4,R5)

ReqT = 6.2 Kohm

11. Vea el circuito de la ﬁgura 7-54. Encuentre las siguientes cantidades:

a. RT
  
b. IT, I1, I2, I3, I4

c. Vab, Vbc.

![image](https://user-images.githubusercontent.com/85137398/125576263-6f9008d6-d0e3-43bc-8737-f6aafb5b21ca.png)

Resistencias en serie: 

R1=560+150=710 ohm

R2=390+910=1300 ohm

R_3=180+220=400 ohm

Resistencias en paralelo: 1/R4= 1/1300+1/400 → R4=305.88 ohm 

1/R5= 1/305.88+1/710  R5=213.78 ohm

a. RT = 213.78 + 100 = 313.78 ohm 

b. IT=20/314=63.7 mA

I1 = (305.88/305.88+710)*(63.7)= 19.2 mA

I2=63.7-19.2=44.5 mA

I3 = (1300/1300+400)*(44.5)= 34.1 mA

I4=44.5-34.1=10.4 mA

c. Vab=(34.1*10^(-3) )(400)=13.64 V.

Vbc=-(19.2*10^(-3) )(150)=-2.9 V.

13. Vea el circuito de la ﬁgura 7-56.

a. Encuentre las corrientes I1, I2, I3, I4, I5 e I6.

b. Encuentre los voltajes Vab y Vcd.

c. Veriﬁque que la potencia suministrada al circuito es igual a la suma de las potencias disipadas por los resistores.

![image](https://user-images.githubusercontent.com/85137398/125576780-1e0094fe-526a-41aa-b3f6-6e297b77982a.png)

a.    Resistencias en serie: 

Req1=6+3=9 kohm

Req3=1+3.6=4.6 kohm  

RT=1+2+2.4=5.4 kohm

Resistencias en paralelo:
Req2=  (9)(6)/(9+6)=3.6 kohm

R_eq4=((4.6)(5))/(4.6+5)=2.4 kohm

IT=V/RT =28/5400=5.2 mA=I1

I4=V_R2/_4 =12.48/5=2.5 mA

I2=I6=Veq3/Req3 =2.71 mA

I3=1.081 mA

I5=1.621 mA

b.  Vab=(2.4*10^(-3) )(5)=12.43 V

Vcd=(1.621*10^(-3) )(6)=9.73 V

c.   PT=(5200)^2 (5400)=145.3 mW

P1=(5200)^2 (1000)=26.9 mW

P2=(2710)^2 (1000)=7.34 mW

P3=(1081)^2 (3000)=3.506 mW

P4=(2500)^2 (5000)=30.9 mW

P5=(1621)^2 (6000)=15.77 mW

P6=(2710)^2 (2100)=7.0 mW

P7=(5200)^2 (2000)=53.9 mW

Pt=∑P=145.316 mW

15. Vea los circuitos de la ﬁgura 7-58:

a. Encuentre las corrientes indicadas.

b. Encuentre el voltaje Vab.

c. Veriﬁque que la potencia suministrada al circuito es igual a la suma de las potencias disipadas por los resistores.

![image](https://user-images.githubusercontent.com/85137398/125577482-43788ff6-a43b-476f-bf7d-b55197445157.png)


a.  I1=9/2=4.5 mA

I2=9/4=2.25 mA

I3=9/6=1.5 mA

b.  Vab=-9 V

c.  PT=(9)(0.018)=162 mW

P(6-kΩ)=(1500)^2 (6000)=13.5 mW

P(3-kΩ)=(1500)^2 (3000)=27.0 mW

P(2-kΩ)=(4500)^2 (2000)=40.5 mW

P(4-kΩ)=(2250)^2 (4000)=20.25 mW

b. 
I1=0.571 A

I2=0.365 A

I3=0.122 A

27. Vea el circuito de la figura 7-69: 

![image](https://user-images.githubusercontent.com/84390820/125565399-a6b35b08-0e3c-4528-a29a-5cb9c99c29ab.png)

a. Determine el intervalo de voltajes que aparecerán en RL a medida que el potenciómetro varíe entre sus valores mínimo y máximo.

Vbc=ReǁRL/(ReǁRL+R1)*E

= (5/(5+20))36 

RE = R1+R2=30kΩ

Vbc=7,2 v          Vbc=0=7,2 v

Si R2=2,5 Ω 

VL=((1,25 kΩ)/(1,25kΩ+20kΩ))36 = 2,117 v

b. Si R2 se ajusta para tener 2.5 kΩ ¿cuál será el voltaje VL? Si se remueve el
resistor de carga ¿qué voltaje aparecerá entre las terminales a y b?

Vab=(6,25kΩ/(6,25kΩ+20))36=8,57 ≈9v

29. Si el potenciómetro de la figura 7-70 se ajusta para que R2 = 200 Ω, determine los voltajes Vab y Vbc.

![image](https://user-images.githubusercontent.com/84390820/125565423-7088e605-cd68-44a3-bc58-d54290ce71b3.png)

Rp=(200*50)/(200+50)=40

Rp=(200*100)/(200+100)=66,7

Vbc=24(40/(100+40))=7,428≈7,43 v

VT = V1+V2

24 = V1+7,43

V1 = 24-7,43

V1 = 16,57 v

Vab = 16,57  

31. Vea el circuito de la figura 7-71:

a. Determine el intervalo del voltaje de salida (del mínimo al máximo) que se espera cuando el potenciómetro se ajusta del mínimo al máximo.

![image](https://user-images.githubusercontent.com/84390820/125567364-a06e81c4-c13f-4181-ae0e-a5455c2c8160.png)

El voltaje mínimo entre las terminales b y c es Vbc =0V, ya que las terminales están en corto.

El voltaje máximo: R1 y R2 están en paralelo con 10 k Ω. 

Vbc=((R1+R2)||10kΩ) )/((R1+R2)||10kΩ+10kΩ)*(120V)=(0.33)(120V)= 40 V

b. Calcule R2 cuando Vsal=20 V. 

Vsalida=((R2)||10kΩ) )/((R2)||10kΩ+10kΩ)*(120V)=20V

Sea R2=X

(10X/(10+X))/(10X/(10+X)+10) (120V)=20V

(10X/(10+X))/((20X+100)/(10+X))=0.16

X = 3.82 k Ω

35. Un voltímetro con una sensibilidad de S = 20 k Ω /V se usa en la escala de 10 V (con una resistencia interna total de 200 k Ω) para medir el voltaje en el resistor de 750 k Ω de la figura 7-74. El medidor indica un voltaje de 5.00 V. 

![image](https://user-images.githubusercontent.com/84390820/125569527-539fb4ab-c4e2-465d-89e7-68200da66199.png)

a. Determine el valor de la fuente de voltaje E. 

Vmultimetro=MUTÍMETROΩ/(MUTÍMETROΩ+CIRCUITOΩ)*(E)

5V=200kΩ/(200kΩ+200kΩ)*(E)

(5V(200kΩ+200kΩ))/200kΩ=(E)

E=11.33V

b. ¿Qué voltaje se presentará en el resistor de 750 k Ω cuando el voltímetro se quite del circuito? 

V=((750 kΩ)/(750 kΩ+200 kΩ))(11.33 V)=8.93 V

c. Calcule el efecto de carga del medidor cuando se utilice como se muestra. 

Se necesita calcular el voltaje con carga como sin carga. 

Voltaje sin carga: 

V=((750 kΩ)/(750 kΩ+200 kΩ))(11.33  V)=0.789* 11.33 V=8.93 V

Voltaje con carga: 

V=((750 kΩ||200 kΩ)/((750 kΩ||200 kΩ)+200 kΩ))(11.33 V)=0.441*11.33 V=4.99 V

Efecto de carga=  (8.93V-4.99 V)/(8.93 V)*100%=44.1%

d. Si se usa el mismo voltímetro para medir el voltaje en el resistor de 200 k Ω, ¿cuál será la lectura? 

Voltaje con carga: 

V=((200 kΩ||200 kΩ)/((200 kΩ||200 kΩ)+7500 kΩ))(11.33 V)=0.117*11.33 V = 1.33 V

37. Un amperímetro se usa para medir la corriente en el circuito que se muestra en la figura 7-76.

![image](https://user-images.githubusercontent.com/84390820/125569357-681141ba-d05c-4ff4-87ce-153f0f7a6ff8.png)

a. Explique cómo conectar de manera correcta el amperímetro para medir la corriente I1. 

Se abre el circuito entre el resistor de 5.6 Ω y la fuente de voltaje. Se conecta el amperímetro en serie y se conecta su terminal roja (+) a la terminal positiva de la fuente de voltaje y su terminal negra (-) al resistor de 5.6 Ω. 

b. Determine los valores indicados cuando el amperímetro se usa para medir cada una de las corrientes que se indican en el circuito. 

IT=24.7mA

I2=(24.7mA*3.9ohm)/(6.8+3.9)=9mA

I3=(24.7mA*6.8ohm)/(6.8+3.9)=15.6mA

IT=9+15.6=24.6 mA

IT=9+15.6+2=26.6 mA

I2=(24.7mA*3.9ohm)/(6.8+2)=7.4mA

I3=(24.7mA*6.8ohm)/(3.9+2)=12.2mA

I1=0.2/(5.6+5)=19.84mA

c. Calcule el efecto de carga en el medidor cuando se mide cada una de las corrientes. 

Efecto de carga I1=(26.6  -19.84)/(26.6 )*100%=19.67%

Efecto de carga I2=(9 -7.4)/9*100%=18 %

Efecto de carga I3=(15.6 -12.2)/15.6*100%=22.3%

4. VIDEO

5. CONCLUSIONES

6. BIBLIOGRAFIA



