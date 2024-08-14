
# Fórum de Perguntas e Respostas

Bem-vindo ao repositório do backend para o fórum de perguntas e respostas. Este projeto é desenvolvido para fornecer uma solução robusta e escalável para a criação e gerenciamento de um fórum online.

## Descrição do Sistema

Este sistema é um backend para um fórum de perguntas e respostas, projetado para ser modular, escalável e de alta qualidade. Abaixo estão os detalhes das tecnologias e práticas utilizadas:

- **TypeScript** 🦔: Linguagem de programação que traz tipagem estática ao JavaScript, aumentando a robustez e a manutenção do código.
- **Node.js** 🌐: Ambiente de execução que permite construir aplicações rápidas e escaláveis.
- **NestJS** 🏛️: Framework para construção de aplicações eficientes e escaláveis, baseado em TypeScript.
- **Domain-Driven Design (DDD)** 📘: Abordagem de design que foca em criar um modelo de domínio rico e alinhado com as necessidades do negócio.
- **Clean Architecture** 🧱: Padrão arquitetural que promove uma separação clara entre as diferentes camadas da aplicação.
- **PostgreSQL** 🗃️: Sistema de gerenciamento de banco de dados relacional robusto e confiável.
- **TypeORM** 🔄: Biblioteca ORM para TypeScript e JavaScript, facilitando a interação com o banco de dados e a gestão de migrações.
- **Pub/Sub** 🔊: Padrão de comunicação assíncrona para garantir que diferentes partes do sistema possam se comunicar de forma eficiente.
- **Test-Driven Development (TDD)** 🧪: Prática de desenvolvimento que assegura a qualidade do código por meio de testes rigorosos.
- **Docker** 🐋: Plataforma de containerização que garante um ambiente de desenvolvimento e produção consistente e confiável.

## Funcionalidades

- **Criação e Gerenciamento de Perguntas e Respostas**: Permite aos usuários criar, editar e excluir perguntas e respostas no fórum.
- **Moderação e Administração**: Funcionalidades para moderar conteúdo e gerenciar usuários.
- **Comunicação Assíncrona**: Utiliza Pub/Sub para atualizar partes do sistema de forma eficiente.
- **Ambiente Consistente**: Docker garante que o ambiente de desenvolvimento e produção seja o mesmo.

## Como Começar

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/feh-franc0/nest-clean
   ```

2. **Instale as Dependências**

   Navegue até o diretório do projeto e execute:

   ```bash
   pnpm install
   ```

3. **Configure o Ambiente**

   Crie um arquivo `.env` com as variáveis de ambiente necessárias. Consulte o arquivo `.env.example` para detalhes.

4. **Inicie o Projeto**

   Execute o comando:

   ```bash
   pnpm run start:dev
   ```

5. **Executar Testes**

   Para rodar os testes, use:

   ```bash
   pnpm run test
   pnpm run test:e2e
   ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, fazer pull requests ou sugerir melhorias.


## 🎁 Expressões de gratidão

* Conte a outras pessoas sobre este projeto 📢;
* Agradeça publicamente 🫂;

---

⌨️ Por: [Fernando Franco](https://www.linkedin.com/in/fernandofrancovalle/) 😊
