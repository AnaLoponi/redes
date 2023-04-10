# Experimentos de otimização e algoritmos genéticos 🧬

Olá, você está na pasta de Algoritmos Genéticos.  
Aqui você encontrará todo o desenvolvimento deste eixo da disciplina mencionada no [repositório](https://github.com/AnaLoponi/redes).

### 👩‍💻 Mas, o que são algoritmos genéticos? 
Uma busca rápida no [Wikipedia](https://pt.wikipedia.org/wiki/Algoritmo_gen%C3%A9tico) diz: _"Um algoritmo genético é uma técnica de busca utilizada na ciência da computação e em investigação operacional para achar soluções aproximadas em problemas de otimização e busca. Algoritmos genéticos são uma classe particular de algoritmos evolutivos que usam técnicas inspiradas pela biologia evolutiva como hereditariedade, mutação, seleção natural e recombinação (ou crossing over)"_.

Mas como isso funciona? 👇

### 📓 Guia Rápido
<sub> Arquivos de desenvolvimento .ipynb </sub>

* [Algumas coisas que valem a pena aprender ou relembrar.ipynb](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/Algumas%20coisas%20que%20valem%20a%20pena%20aprender%20ou%20relembrar.ipynb)
> Importações, Funções e Lógica de Programação já mencionadas ou usadas antes, que podem auxiliar o desenvolvimento dos algoritmos genéticos.

* [experimento GA.02 - performance caixas binarias](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/experimento%20GA.02%20-%20performance%20caixas%20binarias.ipynb)
> Comparação de performances para os algoritmos de otimização que já utilizamos nos outros experimentos (busca aleatória, busca em grade e algoritmos genéticos) na resolução do problema das caixas binárias.  
Ainda não desenvolvido.

* [experimento A.01 - busca aleatoria.ipynb](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/experimento%20A.01%20-%20busca%20aleatoria.ipynb)
> O algoritmo de busca aleatória é um certo espaço de busca, em que definimos de onde sorteamos candidatos de soluções para o problema.
Utilizando o problema das caixas binárias, temos um número aleatório de caixas, que só podem ser preenchidas com 0 e 1. Sendo assim, o objetivo é encontrar uma combinação de caixas que, ao serem somadas, atingem o valor máximo. Temos um problema de Maximização! 

* [experimento A.02 - busca em grade.ipynb](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/experimento%20A.02%20-%20busca%20em%20grade.ipynb)
> Ainda refletindo no problema das caixas binárias, utilizamos o método de busca em grade, que basicamente testa todas as combinações possíveis por meio de alguns parâmetros definidos (como um filtro).
Desse modo, podemos esquematizar as vantagens e desvantagens de cada modelo de busca.

* [experimento A.03 - algoritmo genetico.ipynb](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/experimento%20A.03%20-%20algoritmo%20genetico.ipynb)
> Agora que entendemos o método proposto nos exercícios anteriores, é necessário criar um modelo para otimizar os processos de busca. Por isso, utilizamos algoritmos genéticos, em que geramos uma população aleatória e por meio da seleção, cruzamento e mutações, geramos novas populações, assim como Darwin propôs.
Ainda utilizando as caixas binárias, vamos otimizar este problema!

* [experimento A.04 - caixas nao-binarias.ipynb](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/experimento%20A.04%20-%20caixas%20nao-binarias.ipynb)
> Novo desafio: E se a caixas, não contivessem apenas 0 e 1? E se esses conteúdos são tão desconhecidos, que nem conseguimos se aproximar de um resultado real? Como usar algoritmos genéticos nesse casos?  
Lembre-se: ainda devemos encontrar o valor máximo da soma dessas caixas!

* [experimento A.05 - descobrindo a senha.ipynb](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/experimento%20A.05%20-%20descobrindo%20a%20senha.ipynb)
> Como utilizar algoritmos genéticos para descobrir senhas? Neste caso, a lógica não foi perto do real, pois, a função objetivo já teria a senha informada e desse modo calcularia a distância de seus "chutes" até encontrar a senha correta. Vale a pena tentar ;)

* [experimento A.06 - o caixeiro viajante.ipynb](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/experimento%20A.06%20-%20o%20caixeiro%20viajante.ipynb)
> O problema do caixeiro viajante define-se em visitar uma lista de cidades, passando por cada uma apenas uma vez e ainda, utilizando o menor caminho possível (já sabemos que este é um problema de minimização). Ao terminar de visitar todas as cidades, ele retorna ao ponto de origem, esse é o critério de parada. Mas, para utilizar algoritmos genéticos devemos modificar algumas das funções. Vem descobrir!

<sub> Arquivos .py </sub>
* [funcoes.py](https://github.com/AnaLoponi/redes/blob/main/AlgoritmosGeneticos/funcoes.py)
> Armazenamento de funções para o uso em diversos notebooks.

* classes.py
> Ainda não desenvolvido.

* constantes.py
> Ainda não desenvolvido.

<sub> README.md </sub>
> Onde estão armazenadas todas as informações que você acabou de ler ✔️
