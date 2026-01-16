# 📘 Assignment: Jogos em Python — Hangman

## 🎯 Objetivos

Neste exercício o estudante vai construir o clássico jogo da forca (Hangman) usando strings, laços e entrada do usuário em Python. O foco é praticar manipulação de strings, condicionais e lógica de jogo.

## 📝 Tarefas

### 🛠️ Criar o jogo Hangman

#### Description
Implemente um jogo da forca que permita ao jogador adivinhar letras para revelar uma palavra oculta antes que as tentativas se esgotem. O jogo deve ser jogável via terminal e fornecer feedback claro sobre o progresso.

#### Requirements
Completed program should:

- Selecionar palavras aleatoriamente a partir de uma lista pré-definida.
- Aceitar palpites de letras e exibir o estado atual da palavra no formato `_ _ a _ _`.
- Rastrear e exibir a quantidade de tentativas incorretas restantes.
- Terminar quando a palavra for completamente adivinhada ou as tentativas terminarem.
- Exibir mensagens de vitória ou derrota apropriadas.

#### Exemplo de execução

Entrada do usuário (exemplo):

```
Guess a letter: a
Guess a letter: e
```

Saída esperada (parcial):

```
Word: _ a _ _ _
Incorrect guesses left: 5
```

---

Se desejar, inclua um arquivo `starter-code.py` com funções auxiliares para seleção de palavra e exibição do estado do jogo.
