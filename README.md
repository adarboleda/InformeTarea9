# InformeTarea9

1. OBJETIVOS

Objetivo General

* Conocer sobre los circuitos RC y circuitos RL mediante la utilización del libro de Floyd "Principios de Circuitos Eléctricos"

Objetivo Específico

* Resumir los capitulos quince y dieciséis del libro de Floyd "Principios de Circuitos Eléctricos", para que de esta forma se pueda comprender de una mejor manera los temas descritos.
* Aplicar los conocimientos adquiridos de circuitos RC y circuitos RL para la resolcuión de los ejercicos propuestos por el libro de Floyd.

2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/93734334/154959484-fcec4abc-8bd5-4a1f-ab0a-a0244e728f29.png)

![image](https://user-images.githubusercontent.com/93734334/154961311-18908510-94e4-453c-bdda-b58e8fe9b412.png)

![image](https://user-images.githubusercontent.com/93734334/154970174-bd829358-1b1d-45cf-b21a-1783fffe2b8c.png)

![image](https://user-images.githubusercontent.com/93734334/154971999-ab87507e-671c-4a22-b0a8-04078a94a628.png)

3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

**PARTE 1: CIRCUITOS EN SERIE**
**SECCIÓN 17–1 Impedancia de circuitos RLC en serie**

1. Cierto circuito RLC en serie tiene los siguientes valores: R = 10ohm, C  = 0.047uF, y L = 5mH. Determine la impedancia en forma polar. ¿Cuál es la reactancia neta? La frecuencia de la fuente es de
5 kHz. 

R = 10 ohm                                                                                                                                                                       
C = 0.047 uF => 4.7x10^-8 F                                                                                                                                                       
L = 5 mH => 0.005 H                                                                                                                                                               
f = 5 kHz => 5000 Hz

Xc = 1/2πfC                                                                                                                                                                       
Xc = 1/2π(5000)(4.7x10^-8)                                                                                                                                                       
Xc = 677.255 ohm

XL = 2πfC                                                                                                                                                                         
XL = 2π(5000)(0.005)                                                                                                                                                             
XL = 157.08 ohm

Xtot = |157.08 - 677.255|                                                                                                                                                         
**Xtot = 520 ohm => Capacitiva**

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)                                                                                                                                               
Z = √(10)^2 + (250)^2 ∠ tan^-1 (250/10)                                                                                                                                           
**Z = 520 ∠ -88.90° ohm**

3. Si en la figura 17-59 la frecuencia del voltaje de fuente se duplica a partir del valor que producen las
reactancias indicadas, ¿cómo cambia la magnitud de la impedancia?

![image](https://user-images.githubusercontent.com/93734334/154956351-63361474-cdd6-4925-ba13-b64f7cf4d8dd.png)

Xtot = |80 - 35|                                                                                                                                                         
Xtot = 45 ohm => Inductivo

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)                                                                                                                                               
Z = √(47)^2 + (45)^2 ∠ tan^-1 (45/47)                                                                                                                                           
**Z = 65.07 ∠ 43.75° ohm**

**Respuesta**

La impedancia se incrementa a 150 ohm

**SECCIÓN 17–2 Análisis de circuitos RLC en serie**

5. Para el circuito de la figura 17-59, determine Itot, VR, VL y VC en forma polar.

![image](https://user-images.githubusercontent.com/93734334/154956449-49bcdd7a-574b-48b7-8c7e-0fa8d660669b.png)

Z = R + jXL - jXc
Z = 47 + j80 -j35
Z = 47 + j45 ohm

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)                                                                                                                                               
Z = √(47)^2 + (45)^2 ∠ tan^-1 (45/47)                                                                                                                                           
Z = 65.07 ∠ 43.75° ohm

Itot = Vs/Z                                                                                                                                                                       
Itot = (4 ∠ 0°)/(65.07 ∠ 43.75°)                                                                                                                                                 
**Itot = 61.4 ∠ -43.75° mA** 
  
VR = IR                                                                                                                                                                           
VR = (61.4 ∠ -43.75°)(47 ∠ 0°)                                                                                                                                                   
**VR = 2.89 ∠ -43.75° V**

VL = IXL                                                                                                                                                                         
VL = (61.4 ∠ -43.75°)(80 ∠ 90°)                                                                                                                                                 
**VL = 4.91 ∠ 46.25° V**

Vc = IXc                                                                                                                                                                         
Vc = (61.4 ∠ -43.75°)(35 ∠ -90°)                                                                                                                                                 
**VL = 2.15 ∠ -134° V**

7. Analice el circuito de la figura 17-60 para determinar lo siguiente (f = 25 kHz):

(a) Itot (b) Preal (c) Pr (d) Pa

![image](https://user-images.githubusercontent.com/93734334/154956627-5cf3c63d-d2de-4528-9444-4c9b7414bc12.png)

1/R = 1/220 + 1/390                                                                                                                                                               
RT = 140.656 ohm

LT = 0.5 + 1                                                                                                                                                                     
LT = 1.5 mH => 0.0015 H

CT = 10000 + 1800                                                                                                                                                                 
CT = 11800 pF => 1.18x10^-8 F

f = 25 kHz => 25000 Hz

Xc = 1/2πfC                                                                                                                                                                       
Xc = 1/2π(25000)(1.18x10^-8)                                                                                                                                                     
Xc = 539.51 ohm

XL = 2πfC                                                                                                                                                                         
XL = 2π(25000)(0.0015)                                                                                                                                                           
XL = 235.62 ohm

Xtot = |235.62 - 539.51|                                                                                                                                                         
**Xtot = 303.9 ohm => Capacitiva**

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)                                                                                                                                               
Z = √(140.656)^2 + (303.9)^2 ∠ tan^-1 (303.9/140.656)                                                                                                                             
Z = 334.87 ∠ -65.2° ohm

Itot = Vs/Z                                                                                                                                                                       
Itot = (12 ∠ 0°)/(334.87 ∠ -65.2°)                                                                                                                                               
**Itot = 35.8 ∠ 65.2° mA**

Preal = I^2R                                                                                                                                                                     
**Preal = 181 mW**

Pr = I^2 Xc                                                                                                                                                                       
**Pr = 390 mVAR**

Pa = I^2 Z                                                                                                                                                                       
**Pa = 430 mVA**

**SECCIÓN 17–3 Resonancia en serie**

9. Para el circuito de la figura 17-61, ¿cuál es el voltaje a través de R en condición de resonancia?

![image](https://user-images.githubusercontent.com/93734334/154956742-05c8b381-d6a8-4733-a32c-f0ed2b5d89f3.png)

I = Vs/R                                                                                                                                                                         
I = 12/22                                                                                                                                                                         
I = 0.54 A

VR = IR                                                                                                                                                                           
VR = (0.5454)(22)                                                                                                                                                                 
**VR = 12 V**

11. Cierto circuito resonante dispuesto en serie tiene una corriente mínima de 50 mA y un VL de 100 V. El
voltaje aplicado es de 10 V. ¿Cuál es el valor de Z? ¿Cuáles los valores de XL y XC?

I = 0.05 A                                                                                                                                                                       
VL = 100 V                                                                                                                                                                       
Vs = 10 V

VL = IXL                                                                                                                                                                         
10 = 0.05(XL)                                                                                                                                                                     
XL = 100/0.05                                                                                                                                                                     
**XL = Xc = 2000 ohm**

I = Vs/Z                                                                                                                                                                         
0.05 = 10/Z                                                                                                                                                                       
**Z = 200 ohm**

13. Para la figura 17-62, ¿cuál es el valor de la corriente en los puntos de potencia media?

![image](https://user-images.githubusercontent.com/93734334/154956884-451e3d6e-0247-4230-b59b-59da8c6aacc6.png)

I = Vs/R                                                                                                                                                                         
I = 7.07/10                                                                                                                                                                       
**I = 707 mA**

15. Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con
un conmutador:

(a) 500 kHz (b) 1000 kHz (c) 1500 kHz (d) 2000 kHz

**Respuesta**

![image](https://user-images.githubusercontent.com/93734334/155039764-635af66d-c0d0-469c-93f0-c987de212c09.png)

**PARTE 2: CIRCUITOS EN PARALELO**
**SECCIÓN 17–4 Impedancia de circuitos RLC en paralelo**

17. ¿Es capacitivo o inductivo el circuito de la figura 17-63? Explique su respuesta. 

![image](https://user-images.githubusercontent.com/93734334/154957077-33b7d827-73be-43d9-b9e2-9ee2b7c4e3f9.png)

L = 15 mH => 0.015 H                                                                                                                                                             
C = 0.022 uF => 2.2x10^-8                                                                                                                                                         
f = 12000 Hz

Xc = 1/2πfC                                                                                                                                                                       
Xc = 1/2π(12000)(2.2x10^-8)                                                                                                                                                       
Xc = 602.86 ohm

XL = 2πfC                                                                                                                                                                         
XL = 2π(12000)(0.015)                                                                                                                                                             
XL = 1130.97 ohm

G = 1/(R ∠ 0°)
G = 1/(5 ∠ 0°)
G = 200 ∠ 0° uS

Bc = 1/(Xc ∠ -90°)
Bc = 1/(602.86 ∠ -90°)
Bc = 1.66 ∠ 90° uS

BL = 1/(XL ∠ 90°)
BL = 1/(1130.97 ∠ 90°)
BL = 0.884 ∠ -90° uS

Ytot = G + jBc - jBL
Ytot = 200 + j1.66 - j0.884
Ytot = 200 uS - j0.776

Ytot = √G^2 + Btot^2 ∠ tan^-1 (Btot/G)                                                                                                                                           
Ytot = √(200)^2 + (0.776)^2 ∠ tan^-1 (0.776/200)                                                                                                                             
Ytot = 200 ∠ -4.43° uS

**El ángulo de fase de -4.43° indica un circuito levemente capacitivo.**

**SECCIÓN 17–5 Análisis de circuitos RLC en paralelo**

19. Para el circuito de la figura 17-63, determine todas las corrientes y los voltajes en forma polar

![image](https://user-images.githubusercontent.com/93734334/155046957-09e55068-2d56-465a-b899-13b070fcfc6b.png)

L = 15 mH => 0.015 H                                                                                                                                                             
C = 0.022 uF => 2.2x10^-8                                                                                                                                                         
f = 12000 Hz

Xc = 1/2πfC                                                                                                                                                                       
Xc = 1/2π(12000)(2.2x10^-8)                                                                                                                                                       
Xc = 602.86 ohm

XL = 2πfC                                                                                                                                                                         
XL = 2π(12000)(0.015)                                                                                                                                                             
XL = 1130.97 ohm

**VR = VL = Vc = 5 ∠ 0°**

IR = Vs/R                                                                                                                                                                         
IR = (5 ∠ 0°)/(100 ∠ 0°)                                                                                                                                                         
**IR = 50 ∠ 0° mA**

Ic = Vs/Xc                                                                                                                                                                       
Ic = (5 ∠ 0°)/(602.86 ∠ -90°)                                                                                                                                                   
**Ic = 8.29 ∠ 90° mA**

IL = Vs/XL                                                                                                                                                                       
IL = (5 ∠ 0°)/(1130.97 ∠ 90°)                                                                                                                                                   
**IL = 4.42 ∠ 90° mA**

Itot = IR + Ic + IL                                                                                                                                                               
Itot = 50 + j8.29 - j4.42                                                                                                                                                         
Itot = 50 mA + j3.87 mA     

Itot = √IR^2 + (Ic - IL)^2 ∠ tan^-1 (IcL/IR)                                                                                                                                     
Itot = √50^2 + (3.87)^2 ∠ tan^-1 (3.87/50)                                                                                                                                       
**Itot = 50.15 ∠ 4.43° mA**

21. Cambie la frecuencia a 100 kHz en la figura 17-63 y repita el problema 19. 

![image](https://user-images.githubusercontent.com/93734334/154957206-12a701c5-6931-4156-b2b1-69b1aae1ee45.png)

L = 15 mH => 0.015 H                                                                                                                                                             
C = 0.022 uF => 2.2x10^-8                                                                                                                                                         
f = 1000000 Hz

Xc = 1/2πfC                                                                                                                                                                       
Xc = 1/2π(100000)(2.2x10^-8)                                                                                                                                                     
Xc = 72.34 ohm

XL = 2πfC                                                                                                                                                                         
XL = 2π(100000)(0.015)                                                                                                                                                           
XL = 9424.78 ohm

VR = VL = Vc = 5 ∠ 0°

IR = Vs/R                                                                                                                                                                         
IR = (5 ∠ 0°)/(100 ∠ 0°)                                                                                                                                                         
**IR = 50 ∠ 0° mA**

Ic = Vs/Xc                                                                                                                                                                       
Ic = (5 ∠ 0°)/(72.34 ∠ -90°)                                                                                                                                                   
**Ic = 69.11 ∠ 90° mA**

IL = Vs/XL                                                                                                                                                                       
IL = (5 ∠ 0°)/(9424.78 ∠ 90°)                                                                                                                                                   
**IL = 0.53 ∠ 90° mA**

Itot = IR + Ic + IL                                                                                                                                                               
Itot = 50 + j69.11 - j0.53                                                                                                                                                       
Itot = 50 mA + j68.58 mA     

Itot = √IR^2 + (Ic - IL)^2 ∠ tan^-1 (IcL/IR)                                                                                                                                     
Itot = √50^2 + (68.58)^2 ∠ tan^-1 (68.58/50)                                                                                                                                     
**Itot = 84.9 ∠ 53.9° mA**

**SECCIÓN 17–6 Resonancia en paralelo**

23. Determine Z en condición de resonancia y fr para el circuito tanque de la figura 17-64.

![image](https://user-images.githubusercontent.com/93734334/154957296-d8fb57c9-6e96-42e3-9d54-d4cbe437b74f.png)

R = 20 ohm                                                                                                                                                                       
L = 50 mH => 0.05 H                                                                                                                                                               
C = 47 pF => 4.7x10^-11

fr = (√1 - Rw^2C/L)/2π√LC                                                                                                                                                         
fr = (√1 - (20)^2(4.7x10-11)/(0.05))/2π√(4.7x10-11)(0.05)                                                                                                                         
fr = 103821.21 Hz                                                                                                                                                                 
**fr = 104 kHz**                                                                                                                                                                 
**Z = 53.5 Mohm**

4. VIDEO

5. CONCLUSIONES

6. BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view

RUBRICA

![](https://github.com/doalulema/InformeTarea/blob/main/Tarea.png)
