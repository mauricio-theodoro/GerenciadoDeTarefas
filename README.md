# Gerenciador de Tarefas 📝

**Gerenciador de Tarefas** é uma aplicação robusta e intuitiva desenvolvida para gerenciar tarefas de maneira eficiente. Com funcionalidades como criação, edição, exclusão, marcação de tarefas como concluídas e persistência de dados usando o MongoDB, esta aplicação é ideal para quem deseja otimizar a organização de suas atividades diárias.

---

## 🚀 Funcionalidades

- **Cadastro de Tarefas**: Adicione novas tarefas com título, descrição e data de vencimento.
- **Visualização das Tarefas**: Interface fácil de usar para visualizar todas as tarefas cadastradas, com opções de filtro.
- **Marcar como Concluída**: Permite atualizar o status de uma tarefa para concluída com um simples clique.
- **Edição de Tarefas**: Editar qualquer tarefa existente, atualizando título, descrição e data de vencimento.
- **Excluir Tarefas**: Remova tarefas que não são mais necessárias.
- **Banco de Dados MongoDB**: Armazenamento escalável e altamente disponível de todas as tarefas no MongoDB.

---

## 🛠 Tecnologias Utilizadas

- **Backend**: [Spring Boot](https://spring.io/projects/spring-boot)
- **Banco de Dados**: [MongoDB](https://www.mongodb.com/)
- **Bibliotecas**:
  - [Spring Data MongoDB](https://spring.io/projects/spring-data-mongodb)
  - [Spring Web](https://spring.io/projects/spring-framework)
  - [Lombok](https://projectlombok.org/)

---

## 📦 Pré-requisitos

Antes de rodar o projeto, você precisará das seguintes ferramentas instaladas:

- [Java 11 ou superior](https://adoptopenjdk.net/)
- [MongoDB](https://www.mongodb.com/try/download/community) ou [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) para usar o banco de dados na nuvem.
- [Maven](https://maven.apache.org/) para compilar o projeto.

---

## 🚧 Instalação e Execução

### Passo 1: Clonar o Repositório

```bash
git clone https://github.com/mauricio-theodoro/GerenciadoDeTarefas.git
cd GerenciadoDeTarefas
