# project-Dart
## rock, paper and scissors 🎮

This project was made through this [video](https://www.youtube.com/watch?v=XoZ01mY-cUg&t=2s)
Level: basic
- Which is?
This is a game with two players, the user and the machine.
 It consists of each one choosing  🪨 rock, 📰 paper or ✂️ scissors
---
  program logic:
If Player1 == rock && Player2 == scissors: Player2 win 
If Player1 == paper && Player2 == pedra: Player1 win
If Player1 == scissors && Player2 == paper: Player1 win
If Player1 == Player2: draw 


---

**O que foi usado nesse código:**
* if else
* while
* comandos de entrada e saída **stdin**
* gerador de números aleatórios **Random**

About 
- if else:
estruturas que direcionam o fluxo de execução do código

- while:
Estrutura de repetição com teste no início
(break: dá fim á repetição)

- stdtin
The standard input stream of data read by this program.
Stdin get stdin {
  return IOOverrides.current?.stdin ?? _stdin;
}

- Random
external factory Random([int? seed]);

  Creates a cryptographically secure random number generator
  If the program cannot provide a cryptographically secure
  source of random numbers, it throws an [UnsupportedError].



