Dining philosophers problem
---------------------------

No código deste repositório fiz uma solução para o problema de sistemas operacionais, envolvendo processos, conhecido como o jantar dos filósofos, além disso tem uma explanação e análise a se verificar, veja a seguir.

Enunciado: "Demonstrar a ocorrencia de deadlock atraves da implementação do banquete dos filósofos. Cada filósofo aguarda um tempo aleatório entre 1 e 10 ms para tentar começar a comer, cada filósofo tenta primeiro pegar o garfo a sua direita e depois o garfo a sua esquerda, e cada filósofo comerá por um tempo aleatório, entre 50 e 100 ms, depois deve liberar seus garfos e o ciclo se repete. Implemento aqui um programa para um número n de filósofos (n <= 5). Verifique a ocorrencia de deadlock na amostragem."

#### Como será a metrica do jantar dos filósofos, um caso muito comum na ciência da computação.
Cinco filósofos silenciosos sentam-se em uma mesa redonda com tigelas de espaguete. Garfos são colocados entre cada par de filósofos adjacentes.

Cada filósofo deve alternadamente pensar e comer. No entanto, um filósofo só pode comer espaguete quando tem garfos esquerdo e direito. Cada garfo pode ser mantido por apenas um filósofo e apenas um filósofo pode usar o garfo apenas se não estiver sendo usado por outro filósofo. Depois que um filósofo individual termina de comer, eles precisam colocar os dois garfos de modo que os garfos fiquem à disposição dos outros. Um filósofo pode pegar o garfo à sua direita ou a esquerda à medida que se tornam disponíveis, mas não pode começar a comer antes de pegar os dois garfos.

Comer não é limitado pelas quantidades remanescentes de espaguete ou espaço estomacal; um suprimento infinito e uma demanda infinita são assumidos.

O problema é como projetar uma disciplina de comportamento (um algoritmo concorrente) tal que nenhum filósofo passará fome; isto é, cada um pode continuar alternando entre comer e pensar, assumindo que nenhum filósofo pode saber quando os outros querem comer ou pensar.



> Veja mais informações aqui https://en.wikipedia.org/wiki/Dining_philosophers_problem
