[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=marcoca712-gif/MSFExamen-Sistema-Circulatorio)

# Examen: Sistema Circulatorio

## Información del estudiante

Campoy Alegria Marco Antonio \[21212145]; L21212145@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1.Dibujar el diagrama elÈctrico del sistema circulatorio, identificando cada uno de sus elementos, es decir,
componentes, voltajes, corrientes y nodos de entrada y salida. 
2. (Determine el modelo de ecuaciones integro-diferenciales.
3. Calcule la funcion de transferencia del sistema.
4. Calcule el error en estado estacionario.
5. Ilustre la respuesta en lazo abierto del control y del caso a un escalon unitario de entrada en Python
o Simulink.
6. Dise;e un controlador en lazo cerrado, con base en el siguiente diagrama, que permita eliminar el
error en la respuesta del caso

## Descripción detallada del sistema
El sistema circulatorio es el encargado de bombear, transportar y distribuir la sangre, oxígeno y nutrientes por todo el cuerpo. Esta hemodinámica puede representarse de forma simplificada mediante un circuito eléctrico de segundo orden (acorde a los modelos tipo Windkessel), modelando los procesos de eyección cardíaca, complianza arterial y resistencia vascular bajo las siguientes suposiciones:

La presión generada por el corazón (por ejemplo, la presión del ventrículo izquierdo) se modela mediante una fuente de voltaje de entrada V_e(t), que representa la fuerza impulsora inicial del sistema.

La oposición al flujo sanguíneo en las válvulas cardíacas o en la aorta proximal se modela con una resistencia R_1, asociada a la resistencia característica inicial durante la eyección de la sangre.

La elasticidad de las grandes arterias (complianza arterial), que les permite expandirse y almacenar volumen de sangre temporalmente, se representa con un capacitor C, el cual regula y amortigua los cambios de presión en el tiempo.

La circulación periférica se modela mediante una segunda rama con una resistencia R_2 y una inductancia L, representando la resistencia vascular sistémica (de arteriolas y capilares) y la inercia biológica de la masa sanguínea en movimiento, respectivamente.

Se identifican los siguientes dos flujos en el sistema: el flujo de entrada o gasto cardíaco F_e(t) y el flujo de salida o perfusión tisular F_s(t).

Palabras clave: Hemodinámica; Complianza arterial; Flujo Fs (t); Resistencia vascular periférica;

## Lista de archivos incluidos en el repositorio

1. Modelo de Simulink \[.slx].
2. Imagen con los parámetros del controlador.
3. Imágenes de las simulaciones \[.pdf].
4. Evidencia del análisis matemático: función de transferencia, modelo de ecuaciones integro-diferenciales.

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley \& Sons, 2020.

\[4] T. Kind, T. J. Faes, J. W. Lankhaar, A. Vonk-Noordegraaf \& M. Verhaegen, "Estimation of three-and four-element Windkessel parameters using subspace model identification", IEEE Transactions on Biomedical Engineering, vol. 57, issue 7, pp. 1531-1538, Jul 2010. https://doi.org/10.1109/TBME.2010.2041351

