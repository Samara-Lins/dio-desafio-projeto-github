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
- Numeral
- Lógico
- Objeto