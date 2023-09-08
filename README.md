# Formulário de Usuário

Esse projeto foi desenvolvido à pedido do professor da disciplina Programação Orientada a Objetos para Web

## Reactive Forms

Criar um formulário de cadastro de usuário utilizando Reactive Forms no Angular. O formulário deve coletar informações como o nome e o endereço de e-mail do usuário. Além disso, você precisa realizar a validação dos campos para garantir que os dados inseridos sejam válidos antes de enviar o formulário.

### Passos:

#### Configuração do Projeto:

1. Crie um novo projeto Angular usando o Angular CLI.
2. Crie um componente chamado user-form que será responsável por exibir o formulário.
3. Formulário de Cadastro:

#### Abra o arquivo HTML do componente user-form e crie um formulário que inclua os seguintes campos:

1. Nome (input de texto)
2. E-mail (input de e-mail)
3. Botão de envio do formulário
4. Utilize Reactive Forms para criar e gerenciar o formulário.

#### Validação de Campos:

##### Implemente a validação dos campos:

1. O campo "Nome" deve ser obrigatório.
2. O campo "E-mail" deve ser obrigatório e conter um endereço de e-mail válido.

#### Manipulação de Dados:

1. Crie um método para lidar com o envio do formulário. Quando o formulário for enviado, os dados inseridos devem ser exibidos no console do navegador.

#### Teste:

1. Inicie o servidor de desenvolvimento Angular e teste o formulário em seu navegador.
2. Certifique-se de que a validação de campos está funcionando corretamente.
3. Verifique se os dados do formulário são exibidos no console quando o formulário é enviado.

##### Lembre-se de utilizar o módulo ReactiveFormsModule para trabalhar com Reactive Forms.
