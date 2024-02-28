# Contrato ANAC

Este é um contrato inteligente escrito em Solidity que implementa os requisitos fornecidos pela Agência Nacional de Aviação Civil (ANAC) para verificar os documentos necessários para embarque em voos internacionais.

O contrato inclui uma variável de estado `idade` que armazena a idade do passageiro e duas funções `setIdade` e `getIdade` para definir e recuperar a idade, respectivamente.

## Testes

Aqui estão alguns testes que podem ser realizados para verificar o funcionamento do contrato:

1. **Teste de Definição de Idade**:
   - Chame a função `setIdade` com uma idade diferente de 18.
   - Chame a função `getIdade` para verificar se a idade foi definida corretamente.

2. **Teste de Restrição de Acesso**:
   - Chame a função `setIdade` de um endereço diferente do proprietário do contrato.
   - Verifique se a transação é revertida e exibe a mensagem de erro correta.

3. **Teste de Retorno de Idade**:
   - Chame a função `getIdade` para verificar se ela retorna a idade correta.

4. **Teste de Eventos**:
   - Chame a função `setIdade` e verifique se o evento `IdadeSet` é registrado corretamente.

## Como Testar o Contrato

1. Clone o repositório para o seu computador.
2. Abra o contrato no Remix.
3. Compile e implante o contrato no Remix.
4. Interaja com o contrato usando as funções `setIdade` e `getIdade` para testar seu funcionamento.

