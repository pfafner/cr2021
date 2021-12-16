# Criptografía y Cifrado de la Información 2021

Este curso es una introducción al estudio de los métodos de criptografía, criptoanálisis y cifrado de la información, la cual consiste en procesar datos en forma ininteligible, de forma reversible, sin pérdida de información, normalmente de forma digital. Dicho de otra forma, la criptografía es el estudio de cómo alterar un mensaje para que alguien que lo intercepte no pueda leerlo sin el algoritmo y la clave adecuados. En esta materia, estudiaremos de manera introductoria los principales métodos y protocolos actuales de cifrado, así como su implementación computacional.

La primera parte el curso inicia con una revisión histórica de la criptografía, para dar paso rápidamente a los métodos usados en la criptografía actual. Se hace una revisión de conceptos y herramientas básicas sobre los que se fundamentan la mayoría de algoritmos y métodos criptográficos. Se estudian los métodos criptográficos simétricos. En particular, se estudian principalmente los métodos de cifrado en flujo (*stream ciphers*), así como los cifrados en bloque (*block ciphers*). Se estudian métodos de integridad de datos, y algunas construcciones clásicas como los sistemas de autenticación de mensajes (MAC). Luego se estudian los métodos asimétricos. Se introduce el concepto de intercambio de claves, y los métodos de cifrado de clave pública y sus aplicaciones. Estudiamos principalmente los protocolos de Diffie-Hellman, el sistema RSA, así como los métodos CCA.

El curso finaliza con una serie de temas avanzados y recientes como la criptografía de curvas elípticas y otros métodos avanzados. Se discuten temas novedosos como las criptomonedas y los métodos de *blockchain*, así como las implicaciones de la computación cuántica para la criptografía.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los siguientes temas:
* Álgebra lineal (matricial).
* Matemática discreta (conteo, permutaciones, divisibilidad, congruencias).
* Cálculo (funciones, límites, derivadas).
* Estadística (probabilidad, distribuciones de probabilidad).
* Programación en Python.

Bastará con haber cursado una materia de cálculo, una de estadística, una de álgebra lineal, y una de mátemática discreta. En el caso de programación, bastará con haber tomado un curso básico de Python, aunque conviene conocer temas de estructuas de datos y algoritmos.

El curso tiene una carga fuerte en el tema de Teoría de Números. Cuando sea conveniente, dedicaremos una parte del curso a cubrir algunos prerrequisitos necesarios en los temas de congruencias y aritmética modular. También cubriremos algún material sobre distribuciones discretas de probabilidad.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-cr2021.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Martes y Jueves, de 19:00 a 20:35.

### Office Hours
<div id='id-office'/>

* Viernes, de 18:00 a 20:00


