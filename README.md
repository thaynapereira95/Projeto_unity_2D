# 🎮 Jogo de Plataforma 2D - Projeto Prático UniFECAF

## 📝 Descrição do Jogo

Este projeto consiste no desenvolvimento de um jogo de plataforma clássico em duas dimensões (2D), construído na engine Unity. O trabalho foi desenvolvido como avaliação prática para a disciplina de Game Development no Centro Universitário UniFECAF.

O objetivo principal é controlar o personagem através de um cenário repleto de plataformas e desafios, coletando moedas para aumentar a pontuação e superando os inimigos para alcançar a porta final, que garante a vitória e o avanço para a próxima fase.

---

## 🛠️ Mecânicas Criadas e Implementadas

### 🎯 Movimentação do Personagem (PlayerController)

Sistema de movimentação lateral e pulo integrado à física da Unity utilizando `linearVelocity`, proporcionando respostas rápidas aos comandos e uma jogabilidade mais fluida.

### 👾 Combate por Impacto Vertical (Inimigo)

Sistema clássico de eliminação de inimigos. O código verifica a posição da colisão: quando o jogador pula sobre a cabeça do inimigo, ele é destruído e o personagem recebe um impulso para cima. Caso a colisão ocorra pelas laterais, a fase é reiniciada automaticamente.

### 🪙 Coleta de Itens e Interface (HUD)

Moedas distribuídas pelo cenário podem ser coletadas pelo jogador. A cada coleta, o placar é atualizado instantaneamente através do sistema de HUD implementado no Canvas da Unity.

### 🏆 Tela de Vitória Automática (GameManager)

Ao alcançar a porta final da fase, um sensor (Trigger) é ativado. O jogo exibe a mensagem **"VOCÊ VENCEU!"**, pausa o cenário e, após alguns segundos, carrega automaticamente a próxima fase.

---

## 🕹️ Controles do Jogo

| Ação                  | Comando                                     |
| --------------------- | ------------------------------------------- |
| Mover para a Esquerda | ← Seta Esquerda ou Tecla A                  |
| Mover para a Direita  | → Seta Direita ou Tecla D                   |
| Pular                 | Barra de Espaço (Space) ou ↑ Seta para Cima |

---

## 📁 Estrutura de Arquivos do Repositório

Para respeitar os limites de upload do GitHub e evitar o envio de arquivos temporários desnecessários da Unity, o projeto foi organizado da seguinte forma:

### 📦 Assets.zip

Contém:

* Scripts em C#
* Cenas do jogo (.unity)
* Sprites e elementos visuais
* Prefabs e demais recursos utilizados

### ⚙️ ProjectSettings.zip

Contém:

* Configurações da Unity
* Configurações de física
* Inputs e controles
* Build Settings e ordem das cenas

---

## 🚀 Como Executar o Projeto

1. Baixe os arquivos **Assets.zip** e **ProjectSettings.zip** deste repositório.
2. Crie uma pasta vazia no computador (exemplo: **MeuJogoUnity**).
3. Extraia o conteúdo dos dois arquivos `.zip` dentro dessa pasta.
4. Abra o **Unity Hub**.
5. Clique em **Add → Add project from disk**.
6. Selecione a pasta onde os arquivos foram extraídos.
7. Abra o projeto.
8. Na janela **Project**, localize a pasta **Scenes**.
9. Abra a cena **Fase 1**.
10. Clique no botão **Play (▶)** para executar o jogo.

---

## 👨‍💻 Tecnologias Utilizadas

* Unity Engine
* Linguagem C#
* Visual Studio
* Sistema de Física 2D da Unity
* Canvas UI

---

## 🎓 Informações Acadêmicas

**Curso:** Análise e Desenvolvimento de Sistemas
**Disciplina:** Game Development
**Instituição:** UniFECAF
**Tipo de Projeto:** Trabalho Prático Avaliativo

---

## 📌 Objetivos de Aprendizagem

Durante o desenvolvimento deste projeto foram aplicados conceitos relacionados a:

* Programação orientada a objetos em C#;
* Desenvolvimento de jogos 2D na Unity;
* Manipulação de colisões e física;
* Criação de interfaces gráficas (HUD);
* Gerenciamento de cenas;
* Controle de fluxo e progressão de fases.

---

## ✅ Status do Projeto

**Projeto Concluído e Funcional**
