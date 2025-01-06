<div align="left">
    <img src="https://app.dreamslatam.com/img/Dreamscloud_beta_colored.webp" 
         width="40%" 
         align="left" 
         style="margin-right: 15px; margin-bottom: 35px; margin-top: 15px;" />
    <div style="display: inline-block;">
        <h2 style="display: inline-block; vertical-align: middle; margin-top: 0;">Dreams API</h2>
        <p>
            <em><code>❯ Um projeto com múltiplas branches para determinadas clouds</code></em>
        </p>
        <p><!-- Repositório local, sem medalhas de metadados. --></p>
        <p>Construído com as seguintes ferramentas e tecnologias:</p>
        <p>
            <img src="https://img.shields.io/badge/Express-000000.svg?style=flat-square&logo=Express&logoColor=white" alt="Express">
            <img src="https://img.shields.io/badge/Socket.io-010101.svg?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.io">
            <img src="https://img.shields.io/badge/npm-CB3837.svg?style=flat-square&logo=npm&logoColor=white" alt="npm">
            <img src="https://img.shields.io/badge/Mongoose-F04D35.svg?style=flat-square&logo=Mongoose&logoColor=white" alt="Mongoose">
            <img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat-square&logo=HTML5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=JavaScript&logoColor=black" alt="JavaScript">
            <img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat-square&logo=Axios&logoColor=white" alt="Axios">
        </p>
    </div>
</div>
<br clear="left" />

<details>
    <summary>Índice</summary>

- [📍 Visão Geral](#-visão-geral)
- [👾 Funcionalidades](#-funcionalidades)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [🚀 Começando](#-começando)
  - [☑️ Pré-requisitos](#-pré-requisitos)
  - [⚙️ Instalação](#-instalação)
  - [🤖 Uso](#🤖-uso)

</details>
<hr>

## 📍 Visão Geral

<code>❯ A api foi feita para gerenciar usuários, filas e clouds em um só ambiente de execução. </code>

---

## 👾 Funcionalidades

<code>❯ *Endpoints para: login, registro, recuperação, obter informação de usuário, ligar/desligar máquina.*
❯ *Sistema de fila*
❯ *Envio de pin para o IP com sunshine*
❯ *Criar/Encerrar máquinas na Oracle/Azure*
❯ *Limitação de contas criadas por IP*
❯ *Endpoints para o painel de Admin*
❯ *Gerenciar DB*
</code>

---

## 📁 Estrutura do Projeto

```sh
└── Dreams API/
    ├── deploy.txt
    ├── index.js
    ├── package-lock.json
    ├── package.json
    ├── squarecloud.app
    └── src
        ├── Config
        ├── Core
        ├── Events
        ├── Middlewares
        ├── Models
        ├── Queue
        ├── Resources
        ├── Routes
        ├── Server
        ├── Services
        ├── Sockets
        └── utils
```

---

## 🚀 Começando

### ☑️ Pré-requisitos

Antes de começar com o Dreams API, certifique-se de que o ambiente de execução atenda aos seguintes requisitos:

- **Linguagem de Programação:** JavaScript
- **Gerenciador de Pacotes:** Npm

### ⚙️ Instalação

Instale o Dreams API usando um dos métodos abaixo:

**Compilação a partir do código-fonte:**

1. Clone o repositório Dreams API:
```sh
❯ git clone <url>
```

2. Navegue até o diretório do projeto:
```sh
❯ cd <folderName>
```

3. Instale as dependências do projeto:

**Usando `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm install
```

### 🤖 Uso

Execute o Dreams API usando o seguinte comando:

**Usando `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ node index.js


---
```