# Material del curso
<div id='id-material'/>

  **No.**  | **Fecha**    | **Tópicos**                                                                    | **Recursos**
  -------- | ------------ | ------------------------------------------------------------------------------ |  -------------------------------------
  01       | 08.07.2021   | Introducción. Aspectos generales de la criptografía. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"}  | Secciones 1.1 a 1.4, Handbook.
  02       | 13.07.2021   | Sistemas de cifrado históricos. <br/> [Aula 02](aulas/Aula02.pdf){:target="_blank"}  | Capítulos 1 y 2, libro de Easttom.
  L1       | 15.07.2021   | Lab 1  [Lab 01](labs/Lab01.pdf){:target="_blank"}                              | [cipher1.txt](labs/cipher1.txt){:target="_blank"} [cipher2.txt](labs/cipher2.txt){:target="_blank"} [cipher3.txt](labs/cipher3.txt){:target="_blank"} <br/> [sp_frequencies.txt](labs/sp_frequencies.txt){:target="_blank"}
  03       | 20.07.2021   | Repaso de probabilidad. <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"}    | 
  04       | 22.07.2021   | Repaso de probabilidad II. <br/> [Aula 04](aulas/Aula04.pdf){:target="_blank"} | 
  L2       | 22.07.2021   | Lab 2                                                                          | [Lab 02](labs/Lab02.pdf){:target="_blank"} 
  05       | 27.07.2021   | One Time Pad. Cifrados de flujo. <br/> [Aula 05](aulas/Aula05.pdf){:target="_blank"} | 
  06       | 03.08.2021   | Cifrados de flujo II. <br/> [Aula 06](aulas/Aula06.pdf){:target="_blank"}      |  
  L3       | 05.08.2021   | Lab 3                                                                          | [Lab 03](labs/Lab03.pdf){:target="_blank"} <br/> [Imagenes_a_bits.ipynb](labs/Imagenes_a_bits.ipynb){:target="_blank"}
  07       | 10.08.2021   | Seguridad de PRGs. Test Estadísticos. <br/> [Aula 07](aulas/Aula07.pdf){:target="_blank"} | 
  L4       | 12.08.2021   | Lab 4                                                                          | [Lab 04](labs/Lab04.pdf){:target="_blank"} <br/>
  08       | 17.08.2021   | Cifrados de bloque. DES. <br/> [Aula 08](aulas/Aula08.pdf){:target="_blank"} | 
  09       | 19.08.2021   | Cifrados de bloque II. AES. <br/>  [Aula 09](aulas/Aula09.pdf){:target="_blank"} | 
  L5       | 19.08.2021   | Lab 5                                                                          | [Lab 05](labs/Lab05.pdf){:target="_blank"} <br/>
  10       | 31.08.2021   | Integridad de mensajes. <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"}    | 
  11       | 02.09.2021   | Funciones Hash. SHA-256. HMAC. <br/> [Aula 11](aulas/Aula11.pdf){:target="_blank"} | 
  L6       | 07.09.2021   | Lab 6                                                                          | [Lab 06](labs/Lab06.pdf){:target="_blank"} <br/> [Ejemplos](labs/lab06-ejemplos.ipynb){:target="_blank"}
  12       | 21.09.2021   | Repaso de divisibilidad, MMC, Algoritmo de Euclides. <br/> [Aula 12](aulas/Aula12.pdf){:target="_blank"} | 
  13       | 21.09.2021   | Repaso de aritmética modular. Potenciación binaria. <br/> [Aula 13](aulas/Aula13.pdf){:target="_blank"} | 
  14       | 23.09.2021   | Aritmética modular. Función $\varphi$ de Euler. Teorema de Euler-Fermat. Test de Fermat  | [Aula 14](aulas/Aula14.pdf){:target="_blank"}
  L7       | 23.09.2021   | Lab 7                                                                          | [Lab 07](labs/Lab07.pdf){:target="_blank"}
  15       | 28.09.2021   | Residuos cuadráticos. Orden y raíces primitivas. <br/> [Aula 15](aulas/Aula15.pdf){:target="_blank"} |
  16       | 05.10.2021   | Intercambio de claves. Mètodo de Diffie-Hellman. <br/> [Aula 16](aulas/Aula16.pdf){:target="_blank"} |
  L8       | 07.10.2021   | Lab 8                                                                          | [Lab 08](labs/Lab08.pdf){:target="_blank"}
  17       | 14.10.2021   | Cifrados de clave pública. RSA. <br/> [Aula 17](aulas/Aula17.pdf){:target="_blank"} | 
  18       | 19.10.2021   | RSA y ataques a RSA. <br/> [Aula 18](aulas/Aula18.pdf){:target="_blank"}       | 
  L9       | 21.10.2021   | Lab 9                                                                          | [Lab 09](labs/Lab09.pdf){:target="_blank"}
  19       | 26.10.2021   | Cifrado de ElGamal. <br/> [Aula 19](aulas/Aula19.pdf){:target="_blank"}        | 
  L10      | 02.11.2021   | Lab 10                                                                         | [Lab 10](labs/Lab10.pdf){:target="_blank"}
  20       | 04.11.2021   | Firmas Digitales. Aplicaciones. <br/> [Aula 20](aulas/Aula20.pdf){:target="_blank"} | 
  21       | 09.11.2021   | Construcción de Firmas Digitales. <br/> [Aula 21](aulas/Aula21.pdf){:target="_blank"} | 
  22       | 16.11.2021   | Presentación de Seminarios.                                                    | 
  23       | 18.11.2021   | Presentación de Seminarios.                                                    | 
  24       | 23.11.2021   | Presentación de Seminarios.                                                    | 
  25       | 25.11.2021   | Presentación de Seminarios.                                                    | 


# Claves públicas para el Lab 9 

**Equipo**    | **Clave Pública**    |  **Equipo**    | **Clave Pública**    
------------- | -------------------- | -------------- | -------------------- 
 Equipo 1     | MjE0NjE1LjI3MTc0MQ== | Equipo 7       | MjYxMjUxLjQzMzg0Mw==
 Equipo 2     | MTM2NjI3LjEzNzkwMw== | Equipo 8       | MjM4NzAzLjM2MDg3Nw==
 Equipo 3     | MzAzOTk3LjM0NTM4Mw== | Equipo 9       | 
 Equipo 4     | NjE5NTcuODIzMTk=     | Equipo 10      | MjE0OS4xMTM1         
 Equipo 5     | MzQ3NDAyLjc2MjA3OQ== | Equipo 11      | 
 Equipo 6     | MzEzMTUxLjQxODM2Nw== | Equipo 12      | Mjc4NDcxLjgyOTAyMQ==


