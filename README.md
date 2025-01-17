
Testes de API - Repositório de Testes e Configuração de Ambiente

Este repositório contém testes de API para o desafio de integração com a plataforma Serverest. O objetivo é validar as funcionalidades das APIs disponíveis, incluindo o cadastro, listagem, edição e exclusão de usuários.

Pré-requisitos
Antes de começar a rodar os testes, siga os passos abaixo para configurar o ambiente de testes:

1. Instalar o Postman
Baixe e instale o Postman a partir do site oficial.
O Postman será utilizado para enviar as requisições para a API e visualizar os resultados dos testes.
2. Acessar a API Serverest
Acesse o ambiente de testes da API Serverest, onde as APIs estão disponibilizadas para teste.
3. Importar a Collection de Testes
Dentro da interface do Postman, acesse a collection chamada "Carrefour desafio".
Esta collection contém os endpoints necessários para realizar os testes.
Dentro da collection "Carrefour desafio", você encontrará os seguintes endpoints para realizar os testes:

Cadastro de Usuário
Método: POST
Descrição: Envia uma requisição para cadastrar um novo usuário, alterando as informações no corpo da requisição (exemplo: nome, e-mail, senha).
Validação: O status da requisição e o tempo de resposta são validados automaticamente.

Listagem de Usuários
Método: GET
Descrição: Envia uma requisição para listar todos os usuários cadastrados. É possível listar também somente os usuários administradores.
Validação: O tempo de resposta e a estrutura da lista de usuários são validados automaticamente.


Buscar Usuário por ID
Método: GET
Descrição: Envia uma requisição para buscar um usuário específico pelo seu ID de cadastro.
Validação: O teste verifica se o ID informado retorna o usuário correto.

Editar Usuário
Método: PUT
Descrição: Envia uma requisição para editar os dados de um usuário já cadastrado. Os dados podem ser alterados diretamente no corpo da requisição.
Validação: O teste valida se os dados do usuário foram corretamente atualizados.

Deletar Usuário
Método: DELETE
Descrição: Envia uma requisição para excluir o cadastro de um usuário pelo seu ID.
Validação: O teste valida se a exclusão foi realizada corretamente e o status de sucesso da requisição.

Foi adicionado em cada end-point na aba de testes validações extras,
