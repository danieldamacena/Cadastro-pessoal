# Cadastro pessoal do Daniel Damacena

O formulário tem os seguintes campos: nome completo, CPF, RG, CEP, endereço, número, bairro, cidade, Estado, telefone fixo, telefone celular.
O seguintes campos são obrigatórios: nome, cpf, cep e telefone celular. Se esses campos não forem preenchidos, os dados do formulário não serão submetidos.
Observação: foi inserida a funcionalidade de preenchimento automático de endereço, bairro, cidade e Estado a partir do número do CEP, daí a obrigatoriedade do campo, já que as regras de negócio definem que o endereço e o número são itens obrigatórios.

Funcionalidades:
Os campos obrigatórios possuem o atributo required, que não permite a submissão dos dados do formulário caso eles estejam em branco. Caso o campo exija que a entrada de texto seja apenas composta de números, o atributo também fará essa validação.
O botão "carregar" ativa a função que insere endereço, bairro, cidade e Estado nos respectivos campos a partir do CEP inserido pelo usuário, como mencionado anteriormente. Caso o CEP esteja em branco ou seja inválido, serão exibidos alertas ao usuário, que será direcionado novamente ao campo, de modo que insira um CEP válido.

Fontes de pesquisa:
1. Validação de formulários em HTML5: https://tableless.com.br/validacao-de-formularios-com-html5/
2. Atributo onclick: https://www.w3bai.com/pt/tags/ev_onclick.html
3. https://viacep.com.br/