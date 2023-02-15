# Informe-Lab-8

## 3. Marco Teorico

![image](https://user-images.githubusercontent.com/116813974/219183576-eb7e55d3-2314-4102-b50d-586f62aded81.png)

## 4. Materiales y equipos requeridos

![image](https://user-images.githubusercontent.com/116761073/219076437-1f5beef5-38cd-4ba5-89b1-259028932692.png)

## 5. Procedimiento

8.5.1. Implemente el circuito que se presenta en la figura 7.1

![image](https://user-images.githubusercontent.com/116761073/219076613-60fdb76b-438c-446f-a9b6-036905a42d15.png)

8.5.2.. Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.

![image](https://user-images.githubusercontent.com/116761073/219076867-26e5fa1e-40fd-4580-91b8-473496b53c28.png)

8.5.3. Conecte el osciloscopio a la resistencia de carga RL. Observe la señal que aparece en el osciloscopio.

![image](https://user-images.githubusercontent.com/116761073/219076980-5d85c071-8fb0-42a6-8077-77fecadb6c13.png)

Respuestas a interrogantes

8.5.4. Responde las siguientes preguntas:

¿Cuantas divisiones por cuadro abarcan la amplitud pico de la señal de salida?

La amplitud pico abarca 2,3 cuadros aproximadamente.

¿En qué valor está posicionada la perilla VOLTS/DIV?

Esta posicionado en el valor de 3v

¿Cuantas divisiones por cuadro abarca un ciclo completo de la señal de salida?

Un ciclo completo abarca cuatro cuadros.

¿En qué valor está posicionada la perilla TIME/DIV?

Esta posicionado en el valor de 0.1ms.

8.5.5.¿Cuál es la amplitud de voltaje y el período de la señal que aparece en la pantalla del osciloscopio?

Amplitud de voltaje:

Como cada cuadro equivale a 3V y se observa 2 cuadros y un poco mas entonces da un valor aproximado de 6.8 (V)

Período:

Un ciclo es de 4 cuadros y esto se va a multiplicar po el valor de la perilla TIME/DIV que es de 0.0001 ms

4(0,0001) = 0,0004 s

T = 0,0004 s

8.5.6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.

Se va a usar el período anterior encontrado en la siguiente fórmula:

fn = 1/T

fn = 1/0.0004

fn: 2500 (Hz)

ω: 2πf

ω: 2π(2500)

ω: 15707,96 (rad/s)

8.5.7. Con el multímetro digital mida el voltaje de salida en RL: 4.833 V

![image](https://user-images.githubusercontent.com/116761073/219077189-03105df5-43f5-4287-bb84-9a3a0076c5a4.png)

8.5.8. Comparar el voltaje medido en el punto 8.5.5. y el obtenido en el punto 8.5.7.

No coinciden, esto se debe a que el osciloscopio da el valor del voltaje pico, mientras que el multimetro da un valor eficas es decir Vrms, esto pasa puesto que el multimetro da el 71% del valor del voltjae pico, si se quiere obtener el valor que da el osiloscpoio se debe usar la siguiente fórmula Vp = Vrms(0.707), reemplazando los valores Vp = 4.833(0.707), nos da Vp = 6.9 V que es el valor que da el osiloscopio.


