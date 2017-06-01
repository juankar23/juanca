##Laboratorio 8-Modelamiento por Homología
### Juan Carlos Rohrer. Sección 11:15

En el corriente laboratorio se evaluó una secuencia aminoacídica con el fin de generar archivos .pdb por medio de la herramienta "modeller". Se introdujo la secuencia en blastp para buscar una proteína homóloga a la secuencia y coincidió con la mayor identidad la proteína 3LRX_A, que corresponde a la estructura cristalina del dominio C-terminal de una hidrogenasa de Pyrococcus furiosus_.
Una vez obtenida la proteína por homología, mediante archivos proporcionados por los docentes, se utilizó modeller con sus comandos respectivos para generar posibles modelos con pequeñas variaciónes tridimensionales en cada uno.  
Modeller asigna este puntaje mediante un algoritmo propio al cual denomina DOPE score. Cuanto mayor sea el número de score DOPE en magnitud, mejor será el modelo creado. En mi caso particular el mejor DOPE score correspondió al modelo 5 con un score de -16826.06445, mientras que el peor fue el modelo 3 con un score de -16003.44434.
Posteriormente con la ayuda de VMD, se realizó una representación gráfica de ambos modelos. En la imagen se logra visualizar en color verde el modelo correspondiente a el modelo 3. Mientras que en cyan se observa el modelo 5. 
Las diferencias a nivel intermedio de la proteína es mínimo, sin embargo al visualizar los extremos tanto amino como carboxilo terminales lejanías en el modelo tridimensional. Por lo que debido a esto se concluye que los dominios conservados de la proteína (dominios alfa hélice) pueden relacionarse con la función proteica ya que son mayormente conservados, mientras que los extremos varían en su ensamblaje debido a que la variedad de aminoácidos deben ser con menor rigidez de enlace, brindando por lo tanto mayor libertad en el ensamblaje proteico final.
![](https://cloud.githubusercontent.com/assets/28123434/26663823/672a1f88-465b-11e7-9cd2-80a8700d6242.PNG)
