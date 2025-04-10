# Projeto API Alunos
A API contida neste repositório disponibiliza recursos de:
- Listar alunos
- Salvar um aluno

## Stack utilizada:
- Java (JDK 17)
- Springboot (Serviço Web)
- MongoDB (Banco de dados NOSQL)
- Swagger (Documentação da API)

## Requerimentos para rodar:
- Java versão 17+
- IDE de sua preferência
- MongoDB server e algum GUI para visualização dos dados
> [!WARNING]
> Para rodar o projeto é necessário estar rodando o serviço do mongoDB em seu computador.
> Caso não tenha instalar seguindo o passo a passo para seu sistema operacional no próprio site do mongoDB: [Documentação Oficial MongoDB](https://www.mongodb.com/try/download/community)

## Como instalar:
- Clonar este repositório em algum diretório de sua preferência: `git clone https://github.com/gustavoc0imbra/apialunos/tree/main`
- Abrir em sua IDE de preferência e rodar.

> [!NOTE]
> A API vai ser disponibilizada no endereço `http://localhost:8080/`  
> A documentação dos endpoints disponibilizados estará em `http://localhost:8080/api-docs`

## Frontend que consome esta API:
O repositório do projeto que consome esta API e exibe de uma forma mais interativa os dados salvos nesta aplicação é: [Frontend Alunos](https://github.com/gustavoc0imbra/frontalunos)
