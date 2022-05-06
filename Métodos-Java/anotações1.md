# Métodos Java
*Definição:* É uma oprção de código (sub-rotina) que é disponibilizada por uma classe.Este é executado quando é feita uma requisição a ele. São responsáveis por definir e realizar um determinado comportamento.
## Criação de métodos
Padrão de definição:
<?visibilidade?> <?tipo?> <?modificador?> retorno nome  (<?parâmetros?>) <?exceções?> corpo
Onde:
V: "public", "protected" ou "private"
T: concreto ou abstrato
M: "static" ou "final"
R: tipo de dado
N: nome que é fornecido ao método
P: parâmetros que pode receber
E: exceções que pode lançar
C: código que possui ou vazio

## Utilização de métodos
Métodos precisam ser chamados através de classes ou objetos, através dos modelos nome_da_classe.nome_do_metodo(?parametros?) e nome_do_objeto.nome_do_metodo(?parametros?), respectivamente.

## Particularidades
- Construtor e Destrutor (orientação a objetos)
- Mensagem: é o ato de solicitar ao método sua execução. Pode ser direcionada a um objeto ou a uma classe.