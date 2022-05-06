# Conceitos Chave da Linguagem Java
## Variáveis
*Definição:* É um espaço na memória do computador que pode armazenar valores.
Existem 4 tipos de variáveis:
- Instância: objeto
- Classe: classe
- Local: dentro de métodos
- Parâmetro: na assinatura do método

##Criação
Padrão de definição:
<?visibilidade?>  <?modificador?> tipo nome <?=valor inicial?>;

V: "public", "protected" e "private" (opcional)
M: "static" e "final" (opcional)
T: tipo de dado
N: nome que é fornecido à variável
VI: um valor inicial (opcional)

### Conveções na criação de variáveis
Algumas convenções e regras da criação de variáveis em Java:
- Não devem começar com números;
- Embora permitido, "$" e "_" devem ser evitados;
- Case sensitive;
- Não permite espaços;
- Não permite o uso de palavras reservadas;

### Boas práticas da criação em Java
- Sempre começar nomes de variáveis com letra minúscula;
- Nomes expressivos;
- Notação camelo (separar palavras pelo case);
- Constantes (final) em maiúsculo e separação por "_"

### Tipos de dado
São os valores e consequentemente operações que as variáveis podem assumir e sofrer, respectivamente.
#### Tipificação
- Estática (forte) vs Dinâmica (fraco)
- Primitivo vs Composto

_* Pesquisar sobre linguagens compiladas vs linguagens interpretadas_

#### Opções de tipos
- Textual
  -  char: caracteres de 16-bit unicode -> char c = '\u0084'; ou char c = 'T';
  -  String: um tipo "especial" -> String s = "T";
- Numeral
  -  byte: -128 até 127 -> byte b = 15;
  -   short: -32768 até 32767 -> short s = -15785;
  -  int: -2147483648 até 2147483647 -> int i = 8515785;
  -  long: -9223372036854775808 até 9223372036854775807 -> long l = 5938515785L; 
  -  float: +-3.40282347E + 38F -> float f = 3.14...(f);
  -  double:+-1.79769313486231570E + 308 -> double d = 3.14...(d)
- Lógico 
  -  boolean: true ou false -> boolean s = false;
- Objeto

## Operadores
São símbolos especiais capazes de realizar ações específicas em um, dois ou mais operandos e, em seguida, retornar um resultado.

### Tipos de operadores
- Pós-fixado: exp++ ou exp--;
- Prefixado: ++exp ou --exp
- Aritmético: +,-,*,/ e %;
- Atribuição: =, +=, *=, /= e %=

## Casting
*Definição: *É a transformação de determinada variável de um tipo menos específico para um tipo mais específico ou vice-versa.

### Tipos
- Upcast (implícito)
- Downcast (explícito)