# Seminarios

A continuación se listan algunos temas sugeridos para presentación de seminarios. [Temas-seminario.pdf](projects/Temas-seminario.pdf){:target="_blank"}

Temas a presentar:

**Tema No.**  | **Equipo**   |  **Fecha**   | **Tópicos**                                                                    
------------- | ------------ | ------------ | -----------------------------------------
 10           |  Equipo 1    |  16.11.2021  | Protocolos de seguridad de redes [Presentación](){:target="_blank"}
 9            |  Equipo 6    |  16.11.2021  | Firewalls [Presentación](){:target="_blank"}
 7            |  Equipo 2    |  16.11.2021  | Protocolo SSH [Presentación](){:target="_blank"}
 2            |  Equipo 5    |  18.11.2021  | Seguridad Web [Presentación](){:target="_blank"}
 8            |  Equipo 4    |  18.11.2021  | Protocolos SSL/STL y Https [Presentación](){:target="_blank"}
 3            |  Equipo 8    |  18.11.2021  | VPNs y *Tunneling* [Presentación](){:target="_blank"}
 4            |  Equipo 12   |  23.11.2021  | Cifrado en VPNs [Presentación](){:target="_blank"}
 5            |  Equipo 3    |  23.11.2021  | Cifrado en WhatsApp [Presentación](){:target="_blank"}
 6            |  Equipo 11   |  23.11.2021  | Cifrados en Telefonía Móvil [Presentación](){:target="_blank"}
 11 y 12      |  Equipo 7    |  25.11.2021  | Blockchain y Criptomonedas [Presentación](){:target="_blank"}
 17           |  Equipo 9    |  25.11.2021  | Criptovirología [Presentación](){:target="_blank"}
 15           |  Equipo 10   |  25.11.2021  | Certificados Digitales en Guatemala [Presentación](){:target="_blank"}


# Referencias
<div id='id-ref'/> 

### Textos:

* [D. Boneh, V. Shoup (2020). *A Graduate Course in Applied Cryptography*.](http://toc.cryptobook.us/){:target="_blank"}

* [N. Smart (2016). *Cryptography Made Simple*.](http://library.lol/main/0BA15B42E21B98223BC711A4CD3564CC){:target="_blank"}


### Referencias adicionales:

* [A. Menezes, P. van Oorschot, S. Vanstone (2021). *Handbook of Applied Cryptography*.](http://cacr.uwaterloo.ca/hac/){:target="_blank"}

* [William Easttom (2021). *Modern Cryptography*.](http://library.lol/main/B5DB9B050F1044082F9ED26411AFC68B){:target="_blank"}

* [Jonathan Katz, Yehuda Lindell (2021). *Introduction to Modern Cryptography*](http://library.lol/main/7D5DC1756540342F85FE9E259A27CCDB){:target="_blank"}

* [Niels Ferguson, Bruce Schneier, Tadayoshi Kohno (2012). *Cryptography Engineering*. 3rd. Edition.](http://library.lol/main/1AE4E3F764B5DF33684E6F1967247A90){:target="_blank"}

* [Seth James Nielson, Christopher K. Monson (2019). *Practical Cryptography in Python*.](http://library.lol/main/4EDBDF158332CDC1356AEB3A99E3DF68){:target="_blank"}

* [Christof Paar, Jan Pelzl (2010). *Understanding Cryptography*.](http://library.lol/main/AF81CAABE760D15FA77407B09268EA96){:target="_blank"}

* [Jeffrey Hoffstein, Jill Pipher, Joseph H. Silverman (2008). *An Introduction to Mathematical Cryptography*.](http://library.lol/main/025B703D15FBA2AAF6F4750AD959187D){:target="_blank"}

* [David Wong (2021). *Real-World Cryptography*.](http://library.lol/main/596C1D3C55B73ED374A7FBA8D856589E){:target="_blank"}

* [Jean-Philippe Aumasson (2018). *Serious Cryptography*.](http://library.lol/main/772A00F78F3980BBC8ADCC04BBDC7477){:target="_blank"}


### Referencias en teoría de números y matemática discreta:

* [Kenneth Rosen (2011). *Elementary Number Theory*.](http://library.lol/main/4F17982CE43B7BB0AE7543C1946A22DD){:target="_blank"}

* [Kenneth Rosen (2013). *Discrete Mathematics and its Applications*.](http://library.lol/main/638D5EC2547DEF019458AB88AD39A040){:target="_blank"}

---
