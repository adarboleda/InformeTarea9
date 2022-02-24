# InformeTarea9

1. OBJETIVOS

Objetivo General

* Conocer sobre los circuitos RCL y resonancia y filtros pasivos mediante la utilización del libro de Floyd "Principios de Circuitos Eléctricos"

Objetivo Específico

* Resumir los capitulos diecisiete y dieciocho del libro de Floyd "Principios de Circuitos Eléctricos", para que de esta forma se pueda comprender de una mejor manera los temas descritos.
* Aplicar los conocimientos adquiridos de circuitos RCL y resonancia y filtros pasivos para la resolcuión de los ejercicos propuestos por el libro de Floyd.

2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/93734334/154959484-fcec4abc-8bd5-4a1f-ab0a-a0244e728f29.png)

![image](https://user-images.githubusercontent.com/93734334/154961311-18908510-94e4-453c-bdda-b58e8fe9b412.png)

![image](https://user-images.githubusercontent.com/93734334/154970174-bd829358-1b1d-45cf-b21a-1783fffe2b8c.png)

![image](https://user-images.githubusercontent.com/93734334/154971999-ab87507e-671c-4a22-b0a8-04078a94a628.png)


![image](https://user-images.githubusercontent.com/93733175/155553500-bb36c47a-66c6-4db2-b9c8-87aaef5b2809.png)

![image](https://user-images.githubusercontent.com/93733175/155553593-70115c4d-ec4c-4bff-8416-743cb2307555.png)

![image](https://user-images.githubusercontent.com/93733175/155553648-73e23e3a-dae4-4dab-8c40-b7a3a285501a.png)

![image](https://user-images.githubusercontent.com/93733175/155553718-26e0513b-432c-4a52-85a2-46636abd8404.png)


![imagen](https://user-images.githubusercontent.com/93879569/155470932-e27cd063-f0b8-4351-bba8-84b87f477579.png)

![imagen](https://user-images.githubusercontent.com/93879569/155470999-412b6acf-c64f-40ce-b96b-dc40009f5f4c.png)

![imagen](https://user-images.githubusercontent.com/93879569/155471042-c5407c53-00f1-4d64-b239-d031393f0a27.png)

![imagen](https://user-images.githubusercontent.com/93879569/155471083-f13d703c-6e1f-4354-a8b0-35b806ecfec8.png)


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

SECCIÓN 17–6 Resonancia en paralelo

25. Determine Preal, Pr y Pa en el circuito de la figura 17-64 en condición de resonancia.

![image](https://user-images.githubusercontent.com/93733175/155553889-7e7b3f14-738e-45e4-8ea6-bec67b37128c.png)

![image](https://user-images.githubusercontent.com/93733175/155553912-965d83d4-887c-4226-a763-f075e02326f0.png)

PARTE 3: CIRCUITOS EN SERIE-PARALELO 

SECCIÓN 17–7 ANÁLISIS DE CIRCUITOS RLC EN SERIE-PARALELO

27. Para cada circuito de la figura 17-65, determine el ángulo de fase entre el voltaje de fuente y la corriente total.

29. Convierta el circuito de la figura 17-66 a una forma equivalente dispuesta en serie.

![image](https://user-images.githubusercontent.com/93733175/155554007-f757b169-ba51-4256-9ca9-853bad70aae4.png)

31. En la figura 17-67, ¿cuál es el ángulo de fase entre I2 y el voltaje de fuente?

![image](https://user-images.githubusercontent.com/93733175/155554047-ac582517-8d9d-47c4-bd3c-19ee55e6b853.png)

33. Determine la corriente a través de cada componente mostrado en la figura 17-68. Encuentre el voltaje entre las terminales de cada componente.

![image](https://user-images.githubusercontent.com/93733175/155554087-900bd2ce-a040-40f4-9f90-df2fc393cf86.png)

35. Si el valor de C es de 0.22 µF, ¿cuál es la corriente a través de un resistor de 100 Ω conectado de a a b en la figura 17-69?

![image](https://user-images.githubusercontent.com/93733175/155573088-ef26cb37-0bab-40d7-98a1-ca018211d795.png)

Calcular la impedancia del conductor e inductor:

![image](https://user-images.githubusercontent.com/93733175/155573198-506eb612-1333-4f02-8ba6-b9f92e69c428.png)

Calcular la resistencia total:

![image](https://user-images.githubusercontent.com/93733175/155573254-3adf7fb4-72bd-4cf7-8a11-42b030a2a529.png)

Calcular la corriente total:

![image](https://user-images.githubusercontent.com/93733175/155573441-f5173034-ad0e-4c8e-9a08-d0bc1d9d93c0.png)

Calculo de la corriente por la resistencia de 100Ω

![image](https://user-images.githubusercontent.com/93733175/155573626-14491429-d047-4ba4-b209-e1d021d5637f.png)

37. Determine las frecuencias resonantes y el voltaje de salida en cada frecuencia mostrada en la figura 17-70.

![image](https://user-images.githubusercontent.com/93733175/155555033-8b18033e-0f1c-4b6a-8f2c-7f8e40d31843.png)

Frecuencia en serie

![image](https://user-images.githubusercontent.com/93733175/155555135-619a2cec-61be-438a-a5c3-506c454c3f40.png)

Frecuencia en paralelo

![image](https://user-images.githubusercontent.com/93733175/155555254-a3a7d6b0-dd21-4582-8e3d-59e84c79c97c.png)

**PARTE 4: TEMAS ESPECIALES**

**SECCIÓN 17–8 Ancho de banda de circuitos resonantes**

39. En condición de resonancia, XL = 2 kΩ y RW 25Ω en un circuito RLC en paralelo. La frecuencia resonante es de 5 kHz. Determine el ancho de banda.

Para la resolución del problema se tiene las siguientes formulas:

El factor Q:

![image](https://user-images.githubusercontent.com/93733175/155555425-dc9d644a-1cbd-4393-8dc7-c7e6441ef300.png)

Un valor alto de Q produce un ancho de banda más angosto. Un valor bajo de Q produce un ancho de banda más amplio. En la siguiente ecuación se establece una fórmula para el ancho de banda de un circuito resonante en función de Q:

![image](https://user-images.githubusercontent.com/93733175/155555478-df6e1ec6-f434-41de-abf8-65ae0b04ef76.png)

41. En cierto circuito RLC, la potencia en condición de resonancia es de 2.75 W. ¿Cuál es la potencia a la frecuencia crítica baja?

En condición de resonancia:

![image](https://user-images.githubusercontent.com/93733175/155555564-c0be7a86-3970-435d-8fad-c67ee8dad210.png)

![image](https://user-images.githubusercontent.com/93733175/155555594-33c6dd53-b0e4-408d-b122-10d3e5171d47.png)

De forma tal que la potencia a la frecuencia crítica baja es:

![image](https://user-images.githubusercontent.com/93733175/155555645-62cd74d2-c25b-4b79-a772-8c898478a37b.png)

43. Cierto circuito resonante en paralelo tiene un factor Q de 50 y un AB de 400 Hz. Si Q se duplica, ¿cuál es el ancho de banda a la misma fr?

En la siguiente ecuación se establece una fórmula para el ancho de banda de un circuito resonante en función de Q:

![image](https://user-images.githubusercontent.com/93733175/155555725-a45ff9d5-9135-43e0-bb77-42c12b8442b2.png)

Para ello se calcula primeramente frecuencia de resonancia:

![image](https://user-images.githubusercontent.com/93733175/155555782-c7ae7f72-2489-44ba-92cd-f18483e0df80.png)

Ahora según el enunciado nos dice que el factor Q se ha duplicado entonces de 50 pasa a 100 y se determina con este valor el ancho de banda de fr:

![image](https://user-images.githubusercontent.com/93733175/155555859-a937f65f-50fa-40b9-8c82-e505ab8f7ebf.png)

SECCIÓN 18–1 Filtros pasabajas

1. En cierto filtro pasabajas, XC = 500 Ω y R = 2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando la entrada es de 10 V rms?

Al aplicar la fórmula del divisor de voltaje, la magnitud del voltaje de salida es:

![image](https://user-images.githubusercontent.com/93733175/155555942-31607279-2548-4895-82a9-dadd312b9c4c.png)

3. Determine el voltaje de salida (Vsal) de cada filtro mostrado en la figura 18-38 a la frecuencia especificada cuando Vent = 10 V

![image](https://user-images.githubusercontent.com/93733175/155556045-8599e54e-5ecf-434a-a8c4-2d9e4a85c17b.png)

![image](https://user-images.githubusercontent.com/93733175/155556149-fedb0b2e-fb56-4c55-9ed2-0d7e279e4dc3.png)

![image](https://user-images.githubusercontent.com/93733175/155556193-1077741d-efa6-4aaf-9af1-634cd8684da8.png)

![image](https://user-images.githubusercontent.com/93733175/155556236-e2669cad-db20-4654-8fa9-ea5c1d1beac4.png)

5. Para el filtro de la figura 18-39, calcule el valor de C requerido para cada una de las siguientes frecuencias críticas:

![imagen](https://user-images.githubusercontent.com/93879569/155531522-2117eb7e-f099-4741-bcd8-2a47deb817b3.png)


fc=1/2πRC

fc*2π*R=1/C

C=  1/(fc*2π*R)

Reemplazando valores

(a) 60 Hz 

C=  1/(60Hz*2π*220Ω)

**C= 0.000012057 F=12.1 μF**

(b) 500 Hz 
	
C=  1/(500Hz*2π*220Ω)

**C= 0.000001447 F=1.45 μF**

(c) 1 kHz 

C=  1/(1000 Hz*2π*220Ω)

**C= 0.000000723 F=0.72 μF**
	
(d) 5 kHz

C=  1/(5000 Hz*2π*220Ω)

**C= 0.000000145 F=0.145 μF**

7. Trace una curva de Bode para cada una de las partes del problema 5.

![imagen](https://user-images.githubusercontent.com/93879569/155531711-179a59b0-3510-4704-a846-f70764d1f582.png)

![imagen](https://user-images.githubusercontent.com/93879569/155531741-44ded8bc-b1e6-46ac-be55-586834e877ac.png)

![imagen](https://user-images.githubusercontent.com/93879569/155531760-18904daa-5982-4288-b53d-a8adaf2627dd.png)

![imagen](https://user-images.githubusercontent.com/93879569/155531800-edd1521c-2268-4786-a283-304a7fa1d5ef.png)

9. El voltaje de entrada a un filtro RC pasabajas es de 8 V rms. Determine el voltaje de salida a los siguientes niveles de dB:

20*log⁡(Vsalida/Ventrada)=dB

log⁡(Vsalida/(8 Vrms))=dB/20

Vsalida/(8 Vrms)=e^(dB/20)

Vsalida=8 Vrms* e^(dB/20)

Reemplazando valores

(a) -1 dB

Vsalida=8 Vrms* e^((-1)/20)

**Vsalida=7.61 V**

(b) -3 dB

Vsalida=8 Vrms* e^((-3)/20)

**Vsalida=6.89 V**

(c) -6 dB

Vsalida=8 Vrms* e^((-6)/20)

**Vsalida=5.92 V**

(d) -20 dB

Vsalida=8 Vrms* e^((-20)/20)

**Vsalida=2.94 V**

**SECCIÓN 18–2 Filtros pasaaltas**

11. En un filtro pasaaltas, XC =500 Ω y R =2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando Vent =
10 V rms?

Vsalida=(R/√(R^2+〖Xc〗^2 ))*Ventrada

Vsalida=(2200/√(2200^2+500^2 ))*10

Vsalida=9.75 Vrms

Desplazamiento de fase 

φ=〖tan〗^(-1) (Xc/R)

φ=〖tan〗^(-1) (500/2200)

φ=12.80°

El voltaje 

**Vsalida=9.75∠12.8° V**

13. Determine el voltaje de salida de cada filtro mostrado en la figura 18-41 a la frecuencia especificada cuando Vent = 10 V.

![imagen](https://user-images.githubusercontent.com/93879569/155532118-694a6814-5a19-4c31-8a82-72b87fd56e5b.png)

Reactancia capacitiva

Xc=1/(2π*f*C)

Xc=1/(2π*60Hz*10μF)=265 Ω

Vsalida=(R/√(R^2+〖Xc〗^2 ))*Ventrada

Vsalida=(100/√(100^2+265^2 ))*10

Vsalida=3.53 Vrms

Desplazamiento de fase 

φ=〖tan〗^(-1) (Xc/R)

φ=〖tan〗^(-1) (265/100)

φ=69.33°

El voltaje 

**Vsalida=3.53∠69.33° V**

![imagen](https://user-images.githubusercontent.com/93879569/155532261-33761fb1-b3c6-4b53-b1ca-4da989338111.png)

Reactancia capacitiva

Xc=1/(2π*f*C)

Xc=1/(2π*400Hz*4.7μF)=84.6 Ω

Vsalida=(R/√(R^2+〖Xc〗^2 ))*Ventrada

Vsalida=(47/√(47^2+〖84.6〗^2 ))*10

Vsalida=4.85 Vrms

Desplazamiento de fase 

φ=〖tan〗^(-1) (Xc/R)

φ=〖tan〗^(-1) (84.6/47)

φ=60.95°

El voltaje 

**Vsalida=4.85∠60.95° V**

![imagen](https://user-images.githubusercontent.com/93879569/155532375-86e177c0-37a2-426a-868f-57c27422e568.png)

Rw=2*π*f*L

Rw=2*π*1000 Hz*,005 H=31.42

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(330/(330+31.42))*10

Vsalida=9.47mVrms

Desplazamiento de fase 

φ=〖tan〗^(-1) (Rw/R)

φ=〖tan〗^(-1) (3142/330)

φ=84°

El voltaje 

**Vsalida=9.4∠84° mV**

![imagen](https://user-images.githubusercontent.com/93879569/155532546-ae2815d6-e336-41af-8790-942860924949.png)

Rw=2*π*f*L

Rw=2*π*2000 Hz*0.08 H=1005.3 

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(10/(10+1005.3))*10

Vsalida=995 mVrms

Desplazamiento de fase 

φ=〖tan〗^(-1) (Rw/R)

φ=〖tan〗^(-1) (1005.3/10)

φ=84.3°

El voltaje 

**Vsalida=995∠84.3° mV**

15. Trace la curva de Bode para cada filtro mostrado en la figura 18-41.

(a)

![imagen](https://user-images.githubusercontent.com/93879569/155532711-8a722ddb-ad93-4844-a2f9-6a9bef682961.png)

(b)

![imagen](https://user-images.githubusercontent.com/93879569/155532757-6cc35fca-125e-4d45-940f-78725084d153.png)

(c)

![imagen](https://user-images.githubusercontent.com/93879569/155532787-f068ee08-9663-4ec9-a47d-6ee239022989.png)

(d)

![imagen](https://user-images.githubusercontent.com/93879569/155532835-a856705d-2017-47ba-845c-c34cf84eb730.png)

SECCIÓN 18–3 Filtros pasabanda

17. Determine la frecuencia central para cada filtro de la figura 18-43.

![imagen](https://user-images.githubusercontent.com/93879569/155532918-55e0c851-fcec-4f6c-82a7-f96672998dad.png)

fo=√(1-(〖Rw〗^2*C/L))/(2π√(L*C))

fo=√(1-(0^2*0.01μF/12mH))/(2π√(12mH*0.01μF))

**fo=14.5 kHz**

![imagen](https://user-images.githubusercontent.com/93879569/155533039-2e9bda74-e4ba-4175-a808-c1b748a4eaa4.png)

fo=√(1-(〖Rw〗^2*C/L))/(2π√(L*C))

fo=√(1-(0^2*0.022μF/2mH))/(2π√(2mH*0.022μF))

**fo=24.0 kHz**

19. ¿Cuáles son las frecuencias críticas alta y baja para cada filtro de la figura 18-43? Suponga que la respuesta es simétrica con respecto a f0.

![imagen](https://user-images.githubusercontent.com/93879569/155533188-1f293072-f287-41df-9f28-2ed50085e232.png)

fc=1/(2π*L/R)

fc=1/(2π*1H/680Ω)

**fc=15.06 kHz**

fc=1/(2π*R*C)

fc=1/(2π*680Ω*10μF)

**fc=13.94 kHz**

![imagen](https://user-images.githubusercontent.com/93879569/155533334-1923ae30-7aa3-43c2-a578-1735c918b431.png)

fc=1/(2π*L/R)

fc=1/(2π*(2.5 μH)/(1 kΩ))

**fc=25.3  kHz**

fc=1/(2π*R*C)

fc=1/(2π*1 kΩ*25pF)

**fc=22.7 kHz**

21. Si la resistencia de devanado de las bobinas que aparecen en la figura 18-44 es de 4 Ω, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent = 120 V?

![imagen](https://user-images.githubusercontent.com/93879569/155533482-b25e671f-bda1-498b-9efc-efa47b9f4afd.png)

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(680/(680+4))*120V

**Vsalida=119.29V**

![imagen](https://user-images.githubusercontent.com/93879569/155533600-28e90d57-a572-473f-8f61-ea104f98e172.png)

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(1000/(1000+4))*120V

**Vsalida=119.52V**

*23. Diseñe un filtro pasabanda utilizando un circuito resonante paralelo que satisfaga las siguientes especificaciones: AB = 500 Hz; Q = 40; e IC(máx) =20 mA, VC(máx) =2.5 V.
Entonces 

el valor de la capaitancia es 0.064 uF 

La inductancia debe ser de 989 uH

la frecuencia  f= 20 kHz

25. Para cada filtro de la figura 18-47, determine la frecuencia central de la banda de rechazo

![imagen](https://user-images.githubusercontent.com/93879569/155533708-f33b9640-0fa4-4424-b67f-7e7b9b2b74c0.png)

F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-1000^26.8/0,5)/2piSqrt(0.56,8)

**F0=318Hz**

![imagen](https://user-images.githubusercontent.com/93879569/155533736-2de717dd-75df-40ef-9609-9799bf930876.png)

F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-2200^247/10)/2piSqrt(1047)

**F0=10,21Hz**

*27. Determine los valores de L1 y L2 en la figura 18-48 para dejar pasar una señal con frecuencia de 1200 kHz y rechazar una señal con frecuencia de 456 kHz.

![imagen](https://user-images.githubusercontent.com/93879569/155533848-d2e007a6-ea7b-4e3d-a8bd-88bb6f3b96d7.png)

fo=√(1-(〖Rw〗^2*C/L))/(2π√(L*C))

Si Rw = 0 ohmios

fo=1/(2π√(L*C))

2π*fo=1/√(L*C)

√(2π*fo)=1/(L*C)

L=C/√(2π*fo )

Reemplazando datos

Fo = 1200 kHz 

L=(0.22 μF)/√(2π*1200 kHz )

**L=0.0025  μH**


Fo = 456 kHz 

L=(0.22 μF)/√(2π*456 kHz )

**L=0.004  μH**


4. VIDEO

https://youtu.be/LAPIIRt6Ho8

5. CONCLUSIONES

* Como conclusión, un circuito RLC en serie está formado por una resistencia, un inductor y un condensador. Las reactancias inductiva y capacitiva tienen efectos opuestos en el ángulo de fase del circuito, de modo que la reactancia global es menor que las reactancias individuales, pero como la resonancia es una situación en la que las reactancias capacitiva e inductiva son iguales, se anulan mutuamente, dando lugar a una impedancia puramente resistiva.
* Tambien, en un circuito en serie RLC, las tensiones entre los terminales del condensador y los terminales del inductor están siempre separadas 180°. Por lo tanto, VC y VL se restan entre sí, de modo que la suma de las tensiones en L y C es siempre menor que la tensión máxima individual entre los terminales de cualquiera de los componentes.
* Los filtros de pasaaltas permite que fluya señales de alta frecuencia y los filtros de pasabajas permite quefluya las señales de baja frecuencia.
* Los filtros de pasabanda permite que pasen las señales que se encuentran en un determinado intervalo de frecuencia si una frecuencia se pasa del intervalo es eliminada y los filtros de rechazabanda es lo opuesto a los filtros de pasabanda debido a que determina el intervalo de frecuencia donde las frecuencias son rechazadas.

6. BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view

RUBRICA

![](https://github.com/doalulema/InformeTarea/blob/main/Tarea.png)
