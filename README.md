# INFORME LABORATORIO 6

## 1. OBJETIVOS

Comprobar experimentalmente el Teorema de la Máxima Transferencia de Potencia en un circuito resistivo mixto mediante simulaciones en la aplicacion ACDC LAB para comparar los resultados con los resultados analiticos el teorema.

### OBJETIVOS ESPECIFICOS

- Implementar el uso basico de la ley de ohm, tanto para intensidades como para potencia.

- Identificar las aplicaciones que tiene la reduccion de circuitos de Thevenin para el calculo de potencia. 

## 2. MARCO TEORICO 

TEOREMA DE LA MAXIMA TRANSFERENCIA DE POTENCIA

![](https://github.com/melaniegutierrez/INFORME-LABORATORIO-6/blob/main/WhatsApp%20Image%202023-01-12%20at%2010.02.42.jpeg)

## 3. EXPLICACION DEL PROCEDIMIENTO

**CIRCUITO DE LA PRACTICA**

![](https://github.com/melaniegutierrez/INFORME-LABORATORIO-6/blob/main/e1.png)

![](https://github.com/melaniegutierrez/INFORME-LABORATORIO-6/blob/main/e5.png)

![](https://github.com/melaniegutierrez/INFORME-LABORATORIO-6/blob/main/e6.png)

**CALCULO TEORICO DE LA POTENCIA**

![](https://github.com/melaniegutierrez/INFORME-LABORATORIO-6/blob/main/e2.png)

## 4. RESPUESTAS A INTERROGANTES

Tabla 6.1. Parámetros Eléctricos del circuito de la figura 6.1.

| **RL -------** |  **CORRIENTE MEDIDA (mA)** | **VOLTAJE MEDIDO (V)** | **POTENCIA CALCULADA TEORICAMENTE (w)** |**POTENCIA SIMULADA (w)** |    
| :----------: | :----------: | :----------: | :----------: | :----------: |
|  220 (Ω) | 4.23 (mA) | 0.930 (V) | 0.00393 (W) | 4 (mW) |
|  470 (Ω) | 3.59 (mA) | 1.69 (V)  | 0.00608 (W) | 7 (mW) |
|  680 (Ω) | 3.19 (mA) | 2.17 (V)  | 0.00692 (W) | 6 (mW) |
|  820 (Ω) | 2.97 (mA) | 2.44 (V)  | 0.00726 (W) | 7 (mW) |
| 1000 (Ω) | 2.73 (mA) | 2.73 (V)  | 0.00745 (W) | 8 (mW) |
| 1500 (Ω) | 2.22 (mA) | 3.33 (V)  | 0.00739 (W) | 8 (mW) |
| 1800 (Ω) | 2.00 (mA) | 3.60 (V)  | 0.00720 (W) | 7 (mW) |
| 2200 (Ω) | 1.76 (mA) | 3.88 (V)  | 0.00681 (W) | 4 (mW) |
| 3900 (Ω) | 1.18 (mA) | 4.59 (V)  | 0.00543 (W) | 4 (mW) |
| 4700 (Ω) | 1.02 (mA) | 4.79 (V)  | 0.00488 (W) | 5 (mW) |

6.5.4. ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta.

- Sí se cumple el teorema de la máxima transferencia de potencia, ya que, al momento que se calculó la potencia cuando la resistencia de la carga era igual a la resistencia interna de la red fuente vista desde los terminales de la carga, se logró comprobar que era la potencia máxima, sin embargo en la parte de la simulación no se logró apreciar bien con cual resistencia de carga se generaba la potencia máxima dado que medimos 8 mW en tres resistencias de carga diferentes.

6.5.5. ¿Cuál fue la potencia máxima en RL? 0.008 Watts

6.5.6. ¿Para qué valor de RL se obtiene la MTP? 1.2 kΩ

6.5.7. Grafique la curva Potencia vs RL y comente.

![](https://github.com/melaniegutierrez/INFORME-LABORATORIO-6/blob/main/e3.png)

Calcular errores de las mediciones y comentar los resultados.

![](https://github.com/melaniegutierrez/INFORME-LABORATORIO-6/blob/main/e4.png)

Debido a que tiene un porcentaje de error bastante grande se puede deducir que la simulacion de potencia muestra datos algo alejados de los calculados teoricamente

## 5. VIDEO

Link: https://youtu.be/3khIjEkkOUM

## 6. CONCLUSIONES

- A lo largo del presente informe se pudo comprobar el teorema de la máxima tranferencia de potencia, a través de cálculos matemáticos y las simulaciones realizadas en ACDCLAB donde se aprendió a usar el voltímetro para medir la potencia del circuito para cada resistencia RL planteada en el laboratorio.

- Se puede concluir, que el manejo de las fórmulas para calcular la potencia, cada una resulta importante, debido a que analíticamente si usamos una de las mismas, necesariamente debemos sacar las magnitudes que nos plantea, así consiguiendo directamente sus valores, que nos servirán para mas caculos analíticos, además que la importancia de la potencia en cada componente, nos indica como se disipa la energía, asegurando el funcionamiento correcto de cada uno.

## 7. BIBLIOGRAFIA 

- Teorema Máximo de Transferencia de Energía - Electronica Lugo. (2018, June 2). Electronica Lugo. https://electronicalugo.com/teorema-maximo-de-transferencia-de-energia/

‌

