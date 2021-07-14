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

CAPÍTULO VIII

![image](https://user-images.githubusercontent.com/84390686/125584689-8459f090-f57a-4679-9c66-b329996158b3.png)

![image](https://user-images.githubusercontent.com/84390686/125584773-cb921d16-ad96-4aad-ab95-a40527624b8a.png)

![image](https://user-images.githubusercontent.com/84390686/125584799-ce8e25bc-65df-4234-8dc7-ca8ec046f5a5.png)

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



EJERCICIOS CAPÍTULO VIII

1.  Encuentre el voltaje VS para el circuito de la figura 8-64.

 ![image](https://user-images.githubusercontent.com/85209614/125578483-58760299-43e8-4fcc-be92-154796e4af86.png)

(Vs - 20)/6 = 3

Vs – 20 = 18

Vs = 38V

3. Vea el circuito de la figura 8-66: 

a. Encuentre la corriente I3. 

b. Determine los voltajes VS y V1.

![image](https://user-images.githubusercontent.com/85209614/125578555-9ecbf016-a8ac-4c7a-b259-45d7a7614bd3.png)

Is = 20mA     =>     I3 = 20 * (300) / (300 + 200)      =>      I3 = 12mA

V1 = Is * R1 = 0.02A * 100   =>    V1 = 2V

-Vs +V1 +V3 = 0     =>     -Vs + 2 + 0.012 * 200 = 0     =>     Vs = 4.4V

5. Para el circuito de la figura 8-68 encuentre las corrientes I1 e I2.

![image](https://user-images.githubusercontent.com/85209614/125578849-479ebb12-dc3b-4197-9000-4ac6aff7545c.png)

I3 = 15 / 50     =>    I3 = 300uA   ;    I4 = 15 / 150     =>     I4 = 100uA

I1 = 100uA + 300uA    =>    I1 = 400uA

I2 = 100uA + 100uA + 300uA    =>    I2 = 500uA

7. Verifique que la potencia suministrada por las fuentes es igual a la suma de las potencias disipadas por los resistores en el circuito de la figura 8-68.

![image](https://user-images.githubusercontent.com/85209614/125578949-39b8cff9-64ae-4539-b4d9-86f199ca97fc.png)

I1 = 400uA  ;   I2 = 500uA  ;  I3 = 300uA  ;  I4 = 100uA

P1 = 15 * 500uA + 15 * (-100uA) = 6mW

P2 = 100uA^2 * 150k + 300uA^2 *50K = 6mW

9. Convierta cada fuente de voltaje de la figura 8-70 en su fuente de corriente equivalente.

![image](https://user-images.githubusercontent.com/85209614/125579063-8c70e311-0940-4c4e-b547-3e5e142bd16b.png)

I = 5 / 20   =>   I = 0.25A

I = 25 / 2k    =>     I = 12.5mA

11. Vea el circuito de la figura 8-72: 

a. Encuentre la corriente a través del resistor de carga con la regla del divisor de corriente. 

b. Convierta la fuente de corriente en su fuente de voltaje equivalente y determine, otra vez, la corriente a través de la carga.

![image](https://user-images.githubusercontent.com/85209614/125579161-91e81b65-a47f-4547-a6e7-804f5b888d77.png)

I1 = 8A * 450 / 450 + 50    =>   I1 = 7.2A

V = 8A * 450     =>     V = 3600V

I1 = 3600V / 500ohm      =>     I1 = 7.2A

13. Vea el circuito de la figura 8-74: 

a. Convierta la fuente de corriente y el resistor de 330 Ω en su fuente de voltaje equivalente. 

b. Encuentre la corriente I a través de RL. 

c. Determine el voltaje Vab.

![image](https://user-images.githubusercontent.com/85209614/125579259-e91be7e1-89b0-44db-a4b7-0daaec809c80.png)

a)	V = 65mA * 330ohm = 21.45V

b)	-21.45V + 330I + 470I + 16V + 100I = 0     =>    I = 5.45 / 900 = 6.06mA

c)	Vab = 6.06mA * 100ohm = 0.606V

15. Encuentre el voltaje V2 y la corriente I1 para el circuito de la figura 8-76.

![image](https://user-images.githubusercontent.com/85209614/125579344-fd6c65aa-0638-4fec-9d98-c52e46e318f6.png)

IT = I2 – I1 = 100mA – 50mA = -50mA

Req = 1 / (1 / 3kΩ) + (1 / 6kΩ) + (1 / 8kΩ) = 1.6kΩ

VT = -5mA * 1.6KΩ = -80V

VT = VR1 = VR2 = VR3 = -80V

I1 = (1.6kΩ / 3kΩ) * -50mA = -26.7mA

17. Para el circuito de la figura 8-78 convierta la fuente de corriente y el resistor de 2.4 k  en una fuente de voltaje y calcule el voltaje Vab y la corriente I3.

![image](https://user-images.githubusercontent.com/85209614/125579424-0ee47782-c053-489a-8a59-c615fa2a0c1f.png)

V2 = 3mA * 2.4kΩ = 7.2V

Veq = V – V2 = 8V – 7.2V = 0.8V

Req = 1.6kΩ + 2.4kΩ + 2kΩ = 6kΩ

VR2 = (2.4kΩ / 6kΩ) * 0.8V = 0.32V

Vab = V2 + VR2 = 7.2V + 0.32V = 7.52V

Por sentido del circuito: Vab = -7.52V

IT = I3 = 0.8V / 6kΩ = 0.133mA

19. Escriba las ecuaciones de corriente de rama para el circuito de la figura 8-79 y encuentre las corrientes de rama mediante determinantes.

![image](https://user-images.githubusercontent.com/85209614/125579521-c613b238-0fd3-4609-b8f4-991c786f6fb9.png)

Lazo 1 :  15V – (30Ω)I1 + (6Ω)I2 = 0V
                
                  30Ω I1 - 6Ω I2 = 15V (1)

Lazo 2 :  5V – (20Ω) I3 – (6Ω) I2 = 0V
               
                   -6Ω I2 - 20Ω I3 = -5V (2)

I3 = I1 + I2 (3)

D = 900

I1 = 420 / 900 = 0.467A 

I2 = -150 / 900 = -0.167A 

I3 = 270 / 900 = 0.3A 

21. Escriba las ecuaciones de corriente de rama para el circuito de la figura 8-81 y encuentre la corriente I2.

![image](https://user-images.githubusercontent.com/85209614/125579628-e6739a86-6eab-4b29-adcf-606730d4e334.png)

Lazo 1:  20.5V – (8.2) I2 – (6.2 Ω) I2 + (5 Ω) I1 - 10V = 0V
                  
                      14.4 Ω I2 - 5 Ω I1 = 10.5V    (1)

Lazo 2:  10V – (4.7 Ω) I3 – (5 Ω) I2 = 0V

                     -5 Ω I1 – 4.7 Ω I3 = -10V   (2)
     
                           I3 = I1 + I2   (3)

D = 163.18

I2 = 151.85 / 163.18 = 0.931A 

Por el sentido de la corriente: I2 = -0.931A 

23. Vea el circuito de la figura 8-83: 

a. Escriba las ecuaciones de corriente de rama. 

b. Encuentre la corriente I2. 

c. Determine el voltaje Vab.

![image](https://user-images.githubusercontent.com/85209614/125579788-4b866d5f-1fd7-4030-ad9b-b88c87d0d939.png)

a)

-24 Ω + 2I1 + 6I1 – 10I3 = 0                          4I2 + 10I3 – 16V = 0

8I1 – 10I3 = 24                                       4I2 + 10I3 = 16

                                  I1 – I2 + I3 = 0 

b)

8I1 + 0I2 – 10I3 = 24

0I1 + 4I2 + 10I3 = 26

I1 – I2 + I3 = 0
                                      I1 = 62 / 19 = 3.26 A

                                      I2 = 66 / 19 = 3.473 A

                                      I3 = 4 / 19 = 0.21 A

c)

Vab = -(4) (3.47) = -13.89v

25. Escriba las ecuaciones de malla para el circuito que se muestra en la figura 8-79 y encuentre las corrientes de lazo.

![image](https://user-images.githubusercontent.com/85209614/125580516-1cebda1d-4aea-4149-b698-4eaa3c0f2626.png)

-15v + 30I1 + 6(I2 – I2) = 0                             6(I2 – I1) – 5v + 20I2 = 0

30I1 + 6I1 – 6I2 = 15                                    6I2 – 6I1 + 20I2 = 5

36I1 – 6I2 = 15                                          -6I1 + 26I2 = 5

                                     36I1 – 6I2 = 15 
                                               
                                     -6I1 + 26I2 = 5

                     I1 = 7 / 5 = 0.467 A        ;         I2 = 0.3 A

27. Utilice el análisis de malla para encontrar la corriente I2 en el circuito de la figura 8-81.

![image](https://user-images.githubusercontent.com/85209614/125580907-35e41932-6cdb-4ca0-8b37-031546535692.png)

-20.5v + 8.2I2 + 6.2I2 + 5(I2 – I3) + 10 = 0               -10v + 5(I3 – I2) + 4.7I3 = 0

14.4I2 + 5I2 -5I3 = 10.5                                    5I3 - 5I2 +4.7I3 = 10

19.4I2 – 5I3 = 10.5                                        -5I2 + 9.7I3 = 10 

                                  19.4I2 – 5I3 = 10.5

                                  -5I2 + 9.7I3 = 10

I2 = -II15185 / 16318II ≈ -0.931 A

I3 = II12325 / 8159II ≈ 1.511 A

29. Utilice el análisis de malla para encontrar las corrientes de lazo en el circuito de la figura 8-84. Use sus resultados para determinar I y Vab.
 
 ![image](https://user-images.githubusercontent.com/84390686/125584986-100aa59c-5614-4706-9b63-01d49e2fbc29.png)

Lazo 1: -2v+(40+80)I1-80I2-8V=0

Lazo 2: 12V+(60+80)I2-80I1+8V=0

Reformulamos

Lazo 1: 120I1-80I2=10V

Lazo 2: -80I1 +140I2=-20V

Despejar I1

I1= -0,01923 A

I1=-19,23 mA

I2=-0,13185

I3=I1+I2

I3=-0,15108

Calcular Vab

Vab=60*I3+12

Vab=-9,6+12

Vab=2.93V

31. Escriba las ecuaciones de malla para la red de la figura 8-86. Encuentre las corrientes de lazo con determinantes.
 
![image](https://user-images.githubusercontent.com/84390686/125585091-3883b379-9723-424f-ae49-3a5090fc358b.png)

Lazo 1: (3+1+6)I1-1I2-6I3+4V+2V=0

Lazo 2: (3+4+1)I2-1I1-3I3-6V-4V=0

Lazo 3: (3+6)I3-6I1-3I2-5V=0

Reformulamos

Lazo 1: 10I1-1I2-6I3=-6V

Lazo 2: 8I2-1I1-3I3=10V

Lazo 3: 9I3-6I1-3I2=5V

Despejar I1,I2,I3 utilizando sistema de ecuaciones:

I1= 0,495 A

I2=1,879 A

I3=1,512 A

33. Convierta cada una de las redes de la figura 8-92 en su configuración Y equivalente.

![image](https://user-images.githubusercontent.com/84390686/125585149-12badcec-ed80-4a4c-a80e-f5ce732c8be6.png)

Los siguientes valores de resistores son:

Ra= 270 Ω

Rb= 90 Ω

Rc= 30 Ω

Al aplicar las ecuaciones se tiene los siguientes valores de resistores equivalentes en “Y”.

R1=(30)(90)/30+90+270

R1=2700/390

R1=6,92 Ω

R2=(30)(270)/30+90+270

R2=8100/390

R2=20,77 Ω

R3=(90)(270)/30+90+270

R3=24300/390


R3=62,31 Ω

35. Convierta cada una de las redes de la figura 8-93 en su configuración Y equivalente.

![image](https://user-images.githubusercontent.com/84390686/125585248-af05e880-4ed8-4981-bab5-aba39bd4c488.png)

Los siguientes valores de resistores son:

Ra= 7,8 KΩ

Rb= 5,6 KΩ

Rc= 4,7 KΩ

Al aplicar las ecuaciones se tiene los siguientes valores de resistores equivalentes en “Y”.

R1=(5,6)(4,7)/7,8+5,6+4,7

R1=26,32/18,1

R1=1,45 KΩ

R2=(7,8)(4,7)/7,8+5,6+4,7

R2=36,66/18,1

R2=2,02 KΩ

R3=(5,6)(7,8)/7,8+5,6+4,7

R3=43,68/18,1

R3=2,41 KΩ

37. Convierta cada una de las redes Y de la figura 8-94 en su configuracion 
equivalente.

![image](https://user-images.githubusercontent.com/84390686/125585317-4e6531a3-ea8c-40c7-9e5d-d5f08bde84af.png)

Los siguientes valores de resistores son:

R1= 10Ω

R2= 30Ω

R3= 20Ω

Al aplicar las ecuaciones se tiene los siguientes valores de resistores equivalentes en “Y”.

Ra=(10)(30)+(10)(20)+(30)(20)/10

Ra=1100/10

Ra=110 Ω

Rb=(10)(30)+(10)(20)+(30)(20)/30

Rb=1100/30

Rb=36,7 Ω

Rc=(10)(30)+(10)(20)+(30)(20)/20

Rc=1100/20

Rc=55 Ω

39. Convierta cada una de las redes Y de la figura 8-94 en su configuración equivalente.

![image](https://user-images.githubusercontent.com/84390686/125585382-a5f58af4-0138-4dc7-814d-ed6a4efea0a4.png)

Los siguientes valores de resistores son:

R1= 470KΩ

R2= 220KΩ

R3= 390KΩ

Al aplicar las ecuaciones se tiene los siguientes valores de resistores equivalentes en “Y”.

Ra=(470)(220)+(470)(390)+(220)(390)/470

Ra=372500/470

Ra=793 KΩ

Rb=(470)(220)+(470)(390)+(220)(390)/220

Rb=372500/220

Rb=1693 KΩ

Rc=(470)(220)+(470)(390)+(220)(390)/390

Rc=372500/390

Rc=955 KΩ

41. Convierta cada una de las redes Y de la figura 8-95 en su configuración equivalente.
 
![image](https://user-images.githubusercontent.com/84390686/125585436-2e0853bb-7f3c-40ab-a377-c0bb42029251.png)

Los siguientes valores de resistores son:

R1= 24Ω

R2= 48Ω

R3= 96Ω

Al aplicar las ecuaciones se tiene los siguientes valores de resistores equivalentes en “Y”.

Ra=(24)(48)+(24)(96)+(48)(96)/24

Ra=8064/24

Ra=336 Ω

Rb=(24)(48)+(24)(96)+(48)(96)/48

Rb=8064/48

Rb=168 Ω

Rc=(24)(48)+(24)(96)+(48)(96)/96

Rc=8064/96

Rc=84 Ω



4. VIDEO

- https://youtu.be/cGdELaqLFMY

5. CONCLUSIONES

- Los circuios eléctricos en aplicaciones reales de la electrónica se complementan con circuitos en serie y en paralelo entre sí, por lo que debemos utilizar la simplificación de circuitos para realizar los mismos análisis de forma mas simple.

- Las redes puente se usa en un equipo de medición electrónico esto para medir con precisión le resistencia en circuitos de cd y cantidades similares en circuitos de ca.

6. BIBLIOGRAFIA

- Wikipedia.(2018).Circuitos en serie y paraleo. from https://es.wikipedia.org/wiki/Circuitos_en_serie_y_en_paralelo


