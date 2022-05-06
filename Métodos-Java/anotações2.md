# Sobrecarga
É a capacidade de definir métodos para diferentes contextos, mas preservando seu nome.
## Como gerar uma sobrecarga
Uma sobrecarga é gerada alterando-se a assinatura do método, sendo que seu nome é mantido e a mudança ocorre na lista de parâmetros do método.

# Retorno
Assim como o break e o contínuo, o retorno é uma instrução de interrupção. Ocorre por qualquer uma das três situações:
- Percorreu todas as suas linhas internas (finalizado);
- Encontrou durante sua execução uma chamada explícita ao retorno (return encontrado dentro do código do método);
- Por uma exceção encontrada durante sua execução.

## Considerações
- O tipo de retorno do método é definido em sua criação e pode ser um tipo primitivo ou objeto;
- O tipo de dado do return deve ser compatível com o do método;
- Se o método for sem retorno (void), pode ou não ter um "return" para encerrar sua execução.