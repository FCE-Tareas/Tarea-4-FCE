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

![image](https://user-images.githubusercontent.com/84390820/125562592-efad86d2-7652-442e-90eb-a4a0486c6510.png)

3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

EJERCICIOS CAPÍTULO VII

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

