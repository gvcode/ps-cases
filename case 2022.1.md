# Processo seletivo - Primeira fase

Olá!
Se você chegou até aqui parabéns pela iniciativa! Nós já entendemos que você tem um interesse por programação e data science, por isso agora queremos ver como você aprende e se desenvolve enfrentando desafios.
Então, aqui você vai encontrar tudo o que você precisa para essa fase do processo. Nós dividimos esse documento em três partes:

- Como vai ser a estrutura do desafio
- Opções de challenges para você escolher e
- Conteúdo para aprender o básico de programação.

E aí, topa fazer parte desse desafio?

Primeiramente, gostaríamos de deixar bem claro que nós não exigimos NENHUM conhecimento prévio de programação e acreditamos que com dedicação qualquer pessoa pode aprender qualquer coisa!
A programação não é algo que você aprende simplesmente vendo aulas, você precisa pôr em prática!
"É fazendo que se aprende a fazer aquilo que se deve aprender a fazer." -Aristóteles

Por isso, a nossa primeira fase do Processo Seletivo 2022.1 será um desafio prático em programação, e consiste de quatro passos:

- Estudar a lista de projetos disponíveis e escolher um desafio 
- Reunir-se com o seu grupo para resolver o case
- Estudar o necessário para resolver o desafio
- Enviar até 23/03 o arquivo do desafio para o administrador do grupo em que você foi encaixado

Vale lembrar que os projetos serão avaliados conforme a dedicação e a profundidade no desafio escolhido!

Bom projeto!


## Calculadora
Ao fazer uma calculadora simples, você terá uma ideia de como os operadores básicos do Python funcionam, o fluxo de trabalho de entrada / saída, os tipos de dados do Python e a sintaxe básica do Python. Também é recomendável criar casos de teste manualmente para entender as restrições e verificar a funcionalidade de seu aplicativo de calculadora. Definitivamente, você deve começar com isso como um de seus primeiros projetos Python. 

No recorte proposto, esperamos que você elabore um calculadora que colete os números do usuário e execute as operações matemáticas básicas (soma, subtração, produto e divisão). Além disso, você deve escolher 4 operações presentes em uma calculadora financeira e incluí-las como opção da maneira que preferir. Alguns exemplos de operações são, cálculo do valor presente, valor descontado de fluxo de caixa e cálculo da taxa interna de retorno. Lembre que a apresentação da calculadora é algo importante. Bom trabalho!


## Jogo da velha
Tic-Tac-Toe é um jogo muito comum e fácil de jogar, jogado extensivamente em notebooks. A premissa do jogo é simples. É um jogo baseado em turnos, onde o objetivo é alinhar uma trifeta de círculos ou cruzes na diagonal, horizontal ou vertical em uma grade quadrada 3 × 3 para alcançar a vitória.
    
O desafio na criação deste jogo reside principalmente em se familiarizar com a indexação de array 2D e descobrir como verificar alinhamentos diagonais. Uma vez que isso seja resolvido, a codificação deve ser simplificada.

## Impressora de padrões
Em projetos Python para iniciantes, os programas de impressão de padrões são uma ótima maneira de testar as habilidades de design de loops aninhados. Basicamente, tudo o que você precisa fazer é imprimir o texto de tal forma, usando loops, que eles se assemelhem a padrões simétricos.

Por exemplo, um padrão se parece com este:

1 12 123 1234

Agora, se um usuário inserir o número 4, você precisará imprimir quatro linhas do padrão acima. Você também pode tentar outros padrões e criar um programa baseado em menu que pergunta aos usuários qual padrão eles desejam imprimir.

## Anagramas
Um anagrama é uma palavra ou frase formada com o re-arranjo de todas as letras de uma outra palavra ou frase (sem sobra ou falta). Exemplos:
- A palavra barco é um anagrama da palavra cobra (todas as letras de “cobra” usadas em “barco).
- A palavra mar não é um anagrama da palavra roma (a letra “o” em “roma” não foi usada).
- A palavra sal não é um anagrama da palavra mal (a letra “s” de “sal” não existe em “mal”).

