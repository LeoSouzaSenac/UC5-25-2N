# Projeto Prático — English Console Games

## Objetivo

Desenvolver um jogo educativo de inglês utilizando apenas JavaScript no terminal, com entrada de dados através da biblioteca `readline-sync`.

O projeto deve ser totalmente executado no console.

Cada grupo poderá escolher UM dos jogos abaixo para desenvolver.

---

# Regras Obrigatórias

O projeto deve obrigatoriamente:

* Ser desenvolvido em JavaScript
* Utilizar `readline-sync`
* Rodar completamente no terminal
* Possuir sistema de pontuação
* Exibir mensagens organizadas e legíveis
* Possuir no mínimo:

  * 10 perguntas/frases/desafios
  * menu inicial
  * opção de reiniciar
  * feedback de acerto e erro
* Utilizar estruturas de repetição
* Utilizar condicionais
* Utilizar arrays e objetos
* Utilizar funções
* Possuir tratamento básico de entradas inválidas

---

# Jogos Disponíveis

## 1) Quiz Game

### Descrição

O jogador responde perguntas de múltipla escolha sobre tempos verbais em inglês.

### Requisitos

* Exibir pergunta
* Mostrar 4 alternativas
* Informar se acertou ou errou
* Exibir explicação da resposta
* Sistema de pontuação
* Mostrar resultado final

### Exemplo

What is the correct sentence?

A) She go to school
B) She goes to school
C) She going to school
D) She gone to school

---

## 2) Error Detector

### Descrição

O jogador deve encontrar e corrigir erros gramaticais em frases.

### Requisitos

* Mostrar frase incorreta
* Receber frase corrigida pelo usuário
* Comparar respostas
* Informar correção correta
* Sistema de acertos

### Exemplo

Frase:
"He go to work every day."

Resposta correta:
"He goes to work every day."

---

## 3) Build Sentence

### Descrição

O jogador deve reorganizar palavras embaralhadas para formar frases corretas.

### Requisitos

* Embaralhar palavras
* Usuário digita frase organizada
* Validar resposta
* Mostrar resposta correta em caso de erro

### Exemplo

Palavras:
"playing / are / soccer / they"

Resposta:
"They are playing soccer."

---

## 4) Story Mode

### Descrição

Uma história é apresentada e o jogador deve completar os espaços utilizando o tempo verbal correto.

### Requisitos

* História dividida em partes
* Perguntas contextualizadas
* Sistema de progresso
* Pontuação final

### Exemplo

Yesterday I ____ to school.

a) go
b) went
c) going
d) goes

---

## 5) Speed Round

### Descrição

O jogador deve responder rapidamente conjugando verbos corretamente.

### Requisitos

* Temporizador
* Perguntas aleatórias
* Sistema de streak
* Pontuação baseada em velocidade

### Exemplo

Subject: She
Verb: Study
Tempo verbal: Simple Present

Resposta:
studies

---

## 6) Who Wants to Be a Millionaire

### Descrição

Inspirado no Show do Milhão.

### Requisitos

* Perguntas em níveis de dificuldade
* Sistema de prêmios
* 3 ajudas:

  * eliminar alternativas
  * ajuda da plateia
  * ligar para um amigo
* Sistema de progressão

### Exemplo

Pergunta de nível 1 → vale R$100
Pergunta de nível 10 → vale R$100.000

---

# Bibliotecas Permitidas

Apenas:

```bash
npm install readline-sync
```

---

# Desafios Extras (Opcional)

Os grupos que implementarem funcionalidades extras poderão receber bônus.

## Sugestões

* Ranking
* Salvamento de progresso
* Sons no terminal
* Sistema de níveis
* Dificuldade progressiva
* Animações com texto
* Multiplayer local
* Banco de perguntas aleatórias

---

# Entrega

O grupo deverá entregar:

* Pasta do projeto
* Código-fonte completo
* Arquivo README.md explicando:

  * como executar
  * integrantes
  * regras do jogo

---

# Execução

O projeto deverá rodar com:

```bash
node main.js
```



