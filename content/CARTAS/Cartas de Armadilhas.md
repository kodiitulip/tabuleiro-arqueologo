---
title: "Cartas de Armadilhas"
draft: false
tags:
  - cartas
---
[[Index]]

---
# Armadilhas Comuns

1. **Ande em pares** 🤝:  
	jogue o dado mais uma vez:  
		Se número par -> a armadilha será desativada e o jogador pode avançar uma casa  
		Caso for ímpar -> retorne o número de casas equivalente a metade do valor do dado _(arredondado para baixo)_  

3. **Uma Mão Amiga** ✋:  
	O jogador antes de você deve jogar um dado:  
		Se for acima de 3 -> a armadilha desativará  
		Caso abaixo de 4 -> perderá seu próximo turno  

---
# Maldições

1. **Sorte Reversa** 🍀🔄:  
	Impacto: \[🟥🟥🟥]  
		A partir de agora seus dados serão invertidos:  
		Toda vez que rolar um dado, subtraia o valor de 7  
			_Exemplo:_ 🎲 = 5 -> 7 - 5 = 2 -> _ande 2 casas_  
$$
		f(🎲) = 7 - 🎲
$$
2. **A Fadiga** 😴:  
	Impacto: \[🟩⬛⬛]  
		A partir de agora seus dados serão menores:  
		Toda vez que rolar um dado subtraia 1  
			_Exemplo:_ 🎲 = 5 -> 5 -1 = 4 -> _ande 4 casas_  
$$
f(🎲) = 🎲 - 1
$$

3. **Escavação Insatisfeita** 😔:  
	Impacto: \[🟨🟨⬛]:  
		Toda [[Acampamentos de Escavação]] que encontrar relíquias, o jogador perde uma das relíquias encontradas  
$$
f(🏆) = 🏆 - 1
$$
## Como Quebrar Maldições?

1. Impacto: \[🟩⬛⬛]:
	- Maldições de baixo impacto somem após 3 turnos
	- Maldições de baixo impacto podem ser quebradas imediatamente usando:
		- [[Relíquias da Sorte]], [[Escaravelhos]]
1. Impacto: \[🟨🟨⬛]:
	- Maldições de médio impacto podem ser quebradas imediatamente usando:
		- [[Relíquias da Sorte]], [[Escaravelhos]]
3. Impacto: \[🟥🟥🟥]:
	- Maldições de alto impacto podem ser quebradas imediatamente usando:
		- [[Escaravelhos]]


---
# Especiais

1. [[Cartas de Esfinge]]