### O problema 
Escreva um programa na sua linguagem e bibliotecas preferidas que:
1. Leia a expressão (que pode ser uma frase ou apenas uma palavra) a ser usada para a criação dos anagramas da linha de comando. Apenas as letras de “A” a “Z” deverão ser consideradas (ignore espaços e converta todas as letras minúsculas para maíusculas). Retorne erro e aborte a execução se caracteres inválidos forem encontrados na expressão (qualquer caracter não alfabético que não seja espaço, incluindo números, pontuação, ou caracteres acentuados).
2. Leia uma lista de palavras válidas do arquivo [words.txt](https://osprogramadores.com/desafios/d06/words.txt). O arquivo é formatado com uma palavra por linha, com palavras da língua inglesa (Nota: apesar de várias tentativas, o autor não conseguiu achar uma lista “limpa” de palavras da língua portuguesa).
3. Imprima todas as combinações possíveis de anagramas (sem repetição de linhas ou palavras). Os anagramas devem conter apenas palavras válidas (lidas do arquivo acima).
4. O formato de saída deve conter múltiplas linhas (uma por anagrama), com as palavras ordenadas dentro de cada linha (veja Exemplos abaixo).
5. O programa deve ser capaz de calcular e imprimir a lista de anagramas possíveis para uma expressão de até 16 caracteres em menos de 60 segundos.

Exemplos:
Expressão é uma palavra:

```
vermelho

ELM HO REV
ELM OH REV
OHM REVEL
LEVER OHM
ELM HOVER
HOLM VEER
HELM OVER
HELM ROVE
```

Expressão é uma frase (lembre-se de ignorar espaços e converter todas as letras para maiúsculas):

```
oi gente

GO I TEEN
GENE I TO
GET I ONE
EON GET I
ENG I TOE
GEE I TON
GEE I NOT
EGO I NET
EGO I TEN
GEE IT NO
GEE IT ON
GO IN TEE
GEE IN TO
GENIE TO
GONE TIE
GEE OINT
GEE INTO
GEE TONI
GINO TEE
GENE ITO
EGO TINE
```

## Reversão de strings
Este programa exigirá que você pegue uma entrada de string (matriz de caracteres) de um usuário e reorganize a string na ordem inversa, exibindo a saída para o usuário. A primeira abordagem óbvia será simplesmente inverter todos os caracteres da string, mas você pode aprimorar ainda mais este projeto alterando vários atributos do programa:

Pegue uma frase como entrada e inverta cada palavra na frase, mantendo as posições das palavras iguais
Pegue uma frase como entrada e inverta a ordem em que as palavras aparecem, sem alterar o conteúdo das próprias palavras

Da mesma forma, muitas outras variações de manipulação de strings podem ser implementadas nesta atribuição. No final dele, você pode até mesmo criar um programa baseado em menu onde os usuários podem selecionar que tipo de manipulação de string desejam executar em suas entradas fornecidas.

## Jogo baseado em escolha
Você pode colocar suas habilidades de raciocínio condicional fazendo algo incrivelmente divertido, mas como? Sem o uso de qualquer interface de usuário ou mecanismo gráfico complexo, você pode desenvolver um jogo que simplesmente solicite que o jogador selecione opções baseadas em texto para progredir ainda mais no jogo. Você tem a opção de tornar este jogo o mais eficiente possível com vários finais com base nas escolhas feitas pelo jogador ao longo de sua experiência de jogo. Para evitar esforços desnecessários, você pode reutilizar o código e modularizar e planejar adequadamente seu gráfico para minimizar redundâncias.

Para dar um passo adiante e adicionar movimentos reais em seu jogo, você também pode usar grades de matriz 2D para implementar ambientes de jogo ou mapas. Você pode acompanhar onde o jogador está por suas escolhas de movimento, apontando o jogador em uma posição particular na grade da matriz. Obstáculos, inimigos e outros itens de jogo podem ser colocados estrategicamente na grade para o jogador correr ou pegar, para adicionar mais elementos dinâmicos ao seu jogo. Você também pode programar os movimentos do inimigo para tornar o jogo ainda mais desafiador.

Trabalhar com arrays 2D pode ser extremamente útil quando você lida com projetos de programação de nível de indústria maiores, onde você pode ter que ser proficiente em trabalhar e manipular arrays multidimensionais.

## Jogo da forca
Nas ideias de projetos básicos do Python, Hangman é um dos jogos populares em que uma palavra é escolhida pelo jogador adversário ou pelo programa, e o jogador tem todo o conjunto de alfabeto disponível para adivinhar as letras. A palavra alvo será exibida com a maioria das letras faltando. É tarefa do jogador escolher os alfabetos com base em uma dica associada à palavra. Se a letra estiver correta, todas as ocorrências possíveis dessa letra em particular serão preenchidas nos respectivos espaços em branco. Se a estimativa estiver incorreta, a contagem de tentativa aumentará e a letra adivinhada será riscada no banco do alfabeto disponível. O número de tentativas não será ilimitado, é claro. Tradicionalmente, seis suposições erradas são permitidas antes que o jogador perca o jogo,

## Números por extenso
Crie um programa que receba um número, e retorne como se lê o número em uma string. Exemplo:

```
Insira um número:
85
oitenta e cinco
```

Adicionalmente, o programa pode reconhecer unidades de medida diferentes:

```
Insira um número:
243,00 R$
duzentos e quarenta e três reais, e zero centavos

Insira um número:
1.456,50 Kg
uma tonelada, quatrocentos e cinquenta e seis kilos, e cinquenta gramas
```

O programa pode reconhecer pontos divisores de algarismos (como no terceiro exemplo). Também pode perguntar em qual unidade que se quer a resposta:

```
Insira um número:
1.456,50 Kg

Insira a unidade desejada:
kilos

mil quatrocentos e cinquenta e seis kilos, e cinco décimos
```

Quais unidades o programa aceita, bem como o número máximo que o programa consegue ler, ficam a seu encargo.

## Material de Estudos e Dicas
    
Agora que você já escolheu o seu desafio, está na hora de estudar e aprender sobre python! Aqui a gente separou alguns materiais em português e inglês para te ajudar com esse desafio:
    
### Materiais
- Instalando Python: https://www.youtube.com/watch?v=VuKvR1J2LQE
    * Aprenda Python em 10 min:https://www.youtube.com/watch?v=Q8eajxcS6dQ
- Nesse curso ele vai codar usando um site para te ajudar a aprender
- Curso básico de Python: https://www.youtube.com/watch?v=rfscVS0vtbw
    * Em inglês com legendas em português ou inglês
- Curso intensivo de Python: https://www.youtube.com/watch?v=GPVsHOlRBBI
    * Em inglês com legendas em português ou inglês
    * Ele é um curso de 10h beeeeem completo que também ensina sobre numpy e pandas
- Documentação Python: https://docs.python.org/pt-br/3/tutorial/index.html
    * A referência básica da linguagem se encontra aqui
    
### Dicas
- Nós somos uma entidade colaborativa, isso quer dizer que não tem ninguém competindo com você. Ou seja, não temos limites de vagas e a sua candidatura não é comparativa. Então, se você apresentar bons resultados no case e estiver alinhado com a cultura do GVCode, você ta dentro.
- Por isso, estimulamos fortemente que vocês colaborem entre si, inclusive entre duplas, temos um grupo no whats para isso.
- Ah, não tente somente copiar e colar o código da internet, vamos pedir que você explique a lógica por trás da sua resolução, então nada de colar
- Sinta-se a vontade para chamar o pessoal do GVCode para tirar dúvidas. Iremos ajudar sempre que possível, porém não podemos resolver o case para você.
- Por fim: DIVIRTA-SE!! Programação é para ser diversido e desafiador, então esperamos que além do desafio, vocês tenha uma experiência bacana.
