# GVCode Challenge
Olá!

Se você chegou até aqui parabéns tripulante! Nós já entendemos que você tem um interesse por **programação** e **data science**, por isso agora queremos ver como você aprende e se desenvolve enfrentando desafios.

Então, aqui você vai encontrar tudo o que você precisa para essa fase do processo. Nós dividimos esse documento em três partes:, como vai ser a **estrutura do desafio**,  **opções de challenges** para você escolher e conteúdo para **aprender o básico de programação.** 

E aí, topa fazer parte desse desafio?

![enter image description here](https://media.giphy.com/media/QxZ0nbcVgMlPlnfZos/giphy.gif)
## Estrutura do desafio
Primeiramente, gostaríamos de deixar bem claro que nós não exigimos **NENHUM** conhecimento prévio de programação. 

Nós acreditamos que com dedicação qualquer pessoa pode aprender qualquer coisa. E mais do que isso, programação não é algo que você aprende simplesmente vendo aulas, **você precisa pôr em prática!**

> "É fazendo que se aprende a fazer aquilo que se deve aprender a fazer."
> -Aristóteles

Por isso, o nosso desafio nessa segunda fase do GVCode é um desafio prático de consiste de quatro passos:

 1. Olhar a lista de projetos disponíveis e **escolher um**
 2. Reunir-se em **até duas pessoas** para resolver o case
 3. **Estudar** o necessário para resolver o desafio
 4. **Enviar até 21/03** o arquivo do desafio por e-mail no gvcodemaster@gmail.com

Bem simples, não? Ah, no final nós vamos te dar algumas dicas e guidelines sobre como resolver os desafios.

## Opções de Challenges
Você pode escolher qualquer uma das seguintes opções de challenge:

### **1. Calculadora Aritmética**

![Calculadora Aritmética](https://intellipaat.com/blog/wp-content/uploads/2020/11/image005.png)

Esclarecer os conceitos fundamentais de qualquer linguagem de programação é crucial ao começar com projetos Python para iniciantes. Uma calculadora pode ser o projeto básico mais comum para qualquer idioma, mas o objetivo é entender como funciona o fluxo de trabalho do idioma. Ao fazer uma calculadora simples, você terá uma ideia de como os operadores básicos do Python funcionam, o fluxo de trabalho de entrada / saída, os tipos de dados do Python e a sintaxe básica do Python. Também é recomendável criar casos de teste manualmente para entender as restrições e verificar a funcionalidade de seu aplicativo de calculadora. Definitivamente, você deve começar com isso como um de seus primeiros projetos Python.

### **2. Programa de reversão de string**

Este programa exigirá que você pegue uma entrada de string (matriz de caracteres) de um usuário e reorganize a string na ordem inversa, exibindo a saída para o usuário. A primeira abordagem óbvia será simplesmente inverter todos os caracteres da string, mas você pode aprimorar ainda mais este projeto alterando vários atributos do programa:

-   Pegue uma frase como entrada e inverta cada palavra na frase, mantendo as posições das palavras iguais
-   Pegue uma frase como entrada e inverta a ordem em que as palavras aparecem, sem alterar o conteúdo das próprias palavras

Da mesma forma, muitas outras variações de manipulação de strings podem ser implementadas nesta atribuição. No final dele, você pode até mesmo criar um programa baseado em menu onde os usuários podem selecionar que tipo de manipulação de string desejam executar em suas entradas fornecidas.


### **3. Jogo de adivinhação de números**

Considere este projeto como uma introdução ao uso de funções em Python. Pegue um número inicial e um número final de um jogador e gere um número aleatório entre essas duas restrições. O objetivo do jogo é que o jogador adivinhe o número que foi gerado aleatoriamente. A pontuação final do jogador será determinada pelo número de tentativas que o indivíduo levou para chegar à resposta correta. Quanto menor for o número de tentativas, maior será o valor da pontuação. A cada palpite errado, uma dica será fornecida ao jogador, informando se ele está acima do número, abaixo do número ou se o número é um múltiplo da resposta adivinhada incorretamente.

Opcionalmente, você pode criar uma função que recebe dois números e gera um número aleatório entre eles para implementar seu caso de uso. Outras funções também podem ser criadas para fins de sugestão e comparação.

### **4. Jogos baseados em escolha**

Você pode colocar suas habilidades de raciocínio condicional fazendo algo incrivelmente divertido, mas como? Sem o uso de qualquer interface de usuário ou mecanismo gráfico complexo, você pode desenvolver um jogo que simplesmente solicite que o jogador selecione opções baseadas em texto para progredir ainda mais no jogo. Você tem a opção de tornar este jogo o mais eficiente possível com vários finais com base nas escolhas feitas pelo jogador ao longo de sua experiência de jogo. Para evitar esforços desnecessários, você pode reutilizar o código e modularizar e planejar adequadamente seu gráfico para minimizar redundâncias.

Para dar um passo adiante e adicionar movimentos reais em seu jogo, você também pode usar grades de matriz 2D para implementar ambientes de jogo ou mapas. Você pode acompanhar onde o jogador está por suas escolhas de movimento, apontando o jogador em uma posição particular na grade da matriz. Obstáculos, inimigos e outros itens de jogo podem ser colocados estrategicamente na grade para o jogador correr ou pegar, para adicionar mais elementos dinâmicos ao seu jogo. Você também pode programar os movimentos do inimigo para tornar o jogo ainda mais desafiador.

Trabalhar com arrays 2D pode ser extremamente útil quando você lida com projetos de programação de nível de indústria maiores, onde você pode ter que ser proficiente em trabalhar e manipular arrays multidimensionais.

### **5. Adivinhe a palavra / Hangman**

Nas ideias de projetos básicos do Python, Hangman é um dos jogos populares em que uma palavra é escolhida pelo jogador adversário ou pelo programa, e o jogador tem todo o conjunto de alfabeto disponível para adivinhar as letras. A palavra alvo será exibida com a maioria das letras faltando. É tarefa do jogador escolher os alfabetos com base em uma dica associada à palavra. Se a letra estiver correta, todas as ocorrências possíveis dessa letra em particular serão preenchidas nos respectivos espaços em branco. Se a estimativa estiver incorreta, a contagem de tentativa aumentará e a letra adivinhada será riscada no banco do alfabeto disponível. O número de tentativas não será ilimitado, é claro. Tradicionalmente, seis suposições erradas são permitidas antes que o jogador perca o jogo,

### **6. Pedra, Papel, Tesoura**

![Pedra Papel Tesoura](https://intellipaat.com/blog/wp-content/uploads/2020/11/Rock-Paper-Scissors.png)

Rock, Paper, Scissors é um jogo conhecido para usar em seus projetos Python. Existem muitas maneiras de implementar este jogo em código com base em seu conhecimento de Python. Devido ao elemento aleatório anexado ao jogo, você obviamente terá que usar uma função aleatória para determinar a mão de cada jogador. Você pode começar a desenvolver este jogo com um oponente padrão da CPU e com movimentos aleatórios, e então, você pode aumentar o nível de complexidade criando uma opção para dois jogadores humanos irem um contra o outro. De qualquer forma, o fator criativo envolvido no design do jogo permitirá uma tonelada de flexibilidade em sua abordagem. Certifique-se de adicionar opções para novas tentativas e rastreamento de pontuação para aprimorar a experiência geral.

### **7. Gerador de número de Fibonacci**

A série matemática conhecida como série Fibonacci tem sido uma das questões de codificação mais populares na comunidade de programação. Essencialmente, você começa com dois números, de preferência 0 e 1, e os adiciona para criar seu terceiro número de Fibonacci. A partir daí, você simplesmente vai somando a soma e o penúltimo termo de Fibonacci para gerar o próximo.

Neste projeto, você pede a posição do número de Fibonacci exigido pelo usuário e simplesmente o gera. Uma vez gerado, você pode exibir a saída desejada para o usuário. Você pode dar um passo adiante e mostrar ao usuário toda a série até aquele ponto com o funcionamento matemático dela também. Este é um dos melhores projetos Python para se apresentar ao conceito da função recursiva.

### **8. Calculadora de dias**
A premissa deste aplicativo é relativamente direta. Você deve criar um programa que tenha duas datas como entrada: uma data de início e uma data de término. Assim que a entrada for recebida, o programa continuará a calcular o número de dias entre essas duas datas e fornecerá o resultado ao usuário. Você pode obter as datas de entrada no formato DD-MM-AAAA e extrair os parâmetros relevantes da string mencionada.

Este programa pode ser uma tarefa desafiadora para iniciantes e é um dos projetos Python altamente recomendados para esclarecer quaisquer dúvidas fundamentais com relação a matrizes e instruções if-elif-else. O verdadeiro desafio da resolução de problemas surge quando você tem que contabilizar a diferença de dias em meses diferentes e quando chega um ano bissexto.

### **9. Classificando uma lista de elementos**

A otimização de um programa é extremamente importante no desenvolvimento. Esta etapa ajuda a conservar os recursos computacionais ao executar aplicativos, tornando-os mais rápidos sem diminuir a velocidade de outros processos no computador. Uma dessas tarefas de otimização, frequentemente solicitada também em entrevistas de emprego, é chamada de 'classificação'. A classificação é implementada em programas de muitas formas e formatos e também tem diferentes complexidades de tempo.

O objetivo deste programa será pegar uma lista Python como entrada e classificá-la em ordem crescente ou decrescente se for uma lista numérica ou em ordem alfabética se for um array de caracteres ou uma lista de palavras. Você deve ter em mente que Python é uma linguagem de alto nível em comparação com outras linguagens de programação, e já possui várias funcionalidades embutidas. É altamente recomendável para o desenvolvimento de suas habilidades codificar a função de classificação sozinho e não depender da função de classificação que o Python fornece.

### **10. Jogo da velha**

![Jogo da velha](https://intellipaat.com/blog/wp-content/uploads/2020/11/Tic-Tac-Toe.png)

Tic-Tac-Toe é um jogo muito comum e fácil de jogar, jogado extensivamente em notebooks. A premissa do jogo é simples. É um jogo baseado em turnos, onde o objetivo é alinhar uma trifeta de círculos ou cruzes na diagonal, horizontal ou vertical em uma grade quadrada 3 × 3 para alcançar a vitória.

O desafio na criação deste jogo reside principalmente em se familiarizar com a indexação de array 2D e descobrir como verificar alinhamentos diagonais. Uma vez que isso seja resolvido, a codificação deve ser simplificada.

### **11. Pesquisa Binária**

Após a classificação, a pesquisa é outra parte do gerenciamento de listas, que está sujeita a rotinas de otimização. Existem certas abordagens para pesquisar um elemento em uma lista. Existem até estruturas de dados baseadas na arquitetura de valor-chave para tornar essas pesquisas instantâneas. Um dos algoritmos de pesquisa mais eficientes é o algoritmo de 'pesquisa binária'. O pré-requisito é que a entrada para esse algoritmo de pesquisa já esteja classificada. A pesquisa binária corta a área de pesquisa pela metade em cada iteração do loop, tornando-a econômica.

Neste projeto, você precisa criar um aplicativo que peça ao usuário para inserir uma lista na ordem de classificação e um elemento de pesquisa. Se a lista não estiver classificada, você deve, primeiro, implementar um algoritmo de classificação você mesmo e, em seguida, realizar a pesquisa binária na lista para o elemento de pesquisa. Seu programa deve exibir a posição do elemento de pesquisa, se encontrado, e deve notificar o usuário se o elemento não for encontrado na lista Python.

### **12. Contando a frequência de cada elemento único em uma lista**

Depois de adquirir familiaridade com as listas Python, este projeto específico não deve ser tão difícil. Você deve obter uma lista como entrada de um usuário e descobrir a contagem de cada elemento exclusivo nela. Há muito espaço para otimização de tempo aqui, junto com muita flexibilidade nas abordagens que você pode adotar para resolver esse problema. Lembre-se de que qualquer método que evite percorrer a lista inteira em cada iteração é preferido aqui.

### **13. Registro do usuário**

Depois de entender as listas, a próxima etapa é entender outra estrutura de dados chave, chamada de dicionários Python. Com dicionários, você pode implementar facilmente programas que tenham funcionalidade de banco de dados. Dicionários são estruturas de dados com arquitetura NoSQL baseada em valores-chave e são ideais como objetos, que armazenam registros que precisam ser consultados.

Seu aplicativo deve ter vários nomes, números de contato e idades como entrada e armazená-los em um dicionário. Opcionalmente, você pode incluir utilitários de terceiros como o SQLite para armazenar a entrada de forma mais permanente em bancos de dados ou em arquivos JSON se quiser aumentar a utilidade do seu programa.

### **14. Impressora de padrões**

Em projetos Python para iniciantes, os programas de impressão de padrões são uma ótima maneira de testar as habilidades de design de loops aninhados. Basicamente, tudo o que você precisa fazer é imprimir o texto de tal forma, usando loops, que eles se assemelhem a padrões simétricos.

Por exemplo, um padrão se parece com este:

1 12 123 1234

Agora, se um usuário inserir o número 4, você precisará imprimir quatro linhas do padrão acima. Você também pode tentar outros padrões e criar um programa baseado em menu que pergunta aos usuários qual padrão eles desejam imprimir.

### **15. Teste**

![Questionário](https://intellipaat.com/blog/wp-content/uploads/2020/11/Quiz.png)

Neste projeto, você terá que criar um banco de questões com múltiplas escolhas para cada questão e então implementar um sistema de pontuação para os jogadores que tentarem o quiz. Tente armazenar a pontuação de cada jogador usando um arquivo ou banco de dados ao final de cada tentativa de questionário.

## Material de Estudos e Dicas
Agora que você já escolheu o seu desafio, está na hora de estudar e aprender sobre python!
Aqui a gente separou alguns materiais em português e inglês para te ajudar com esse desafio:

### Materiais

 - **Instalando Python:** https://www.youtube.com/watch?v=VuKvR1J2LQE
 -  **Aprenda Python em 10 min**:https://www.youtube.com/watch?v=Q8eajxcS6dQ
	 - Nesse curso ele vai codar usando um site para te ajudar a aprender
 - **Curso básico de Python:** https://www.youtube.com/watch?v=rfscVS0vtbw
	 - Em inglês com legendas em português ou inglês
 - **Curso intensivo de Python:** https://www.youtube.com/watch?v=GPVsHOlRBBI 
	 - Em inglês com legendas em português ou inglês
	 - Ele é um curso de 10h beeeeem completo que também ensina sobre numpy e pandas
- **Documentação Python:** https://docs.python.org/pt-br/3/tutorial/index.html
	- A referência básica da linguagem se encontra aqui

### Dicas
- Nós somos uma entidade **colaborativa**, isso quer dizer que não tem ninguém competindo com você. Ou seja, não temos limites de vagas e a sua candidatura não é comparativa. Então, se você apresentar bons resultados no case e estiver alinhado com a cultura do GVCode, você ta dentro. 
- Por isso, estimulamos fortemente que **vocês colaborem entre si**, inclusive entre duplas, temos um grupo no whats para isso.
- Ah, não tente somente copiar e colar o código da internet, vamos pedir que você explique a lógica por trás da sua resolução, então nada de colar
- Sinta-se a vontade para chamar o pessoal do GVCode para **tirar dúvidas**. Iremos ajudar sempre que possível, porém *não podemos resolver o case para você*.
- Por fim: **DIVIRTA-SE!!** Programação é para ser diversido e desafiador, então esperamos que além do desafio, vocês tenha uma experiência bacana.
