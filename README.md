# sudoku DIO 

# Sudoku - Java Edition

Um jogo de Sudoku clássico implementado em Java com interface gráfica em Swing.  
Projeto desenvolvido como exercício de aprendizado, cobrindo Collections, Stream API, programação funcional, Git e Swing GUI.

[![Java](https://img.shields.io/badge/Java-21-red?style=for-the-badge&logo=java&logoColor=white)](https://www.java.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

## Visão Geral

Jogo de Sudoku 9×9 com:
- Tabuleiro funcional e validado em tempo real
- Células fixas (pré-preenchidas) e jogáveis
- Botões para: Finalizar jogo, Verificar status e Reset
- Notificações com JOptionPane
- Suporte a múltiplos listeners (NotifierService)
- Integração com BoardService para lógica do jogo

## Capturas de Tela

(Adicione prints aqui depois de rodar o jogo!)

![Tabuleiro em ação](screenshots/gameplay.png)
![Mensagem de vitória](screenshots/win.png)
![Status do jogo](screenshots/status.png)

## Funcionalidades

- **Modo console** (versão inicial)
- **Interface gráfica Swing** completa
- Validação de Sudoku em tempo real (linhas, colunas, blocos 3×3)
- Detecção de erros e status (NON_STARTED, INCOMPLETE, COMPLETE)
- Botões interativos com mensagens de feedback
- Reset do jogo com confirmação

## Tecnologias Utilizadas

- **Java 21** (ou superior)
- **Swing** (javax.swing) para GUI
- Collections Framework + Stream API
- Programação funcional (lambdas, method references)
- Padrões: Observer (NotifierService + EventListener)
- Git para versionamento

## Como Rodar

### Pré-requisitos

- Java 21+ instalado
- IntelliJ IDEA (ou qualquer IDE com suporte a Maven/Gradle)

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/ghaar-a/sudoku.git
   cd sudoku
