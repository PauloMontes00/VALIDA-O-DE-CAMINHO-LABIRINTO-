# VALIDA-O-DE-CAMINHO-LABIRINTO-
Um sistema de navegação de robôs autônomos registra os movimentos realizados dentro de um labirinto, por meio de uma sequência de caracteres, como forma de conhecer o ambiente. Cada caractere representa um movimento em uma direção:

N → Norte<br>
S → Sul<br>
L → Leste<br>
O → Oeste<br>

<img width="374" height="251" alt="image" src="https://github.com/user-attachments/assets/d762389d-3305-4d50-a279-a0f1f121a1b1" />

Dois movimentos são considerados opostos se anulam diretamente. Observe que na imagem tem apenas o caminho de ida, onde a volta deveria ser o mesmo percursso.

Um caminho é considerado válido (retorna à origem) quando, após considerar todos os cancelamentos possíveis entre movimentos opostos consecutivos, nenhum movimento restante permanece. Ou seja, o robô terminou exatamente no ponto de partida.

Exemplo:

 
Entrada: N S L O → válido<br>
Entrada: N N S → inválido<br>
Entrada: N N S S → válido<br>
Entrada: L S L S O S L L O O N L N O N O →  ??<br>

