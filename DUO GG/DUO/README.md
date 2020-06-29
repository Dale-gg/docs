<h1 align="center">
    <img alt="DUOAPIDocs" title="#delicinhas" src="../../.github/DUO%20GG/duozada-logo.png" width="200px" />
</h1>

<h4 align="center">
  👭 DUO API Docs 📕
</h4>
<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Dale-gg/DUO-DuozadaAPI?style=for-the-badge&logo=appveyor">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Dale-gg/DUO-DuozadaAPI?style=for-the-badge&logo=appveyor">
  
  <a href="https://github.com/Dale-gg/DUO-DuozadaAPI/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Dale-gg/DUO-DuozadaAPI?style=for-the-badge&logo=appveyor">
  </a>

  <a href="https://github.com/Dale-gg/DUO-DuozadaAPI/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/Dale-gg/DUO-DuozadaAPI?style=for-the-badge&logo=appveyor">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?style=for-the-badge&logo=appveyor">
</p>

<p align="center">
  <a href="#-escopo-e-metodologias">📰 Escopo e Metodologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-requisitos-e-regras">🖋 Requisitos e Regras</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-diagramas">📊 Diagramas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-mer">🎲 MER</a>
</p>

<br>

## 📰 Escopo e Metodologias

- Confira todo o escopo e metodologias usadas no nosso projeto lá na nossa [wiki](https://github.com/Dale-gg/DUO-DuozadaAPI/wiki) page. 🤓

## 🖋 Requisitos e Regras

#### Requisitos funcionais

| Requisitos funcionais | Atores  | Descrição                                                                                                                                                                                |
| --------------------- | ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF 1                  | Usuário | O sistema deve permitir que um usuário mantenha o seu perfil.                                                                                                                            |
| RF 2                  | Usuário | O sistema deve permitir que um usuário mantido faça o login na plataforma.                                                                                                               |
| RF 3                  | Usuário | O sistema deve permitir que um usuário recupere sua senha.                                                                                                                               |
| RF 4                  | Usuário | O sistema deve permitir que um usuário possa fazer manutenções na sua conta.                                                                                                             |
| RF 5                  | Usuário | O sistema deve permitir que um usuário mantenha suas melhores jogadas em seu perfil.                                                                                                     |
| RF 6                  | Usuário | O sistema deve permitir que um usuário possa encontrar e detalhar o perfil de outros usuários.                                                                                           |
| RF 7                  | Usuário | O sistema deve permitir que um usuário possa manter um Like no perfil de outros usuários.                                                                                                |
| RF 8                  | Usuário | O sistema deve permitir que um usuário possa manter um Dislike no perfil de outros usuários.                                                                                             |
| RF 9                  | Usuário | O sistema deve permitir que um usuário mantenha um match (Duozada) com outro usuário.                                                                                                    |
| RF 10                 | Usuário | O sistema deve permitir que um usuário mantenha um chat depois de ocorrer um match (Duozada) com outro usuário.                                                                          |
| RF 11                 | Usuário | O sistema deve permitir que um usuário mantenha uma mensagem dentro do chat.                                                                                                             |
| RF 12                 | Usuário | O sistema deve permitir que um usuário desative a sua conta.                                                                                                                             |

#### Regras de negócio

| Regras de Negócio | RF    | Descrição                                                                                                                                                         |
| ----------------- | ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RN 1              | RF 1  | O usuário deverá fazer um primeiro cadastro fornecendo informações básicas, e algumas informações do jogo como, 3 CAMPEÕES que mais joga e 2 ROTAS que mais joga. |
| RN 2              | RF 4  | O usuário só podera fazer edições no seu perfil caso esteja autenticado.                                                                                          |
| RN 3              | RF 5, 6, 7, 8, 9, 10, 11  | O usuário deverá estar logado na aplicação para utilizar os recursos do Duozada.                                                              |
| RN 4              | RF 1  | O usuário não podera cadastrar uma conta com algum email que já tenha sido usado na aplicação                                                                     |
| RN 5              | RF 9  | O usuário só irá conseguir o match (Duozada) com outro usuário, quando os dois tiverem dado Like no perfil um do outro                                            |
| RN 6              | RF 12 | O usuário que tiver o seu status setado como false, não poderá acessar a aplicação                                                                                |

#### Requisitos não funcionais tecnologicos

| Requisitos funcionais não tecnologicos | Descrição                                                                                                         |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| RNFT 1                                 | O banco de dados a ser utilizado terá o padrão objeto-relacional.                                                 |
| RNFT 2                                 | A aplicação irá usar o architectural pattern REST.                                                                |
| RNFT 3                                 | O chat de texto pós match (Duozada) será implementado usando socket.io.                                           |
| RNFT 4                                 | O sistema vai usar a lib dedSec para padronizar respostas para o Client (React)                                   |
| RNFT 5                                 | O sistema vai usar o Docker para fazer a conteinerização de todos os serviços                                     |

## 📊 Diagramas

<b>
  <h3 align="center">
      Casos de uso
  </h3>
</b>

<h1 align="center">
    <img alt="DUOAPIDocs" title="#delicinhas" src="../../.github/DUO%20GG/General%20UseCase%20Diagram.png" width="800px" />
</h1>

<b>
  <h3 align="center">
      Classes
  </h3>
</b>

<h1 align="center">
    <img alt="DUOAPIDocs" title="#delicinhas" src="../../.github/DUO%20GG/General%20Class%20Diagram.png" width="800px" />
</h1>

<b>
  <h3 align="center">
      Sequence
  </h3>
</b>

<h1 align="center">
    <img alt="DUOAPIDocs" title="#delicinhas" src="../../.github/DUO%20GG/General%20Sequence%20Diagram.png" width="800px" />
</h1>

## 🎲 MER

<h1 align="center">
    <img alt="DUOAPIDocs" title="#delicinhas" src="../../.github/DUO%20GG/MER%20Diagram.png" width="800px" />
</h1>

---

Made with 🖤 by [jlenon7](https://github.com/jlenon7) & [Adryell](https://github.com/adryell):wave:
