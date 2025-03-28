[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=mirosjm/MSF-Practica-2)

# Modelado de Sistemas Fisiológicos. Práctica 2: Sistema Respiratorio [Jacobo21212669]

## Autor
Miroslava Jacobo Mendoza

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l21212669@tectijuana.edu.mx

## Objetivos general
Diseñar un controlador que permita formular un protocolo de tratamiento para que un paciente con efiema (caso) presente la misma presión alveolar que un individuo sano (control).

## Actividades
1. Calcular analíticamente la función de transferencia del sistema pulmonar.
2. Establecer el modelo de ecuaciones integro-diferenciales.
3. Determinar el error en estado estacionario y la estabilidad del sistema en lazo abierto.
4. Construir el diagrama de bloques.
5. Disenar el controlador con Simulink utilizando el bloque PID Controller y la herramienta Tune para sintonizar los valores óptimos para cada una de las ganancias kP, kI y kD.
6. Ilustrar el canbio de flujo y el aire tidal en respuesta a las siguientes formas de onda de presión sinusoidal en la apertura de la vía aerea [Pao(t)]:
   a) 15 respiraciones por minuto con una amplitud (A) de 2.5 cmH2O, es decir, respiración normal
   b) 30 respiraciones por minuto con una amplitud (A) de 1.5 cmH2O, es decir, respirAción elevada o taquipnea.
7. Determinar la respuesta a la función sinusoidal [u(t) = Asinwt] en el intervalo tƎ[0,30] (Segundos) en Python, Simulink y Multisim en lazo abierto.
8. Elaborar el dagrama biológico del sistema con BioRender.com.
9. Discutir los resultados obtenidos en la experientación in silico y elaborar el reporte de la practica.
      
## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus para la asignatura de Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/scl/fi/4gl55ccrjm9yulvziikxs/Modelado-de-Sistemas-Fisiologicos.pdf

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018.
