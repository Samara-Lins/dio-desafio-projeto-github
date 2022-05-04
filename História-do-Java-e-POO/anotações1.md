# História do Java e Programação Orientada a Objetos
## Java
Java é uma linguagem de programação orientada a objetos desenvolvida na década de 90 pela empresa Sun Microsystems e, posteriormente, em 2008, adquirida pela Oracle.
Desde seu lançamento em maio de 1995, a plataforma Java foi adotada mais rapidamente do que qualquer outra linguagem de programação na história da computação.
Tornou-se popular com o uso da internet e está presente em programas de computador, jogos, celulares, calcuradoras entre outros.

### Características do Java
O Java é uma linguagem interpretada, ou seja, é traduzida para linguagem de máquina através de um compilador, através do seguinte processo:
	|Programa.java|-->|Compilador|-->|Programa.class|
O programa em formato "class" pode ser executado pela JVM (Java Virtual Machine).
Diferente das linguagens de programação compiladas, em que a compilação se dá ainda em tempo de desenvolvimento, a linguagem Java é compilada para um _bytecode_ (código em binário) que é interpretado por uma máquina virtual (JVM).

### Plataforma VS Linguagem
- A linguagem Java é uma linguagem de programação convencional da plataforma Java, mas não é sua única linguagem.
- Uma grande vantagem da plataforma é a de não estar presa a nenhum sistema operacional ou _hardware_, pois seus programas rodam através de uma máquina virtual que pode ser emulada.

### Fases da Execução Java
1. Escrevemos o código-fonte.
2. Utilizamos o JDK (Java Development Kit) para compilar o código-fonte e gerar o arquivo bytecode (arquivo com a extensão .class).
3. Para exeutar o programa, a JVM lê o arquivo compilado (.class) e as bibliotecas padrão do Java que estão no JRE.