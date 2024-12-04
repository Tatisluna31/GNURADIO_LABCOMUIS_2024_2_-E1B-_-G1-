En la practica 4A se hizo el analisis de de 10 emisoras Fm con el objetivo de buscar si cumplian con el ancho de banda maximo regido 
por la agencia nacional de espectro, tambien para comprobar que la herramienta GNU Radio no es tan precisa ni tan fiable como el analizador
de espectro, aun asi sus medidas son utiles para tener una nocion de lo que se esta recibiendo, se busco tambien comprbar cada componente
de las emisoras (mono, piloto, estereo, RBDS, subcarriers) es decir caracterizar las emisoras.
![image](https://github.com/user-attachments/assets/a9d8765e-4959-41a4-aa3d-ae7fde183ab9)


En la siguiente imagen se pueden observar las emisoras analizadass con el uso de las herramientas de GNU radio, donde recalco el suo se un max-hold 
y ademas mejorando la resolusion  a 16200 para que fuera mas facil el analisis.



En la siguiente imagen se pueden apreciar dos emisoras analizadas con el analizador de espectro, en esta practica aprendimos a utilizar la funcion 
de traza 2 y max hold dle analizador, esto debido a que las emisoras varian en frecuencia lo que dificultaba medir su ancho de banda haciendo uso del criterio
de los 20dB
![image](https://github.com/user-attachments/assets/be85ff43-e4af-47a6-be50-b61a50bcd30f)

las conclusiones de esta parte de la practica son que, hay emisoras que tienen diferentes caracteristicas y anchos de banda, ademas se pudo evidenciar
que la mayoria de las emisoras no cumplen el ancho de banda maximo permitido.

................................................................................................................................................................

En la practica 4B se buscó analizar el comportamiento de una modulacion fm en banda ancha y en banda estrecha, se analizaron 2 casos para los que KaAM < 0.1 y otros 
dos casos donde KpAm > 4, para estos analisis se reviso la señal en el tiempo por medio de GNU radio, luego la señal modulada en el analizador de espectro y finalmente
la señal modulada en el analizador de espectr.

En la siguiente imagen se puede apreciar un caso de KpAm < 0.1 donde se uede observar la modulacion en banda estrecha.
