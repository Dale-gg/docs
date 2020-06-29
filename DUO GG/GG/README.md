<h1 align="center">
    <img alt="GGAPIDocs" title="#delicinhas" src="../../.github/DUO%20GG/dalegg-logo.png" width="200px" />
</h1>

<h4 align="center">
  🎮 GG API Docs 📕
</h4>
<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Dale-gg/GG-Dale.ggAPI?style=for-the-badge&logo=appveyor">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Dale-gg/GG-Dale.ggAPI?style=for-the-badge&logo=appveyor">
  
  <a href="https://github.com/Dale-gg/GG-Dale.ggAPI/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Dale-gg/GG-Dale.ggAPI?style=for-the-badge&logo=appveyor">
  </a>

  <a href="https://github.com/Dale-gg/GG-Dale.ggAPI/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/Dale-gg/GG-Dale.ggAPI?style=for-the-badge&logo=appveyor">
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

- Confira todo o escopo e metodologias usadas no nosso projeto lá na nossa [wiki](https://github.com/Dale-gg/docs/wiki) page. 🤓

## 🖋 Requisitos e Regras

#### Requisitos funcionais

| Requisitos funcionais |   Atores           | Descrição                                                                                                                                                                                         |
| --------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF 13                 | Usuário, Invocador | O sistema deve permitir que um usuário pesquise por Invocadores dentro da aplicação.                                                                                                              |
| RF 14                 | Usuário, Invocador | O sistema deve permitir a visualização do histórico de partidas assim como todas as informações de cada uma.                                                                                      |
| RF 15                 | Usuário, Invocador | O sistema deve permitir a visualização do histórico de um jogador em relação as partidas jogadas: total de partidas, total vitórias, total derrotas.                                              |
| RF 16                 | Usuário, Invocador | O sistema deve permitir a visualização do histórico de um jogador em relação aos campeões jogados: campeão mais jogado, campeão menos jogado, campeão com melhor índice de vitória.               |

#### Regras de negócio

| Regras de Negócio | RF   | Descrição                                                                                                                                                         |
| ----------------- | ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RN 7              | RF 13, 14, 15, 16 | O usuário não podera fazer requisições a API da Riot se não estiver autenticado.                                                                     |
| RN 8              | RF 13 | O usuário deve fazer as requisições a API da Riot pelo nome de algum Invocador e região apenas.                                                                   |
| RN 9              | RF 13, 14, 15, 16 | O usuário podera atualizar o perfil de algum Invocador, para refazer a requisição a API da Riot.                                                                  |

#### Requisitos não funcionais tecnologicos

| Requisitos funcionais não tecnologicos | Descrição                                                                                                         |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| RNFT 6                                 | Um script será criado para realizar um pré cadastro dos Campeões e Lanes na aplicação.                            |
| RNFT 7                                 | O sistema deve fazer uso da API da Riot Games para buscar as informações dos Invocadores.                         |
| RNFT 8                                 | O sistema vai usar a lib ZedJS para fazer request a API da Riot Games                                             |
| RNFT 9                                 | O sistema vai usar o pattern Observable para lidar com o cadastro de Summoners                                    |

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

Feito com 🖤 por [jlenon7](https://github.com/jlenon7) & [Adryell](https://github.com/adryell):wave:
