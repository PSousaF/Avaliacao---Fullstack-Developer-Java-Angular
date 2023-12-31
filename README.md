# Sistema de Cadastro de Beneficiários e Seus Documentos

Este é um projeto Java Spring Boot com uma API REST para gerenciar o cadastro de beneficiários, incluindo um front-end para interação com a API.

## Funcionalidades

1. **Cadastro de Beneficiário:**
   - Endpoint: `POST /api/beneficiarios/cadastro`
   - Cadastra um beneficiário junto com seus documentos.

2. **Listagem de Beneficiários:**
   - Endpoint: `GET /api/beneficiarios/listar`
   - Lista todos os beneficiários cadastrados.

3. **Listagem de Documentos de um Beneficiário:**
   - Endpoint: `GET /api/beneficiarios/documentos/{id}`
   - Lista todos os documentos de um beneficiário com base no ID.

4. **Atualização de Dados Cadastrais de um Beneficiário:**
   - Endpoint: `PUT /api/beneficiarios/atualiza/{id}`
   - Atualiza os dados cadastrais de um beneficiário com base no ID.

5. **Remoção de um Beneficiário:**
   - Endpoint: `DELETE /api/beneficiarios/deletar/{id}`
   - Remove um beneficiário com base no ID.

## Tecnologias Utilizadas

- Java
- Spring Boot
- Banco de dados H2  
- Front-end em Angular/Typescript

## Processo de Autenticação/Autorização

Não adicionado, apenas um front simples de login.

## Executando o Projeto

1. **Configuração do Banco de Dados:**
   - Configurrado como H2.

2. **Build da Aplicação:**
   - Execute o build do projeto usando Maven.

   ```bash
   mvn clean install
   ```

3. **Executando a Aplicação:**
   - Execute o Springboot.


4. **Executando o Front-end:**
   - Navegue até o diretório do frontend e execute:

   ```bash
   npm install
   ng serve
   ```

5. **Acessando a Aplicação:**
   - Verificação Backend em [http://localhost:8080](http://localhost:8080).
   - Verificação Banco de Dados H2 em [http://localhost:8080/h2](http://localhost:8080/h2).
   - Acesse a aplicação em [http://localhost:4200](http://localhost:4200).

## Autor

- Pedro Sousa Filho
  
