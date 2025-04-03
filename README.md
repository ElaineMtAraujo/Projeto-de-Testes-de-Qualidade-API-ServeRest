# ✨ Projeto de Testes de Qualidade - API ServeRest

## 📚 Sobre o Projeto

Este projeto tem como objetivo avaliar a API do ServeRest, garantindo que todas as funcionalidades estejam operando corretamente, com segurança e eficiência. Foram aplicadas técnicas de teste para validar endpoints, autenticação, manipulação de dados e conformidade com boas práticas de desenvolvimento de APIs RESTful. Os testes foram estruturados com foco em verificar a integridade dos serviços e identificar possíveis falhas antes que impactem os usuários.

## 📌 Principais Testes Realizados

### ✔ Teste de Usuários:

- Cadastro de usuários com dados válidos e inválidos.

- Validação de resposta para tentativas de cadastro duplicado.

- Atualização de informações cadastrais.

- Exclusão de usuários e verificação de impactos no banco de dados.

### ✔ Teste de Produtos:

- Criação de produtos com atributos obrigatórios e opcionais.

- Consulta de produtos por ID e por lista.

- Atualização de informações de produtos.

- Exclusão de produtos e validação de status code correto.

### ✔ Teste de Login:

- Validação do endpoint de autenticação com credenciais válidas e inválidas.

- Verificação da expiração de tokens.

- Teste de tentativa de login sem enviar credenciais.

### ✔ Teste de Carrinho de Compras:

- Adição de produtos ao carrinho.

- Remoção de produtos e validação do status atualizado.

- Finalização de compra e confirmação da criação do pedido.

### ✔ Teste de Respostas HTTP:

- Validação dos status codes retornados pela API.

- Verificação de mensagens de erro e sua coerência com o esperado.

- Testes de limite de requisições por segundo (rate limiting).

## 🔧 Habilidades Utilizadas

- Planejamento e documentação de casos de teste

- Execução de testes manuais e automatizados via Postman

- Validação de respostas JSON com JSON Schema

- Análise de logs e monitoramento de requisições

- Report detalhado de bugs e sugestão de melhorias para a API

- Implementação de testes automatizados para endpoints principais

## 🏆 Resultados e Contribuição

Este projeto permitiu a identificação de falhas e inconsistências na API do ServeRest, garantindo maior segurança, estabilidade e eficiência. Foram sugeridas melhorias na gestão de erros e na padronização das respostas, bem como a implementação de testes de carga para avaliar o comportamento da API sob alto tráfego.

## 📅 Atualizações

[03/04/2025]: Criação do projeto e estruturação dos testes.

[03/04/2025]: Inclusão de testes detalhados para todos os endpoints principais.

[03/04/2025]: Implementação inicial de testes automatizados no Postman.

Este projeto faz parte do meu portfólio como Analista de QA, reforçando minha experiência em testes de API e qualidade de software.
