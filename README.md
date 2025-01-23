# Loja de Imóveis - FuturesX

## Introdução

A Futurex é uma empresa especializada no aluguel de imóveis, como casas, apartamentos e kitnets. Este repositório documenta o projeto desenvolvido para criar um sistema integrado que facilite a gestão e o acesso às informações dos imóveis da empresa.

## Objetivo do Projeto

O objetivo do sistema, desenvolvido como trabalho acadêmico, é permitir à Futurex gerenciar de forma eficiente os imóveis disponíveis e alugados. As funcionalidades principais incluem:

- Cadastro, consulta, atualização e remoção de imóveis.
- Gerenciamento de aluguéis.
- Sistema de autenticação para usuários.

## Funcionalidades

### Imóveis

- **Cadastro de imóveis**: Permite adicionar novos imóveis ao sistema.
- **Consulta de imóveis**: Lista imóveis cadastrados.
- **Atualização de imóveis**: Modificações nas informações de imóveis.
- **Remoção de imóveis**: Exclui imóveis do sistema.

### Aluguéis

- **Cadastro de aluguéis**: Cria contratos de aluguéis.
- **Consulta de aluguéis**: Visualiza contratos existentes.
- **Atualização de aluguéis**: Alterações nos contratos.
- **Encerramento de aluguéis**: Finaliza contratos.

### Autenticação de Usuários

- **Sistema de login**: Controle de acesso seguro.
- **Gestão de usuários**: Gerenciamento dos dados de login.

## Arquitetura do Sistema

### Diagrama de Classes (UML)

![image](https://github.com/user-attachments/assets/db9c0cf3-d743-4a8f-8275-20e0b18d61fd)

## Requisitos

### Requisitos Funcionais

- **RF01**: Cadastro de imóveis.
- **RF02**: Consulta de imóveis.
- **RF03**: Atualização de imóveis.
- **RF04**: Remoção de imóveis.
- **RF05**: Cadastro de aluguéis.
- **RF06**: Consulta de aluguéis.
- **RF07**: Atualização de aluguéis.
- **RF08**: Encerramento de aluguéis.
- **RF09**: Sistema de login.
- **RF10**: Gestão de usuários.

### Requisitos Não Funcionais

- **RNF01**: Disponibilidade de 99,9% do tempo.
- **RNF02**: Tolerância a falhas parciais.
- **RNF03**: Operações concluídas em menos de 2 segundos.
- **RNF04**: Utilização de no máximo 75% da CPU.
- **RNF05**: Usuários aprendem a operar o sistema em menos de 1 hora.
- **RNF06**: Interface intuitiva com no máximo 4 cliques para operações principais.
- **RNF07**: Proteção de dados com criptografia.
- **RNF08**: Garantia de integridade dos dados.
- **RNF09**: Autenticação segura.
- **RNF10**: Adaptação para rodar em Windows e Linux.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/caiotelesz/futurex.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd futurex
   ```
3. Instale as dependências do front:
   ```bash
   npm install
   ```
4. Navegue até o diretório do backend e abra pelo IntelliJ IDEA e Execute-o
5. Navegue pelo cmd até achar o diretório do frontend
  ```bash
    cd featurex/front
  ```
6. Inicie o servidor:
   ```bash
   npm start
   ```
7. Acesse a aplicação em (http://localhost:8090) ao BackEnd.
8. Acesse a aplicação em (http://localhost:4200) ao FrontEnd.
