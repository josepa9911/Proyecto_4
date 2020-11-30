# Modelos probabilísticos de señales y sistemas
## Proyecto 4: Modulación digital, pruebas de estacionaridad y densidad del espectro de potencia

### Realizado por: José Pablo Araya Garbanzo ; Carné: B80508

El proyecto a realizar tiene dos divisiones importantes, la sección de modulación digital y la sección de pruebas de estacionaridad. Por tanto se explicará su procedimiento, metodología y resultados por aparte. 

#### Modulación digital

En la sección de modulació digital es importante destacar los dos tipos de modulación con los que se trabajó: BSPK y QSPK. En esencia, la modulación en BSPK, cada símbolo que transfiere contiene un bit de información, en cambio en la modulación QSPK se contienen 2 bits de información por símbolo. Además, para comentar sobre el proceso de modulación se tienen 6 pasos principales. Primero, se convierto la imagen en código RGB, posteriormente, con base en la información del código RGB se convierte en cadenas de bits. Luego continúa el proceso de modulación, el cuál consiste en a partir de la cadena de bits de entrada, como se trabajaba en códgio RGB habrán 8 bits para poder representar los 256 colores; entonces, la modulación mandaría la información en paquetes de 8 bits. Para enfocarse en un proceso más realista, se usa una función de ruido para añadirle la interferencia que se presenta durante la transmisión de la señal. Finalmente, viene el proceso de demodulación que en esencia con base en la señal de ruido que obtiene, juzga el bit correspondiente en función de ciertos parámetros como la potencia de la señal de salida y la potencia de señal original. 

La modulación QSPK, posee dos portadoras de información (ortogonales entre ellas), 
