En la practica 4A se hizo el analisis de de 10 emisoras Fm con el objetivo de buscar si cumplian con el ancho de banda maximo regido 
por la agencia nacional de espectro, tambien para comprobar que la herramienta GNU Radio no es tan precisa ni tan fiable como el analizador
de espectro, aun asi sus medidas son utiles para tener una nocion de lo que se esta recibiendo, se busco tambien comprbar cada componente
de las emisoras (mono, piloto, estereo, RBDS, subcarriers) es decir caracterizar las emisoras.
![image](https://github.com/user-attachments/assets/a9d8765e-4959-41a4-aa3d-ae7fde183ab9)


En la siguiente imagen se pueden observar las emisoras analizadass con el uso de las herramientas de GNU radio, donde recalco el suo se un max-hold 
y ademas mejorando la resolusion  a 16200 para que fuera mas facil el analisis.



En la siguiente imagen se pueden apreciar dos emisoras analizadas con el analizador de espectro, en esta practica aprendimos a utilizar la funcion KpAm < 0.1 
de traza 2 y max hold dle analizador, esto debido a que las emisoras varian en frecuencia lo que dificultaba medir su ancho de banda haciendo uso del criterio
de los 20dB
![image](https://github.com/user-attachments/assets/be85ff43-e4af-47a6-be50-b61a50bcd30f)

las conclusiones de esta parte de la practica son que, hay emisoras que tienen diferentes caracteristicas y anchos de banda, ademas se pudo evidenciar
que la mayoria de las emisoras no cumplen el ancho de banda maximo permitido.

................................................................................................................................................................

En la practica 4B se buscó analizar el comportamiento de una modulacion fm en banda ancha y en banda estrecha, se analizaron 2 casos para los que KaAM < 0.1 y otros 
dos casos donde KpAm > 4, para estos analisis se reviso la señal en el tiempo por medio de GNU radio, luego la señal modulada en el analizador de espectro y finalmente
la señal modulada en el analizador de espectro.

En la siguiente imagen se puede apreciar un caso de KpAm < 0.1 donde se uede observar la modulacion en banda estrecha, en este caso se puede observar que esta modulacion
se parece mas a una modulacion en amplitud esto se da por el hecho de ser banda estrecha en el analizador de espectro se puede observar el armonico de la portadora y los
dos armonicos correspondientes al mensaje.

![image](https://github.com/user-attachments/assets/0b94b06d-01d2-4fe2-85ba-7d7879314dbb)

En la siguiente imagen se puede apresiar un caso de KpAm > 4 que ya hace parte de banda ancha, en esta ocasion su puede observar que la modulacion ya es una modulacion 
en frecuencia para este caso como ya es netamente una modulacion en frecuencia, se ven muchos mas armonicos en el analizador de espectro, en el analisis de la señal modulada 
en el osciloscopio se puede ver que la frecuencia aumenta desde el centro hacia los lados.

![image](https://github.com/user-attachments/assets/911c0acc-8a2b-409f-a0a6-d1c7da26e970)



conclusiones;
La señal modulada presenta una similitud significativa con la modulación AM, ya que los cambios en la frecuencia instantánea son pequeños y, visualmente, parecen variaciones en la amplitud.
En este régimen, la señal modulada se distingue claramente de una modulación AM, ya que los cambios significativos en la frecuencia instantánea generan múltiples componentes espectrales (bandas laterales), extendiéndose ampliamente en el espectro.
como no se puede evidensiar de forma evidende la modulacion fm en banda anchas se hizo el analisis con un KpAm > 10 dde la cual se obtuvo la siguiente imagen como se menciono
anteriormente la frecuencia de la señal modulada se ve como varia su frecuencia en el tiempo.

![image](https://github.com/user-attachments/assets/0857a6b3-d110-4372-abe0-3133d31f5e19)


![image](https://github.com/user-attachments/assets/b4310327-6cda-4e96-8665-6d9eb1b01c26)


![image](https://github.com/user-attachments/assets/7715ecc7-26d2-42cb-a549-0e8172ab8f1e)

