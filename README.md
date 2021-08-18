# l33tDictionaryGenerator

The main purpose of this tiny script is to generate a fast l33t dictionary to use it with tools like Hashcat, to perform dictionary attacks.

A common practice choosing easy to remember passwords inside companies is to change the company name letters to leet speak like:

google > go0gl€, g[]*6lë, 6()9G!E

nvidia > nV1d|a, ]\[Vid¦/\, NVI[>14

It can be combined with some masks in Hashcat adding characters before and after to attack more complex password hashes.

Usage:

python l33tDictionaryGenerator.py input.txt output.txt simple

--------------------------------------------------------------------------------

El propósito principal de este pequeño script es generar un rápido diccionario l33t para realizar ataques de diccionario con herramientas como Hashcat.

Una práctica habitual dentro de las empresas al elegir contraseñas fáciles de recordar es cambiar el nombre de la empresa a leet speak:

google > go0gl€, g[]*6lë, 6()9G!E

nvidia > nV1d|a, ][Vid¦/, NVI[>14

Se puede combinar con algunas máscaras en Hashcat añadiéndole caracteres delante y detrás para atacar hashes más complejos.

Uso:

python l33tDictionaryGenerator.py input.txt output.txt simple
