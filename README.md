[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=l22211757-svg/Practica0MSF)
# Práctica: Regeneracion de globulos rojos

## Información de la estudiante

Paola Gonzalez Sanchez [22211757]; l22211757@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Comprender el proceso de eritropoyesis
2. Fortalecer la relación entre modelos matemáticos y procesos biológicos reales
3. Simular la recuperación del número de eritrocitos
4. Interpretar los resultados obtenidos de la simulación.
5. Utilizar condiciones iniciales representativas
6. Aplicar el método numérico de Euler
7. Desarrollar habilidades para la resolución computacional

## Descripción detallada del sistema

El modelo utilizado describe el proceso de eritropoyesis, es decir, la producción y maduración de glóbulos rojos en el organismo. Este proceso se representa mediante tres compartimentos celulares que evolucionan con el tiempo:

x₁(t): células precursoras tempranas que se dividen activamente en la médula ósea.

x₂(t): células precursoras en maduración que continúan su diferenciación.

x₃(t): eritrocitos maduros que circulan en la sangre y transportan oxígeno.

La hormona eritropoyetina, producida por el riñón, regula este proceso y aumenta su producción cuando disminuyen los niveles de oxígeno en los tejidos. Además, el modelo considera la muerte natural de las células y puede incluir una transfusión sanguínea representada como una entrada externa que incrementa temporalmente la cantidad de eritrocitos maduros.

El sistema se resolvio con las siguientes condiciones iniciales:
X1(0)=59.03.
X2(0)=44.27.
X3(0)=885.42.

Condiciones iniciales de los parametros de gamma y beta 
gamma = [0.796, 0.388,0.510,0.590,0.262,0.324,0.356, 0.089, 0.243, 0.057]; 
beta = [1.650,0.867,1.617,2.615,1.518,2.676,0.891,2.557,0.925,0.089]

Palabras clave: Eritropoyesis; Eritropoyetina; Glóbulos rojos; Modelado matemático; Ecuaciones diferenciales; Transfusión sanguínea.

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB \[.mlx].
2. Imágenes de las simulaciones Caso Sin transfusion sanguinea \[.pdf ].
3. Imágenes de las simulaciones Caso Con transfusion sanguinea \[.pdf ].

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] Tetschke, M., Liebenthal, P., Potgieter, T., Fiechter, T., Schälte, E., & Sager, S. (2018). Mathematical modeling of RBC count dynamics after blood loss. Processes, 6(9), 157.  file:///C:/Users/HP/Downloads/processes-06-00157.pdf  

