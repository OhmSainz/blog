---
layout: post
title: Analizador Sintáctico
---

Concepto: Analizador Sintáctico (Syntax Parser)

Es un programa que lee tu código y determina qué hace, si su gramática o su sintáxis es válida. Si eres alguien que estudió Sistemas o Informática este tema te será muy familiar, pero vamos, no pasa nada si es un tema nuevo. 

Cuando escribes código en JavaScript no es mágicamente decirle a la computadora qué hacer, recuerda eso, el código JavaScript como tal no hace magia. Imagina el siguiente escenario, estás abstraído entre pensamientos codeando, pero luego alguien más u otras personas crearon programas que convierten tu código JavaScript en algo que la computadora puede entender. Esos programas son denominados compiladores, aunque también existen los intérpretes. Estos programas hacen el proceso, su trabajo recae en leer código carácter por carácter y determinar si la sintaxis es válida y luego implementar esa sintáxis de una forma en la que la computadora pueda entenderlo. 

![](https://omarsainz.com/blog/images/Function.png)

Entonces, si tienes una función con una variable. Tanto la función como la variable se representarán en la memoria, pero siendo traducido de lo que estás escribiendo, lo que es más humano y legible, a lo que la computadora puede entender. Hay un compilador o intérprete entre esas dos cosas y parte de ello es un analizador de sintáxis, a través del cual pasan carácter por carácter palabras como: F-U-N-C-T-I-O-N. Entonces el analizador dice: Oh, esa es una función, debería de haber un espacio después de eso, luego lo siguiente será ver que unos paréntesis salgan o el nombre de la función, etc., etc.


