# project-Dart
## rock, paper and scissors 🎮

Este projeto foi feito através deste [video](https://www.youtube.com/watch?v=XoZ01mY-cUg&t=2s)

- O que é?
Este é um jogo com dois jogadores, o usuário e a máquina
Consiste em cada um escolher 🪨 pedra, 📰 papel ou ✂️ tesoura
---
Se jogador1 == pedra && jogador2 == tesoura: jogador1 win 
SE jogador1 == papel && jogador2 == pedra: jogador1 win
Se jogador1 == tesoura && jogador2 == papel: jogador1 win
Se jogador1 == jogador2: draw 


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



