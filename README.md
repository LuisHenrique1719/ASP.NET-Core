# 🌟 API's - Clean Architecture com DDD

Bem-vindo! 🚀
Esta API foi desenvolvida com **ASP.NET Core** seguindo os princípios de **Clean Architecture** e **Domain-Driven Design (DDD)**, garantindo um código limpo, modular e de fácil manutenção.

---

## 🛠️ Estrutura do Projeto

Este repositório está organizado em camadas bem definidas para separar responsabilidades:

### 1. **Domain**  
Camada central do projeto, contendo:  
- **Entidades**: Modelos de domínio com regras de negócio.  
- **Value Objects**: Representações imutáveis de conceitos do domínio.  
- **Repositórios (Interfaces)**: Contratos para comunicação com a infraestrutura.  

### 2. **Application**  
Camada responsável por:  
- **Use Cases**: Casos de uso do domínio.  
- **Serviços de Aplicação**: Orquestração das regras de negócio.  
- **DTOs**: Transferência de dados entre camadas.  

### 3. **Infrastructure**  
Camada de implementação:  
- **Repositórios**: Integração com banco de dados usando **Entity Framework Core** ou outro ORM.  
- **Configuração**: Implementação de serviços, como autenticação, cache, ou serviços externos.  

### 4. **API (Presentation)**  
Interface da aplicação com o mundo externo:  
- **Controllers**: Exposição de endpoints RESTful.  
- **Middlewares**: Configurações como autenticação e tratamento de erros.  

---

## 🚀 Tecnologias Utilizadas

- **ASP.NET Core**: Framework para APIs modernas e escaláveis.  
- **Entity Framework Core**: ORM para mapeamento objeto-relacional.  
- **AutoMapper**: Mapeamento de objetos entre camadas.  
- **FluentValidation**: Validação de dados de entrada.  
- **Swagger**: Documentação e testes interativos.  
- **MediatR**: Implementação de padrões CQRS.  
- **JWT**: Autenticação segura baseada em tokens.  
- **Docker**: Contêinerização para fácil implantação.

---

## 🛠️ Pré-requisitos

1. **.NET SDK** ([Download aqui](https://dotnet.microsoft.com/download))  
2. **Banco de dados** configurado (ex.: SQL Server, PostgreSQL, etc.)  
3. **Docker** (opcional, mas recomendado para deploy).  

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:  
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

2. Acesse a pasta onde o projeto está localizado:
   ```bash
   cd nome-do-repositorio

3. Configure o arquivo appsettings.json com a string de conexão do banco de dados.

4. Execute os comandos para restaurar os pacotes e rodar o projeto:
   ```bash
   dotnet restore
   dotnet run

---

## 📚 Funcionalidades

✅ Arquitetura limpa e modular baseada em **Clean Architecture** e **DDD**.
✅ Suporte a **CRUD completo** de entidades do domínio.
✅ Documentação interativa da API com **Swagger**.
✅ Autenticação segura usando **JWT**.
✅ Integração com APIs externas e suporte a serviços de terceiros.
✅ Design extensível para fácil adição de novas funcionalidades.

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! 🎉  

Se você encontrou um problema, tem uma ideia para uma nova funcionalidade ou deseja melhorar o código, siga estas etapas para contribuir:

### 📋 Passos para Contribuir

1. **Faça um Fork** deste repositório:  
   Clique no botão **Fork** no canto superior direito da página do repositório.

2. **Clone o repositório Fork para sua máquina local**:  
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
