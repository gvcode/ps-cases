# Processo seletivo - Segunda fase

![Cabeçalho Emails](https://user-images.githubusercontent.com/73006837/131930070-5fd04700-ad35-4ec1-9265-9e7aaddb3ad4.png)

Olá!

Se você chegou até aqui parabéns tripulante! Nós já entendemos que você tem um interesse por programação e data science, por isso agora queremos ver como você aprende e se desenvolve enfrentando desafios.

Então, aqui você vai encontrar tudo o que você precisa para essa fase do processo. Nós dividimos esse documento em três partes:, como vai ser a estrutura do desafio, opções de challenges para você escolher e conteúdo para aprender o básico de programação.

E aí, topa fazer parte desse desafio?



## Anagramas!

Um anagrama é uma palavra ou frase formada com o re-arranjo de todas as letras de uma outra palavra ou frase (sem sobra ou falta). Exemplos:
- A palavra barco é um anagrama da palavra cobra (todas as letras de “cobra” usadas em “barco).
- A palavra mar não é um anagrama da palavra roma (a letra “o” em “roma” não foi usada).
- A palavra sal não é um anagrama da palavra mal (a letra “s” de “sal” não existe em “mal”).

### O problema 
Escreva um programa na sua linguagem e bibliotecas preferidas que:
1. Leia a expressão (que pode ser uma frase ou apenas uma palavra) a ser usada para a criação dos anagramas da linha de comando. Apenas as letras de “A” a “Z” deverão ser consideradas (ignore espaços e converta todas as letras minúsculas para maíusculas). Retorne erro e aborte a execução se caracteres inválidos forem encontrados na expressão (qualquer caracter não alfabético que não seja espaço, incluindo números, pontuação, ou caracteres acentuados).
2. Leia uma lista de palavras válidas do arquivo words.txt (Download). O arquivo é formatado com uma palavra por linha, com palavras da língua inglesa (Nota: apesar de várias tentativas, o autor não conseguiu achar uma lista “limpa” de palavras da língua portuguesa).
3. Imprima todas as combinações possíveis de anagramas (sem repetição de linhas ou palavras). Os anagramas devem conter apenas palavras válidas (lidas do arquivo acima).
4. O formato de saída deve conter múltiplas linhas (uma por anagrama), com as palavras ordenadas dentro de cada linha (veja Exemplos abaixo).
5. O programa deve ser capaz de calcular e imprimir a lista de anagramas possíveis para uma expressão de até 16 caracteres em menos de 60 segundos.

Exemplos:
Expressão é uma palavra:
$ anagrama "vermelho"

$ ./anagramarama "vermelho"\
ELM HO REV\
ELM OH REV\
OHM REVEL\
LEVER OHM\
ELM HOVER\
HOLM VEER\
HELM OVER\
HELM ROVE

Expressão é uma frase (lembre-se de ignorar espaços e converter todas as letras para maiúsculas):
$ ./anagramarama "oi gente"\
GO I TEEN\
GENE I TO\
GET I ONE\
EON GET I\
ENG I TOE\
GEE I TON\
GEE I NOT\
EGO I NET\
EGO I TEN\
GEE IT NO\
GEE IT ON\
GO IN TEE\
GEE IN TO\
GENIE TO\
GONE TIE\
GEE OINT\
GEE INTO\
GEE TONI\
GINO TEE\
GENE ITO\
EGO TINE

## Primos em Pi
### Introdução 
O número pi (π) é uma das mais famosas e mais facilmente reconhecidas constantes matemáticas. Originalmente definido como o resultado da divisão da circunferência de um círculo pelo seu diâmetro, π é um número irracional e a sua representação decimal é infinita e não se repete.

### Instruções 
Este desafio consiste em encontrar a sequência mais longa de números primos (entre 2 e 9973) no primeiro 1 milhão de casas decimais de π.

Em detalhes:
- Localize a sequência mais longa (em dígitos) de números primos nas casas decimais de π no arquivo fornecido (1 milhão de casas decimais).
- Em caso de mais de uma sequência do mesmo tamanho, a sequência com o início mais próximo do ponto decimal deverá ser utilizada.
- Apenas números primos entre 2 e 9973 deverão ser considerados na busca (basicamente, números primos contendo de um a quatro dígitos).

Exemplo 
Considere π com 20 decimais:
3.14159265358979323846

Neste caso, a maior sequência de numeros primos seria:
41 59 2 653 5 89 7 9323

Que resulta na sequência:
4159265358979323

### Formato de saída 
Imprima uma linha contendo a maior sequência encontrada, sem espaços. Exemplo:
4159265358979323

### Validação 
Baixe o arquivo de dados.
Descompacte o arquivo localmente com tar zxvf pi-1M.tar.gz.
Rode o seu programa usando o arquivo de dados como entrada (pi-1M.txt)
Onde 1001 representa o número de decimais desejadas + 1.

## FUNCIONÁRIOS
### Processando as informações da empresa:
Considere, como exemplo, o seguinte arquivo funcionários.json, com o seguinte conteúdo:

{\
    "funcionarios":[\
        {\
            &nbsp;&nbsp;&nbsp; "id":0,\
            &nbsp;&nbsp;&nbsp; "nome":"Marcelo",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Silva",\
            &nbsp;&nbsp;&nbsp; "salario":3200.00,\
            &nbsp;&nbsp;&nbsp; "area":"SM"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":1,\
            &nbsp;&nbsp;&nbsp; "nome":"Washington",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Ramos",\
            &nbsp;&nbsp;&nbsp; "salario":2700.00,\
            &nbsp;&nbsp;&nbsp; "area":"UD"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":2,\
            &nbsp;&nbsp;&nbsp; "nome":"Sergio",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Pinheiro",\
            &nbsp;&nbsp;&nbsp; "salario":2450.00,\
            &nbsp;&nbsp;&nbsp; "area":"SD"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":3,\
            &nbsp;&nbsp;&nbsp; "nome":"Bernardo",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Costa",\
            &nbsp;&nbsp;&nbsp; "salario":3700.00,\
            &nbsp;&nbsp;&nbsp; "area":"SM"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":4,\
            &nbsp;&nbsp;&nbsp; "nome":"Cleverton",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Farias",\
            &nbsp;&nbsp;&nbsp; "salario":2750.00,\
            &nbsp;&nbsp;&nbsp; "area":"SD"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":5,\
            &nbsp;&nbsp;&nbsp; "nome":"Abraão",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Campos",\
            &nbsp;&nbsp;&nbsp; "salario":2550.00,\
            &nbsp;&nbsp;&nbsp; "area":"SD"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":6,\
            &nbsp;&nbsp;&nbsp; "nome":"Letícia",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Farias",\
            &nbsp;&nbsp;&nbsp; "salario":2450.00,\
            &nbsp;&nbsp;&nbsp; "area":"UD"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":7,\
            &nbsp;&nbsp;&nbsp; "nome":"Fernando",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Ramos",\
            &nbsp;&nbsp;&nbsp; "salario":2450.00,\
            &nbsp;&nbsp;&nbsp; "area":"SD"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":8,\
            &nbsp;&nbsp;&nbsp; "nome":"Marcelo",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Farias",\
            &nbsp;&nbsp;&nbsp; "salario":2550.00,\
            &nbsp;&nbsp;&nbsp; "area":"UD"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":9,\
            &nbsp;&nbsp;&nbsp; "nome":"Fabio",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Souza",\
            &nbsp;&nbsp;&nbsp; "salario":2750.00,\
            &nbsp;&nbsp;&nbsp; "area":"SD"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "id":10,\
            &nbsp;&nbsp;&nbsp; "nome":"Clederson",\
            &nbsp;&nbsp;&nbsp; "sobrenome":"Oliveira",\
            &nbsp;&nbsp;&nbsp; "salario":2500.00,\
            &nbsp;&nbsp;&nbsp; "area":"SD"\
        }\
    ],\
    "areas":[\
        {\
            &nbsp;&nbsp;&nbsp; "codigo":"SD",\
            &nbsp;&nbsp;&nbsp; "nome":"Desenvolvimento de Software"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "codigo":"SM",\
            &nbsp;&nbsp;&nbsp; "nome":"Gerenciamento de Software"\
        },\
        {\
            &nbsp;&nbsp;&nbsp; "codigo":"UD",\
            &nbsp;&nbsp;&nbsp; "nome":"Designer de UI/UX"\
        }\
    ]\
}
 
Utilize a linguagem de programação de sua preferência (e quaisquer bibliotecas que sejam necessárias) e escreva um programa que leia o nome de um arquivo JSON como parâmetro – que seguirá os mesmos moldes do arquivo funcionários.json listado acima – e imprima as informações solicitadas a seguir, baseado no conteúdo do arquivo lido.

### Condições
Em todos os casos abaixo, assuma:
- Todos os cálculos envolvendo salários (mínimo, máximo, média) são feitos em ponto flutuante.
- Todas as impressões de salário feitas em duas casas decimais, sem formatação (ex: 1234.56)
- “Nome completo” == Nome + espaço + Sobrenome (Ex: João Silva)
- “Nome da área” é o nome da área, não o código.
- A listagem não precisa estar ordenada.

### Questões 

**1. Quem mais recebe e quem menos recebe na empresa e a média salarial da empresa. 
Calcular e imprimir o nome completo do(s) funcionário(s) com o(s) maior(es) e menor(res) salário(s) na empresa inteira, bem como o salário médio. Em caso de empate (mais de um funcionário nas posições de maior ou menor salário), imprimir todos os funcionários nessas posições que tem o mesmo salário.**

Formato (máximo)\
global_max|<nome_completo>|<Salário>
 
Formato (mínimo)\
global_min|<nome_completo>|<salário>
 
Formato (média)\
global_avg| <média salarial>
 
Exemplo:
global_min|José Ruela|800.00
global_min|José Mané|800.00
global_max|Bernardo Costa|3700.00
global_avg|1400.23
 
**2. Quem mais recebe e quem menos recebe em cada área e a média salarial em cada área. 
Calcular e imprimir o nome completo do(s) funcionário(s) com o(s) maior(es) e menor(res) salário(s) por área da empresa empresa, bem como o salário médio (também por área). Em caso de empate (mais de um funcionário nas posições de maior ou menor salário em uma determinada área), imprimir todos os funcionários nessas posições que tem o mesmo salário, em cada área.**
  
Formato (máximo)\
area_max|<nome da área>|<nome_completo>|<salário máximo>
 
Formato (mínimo)\
area_min|<nome da área>|<nome_completo>|<salário>
 
Formato (média)\
area_avg|<nome da área>|<salário médio>
 
Exemplo:\
area_max|Gerenciamento de Software|Bernardo Costa|3700.00\
area_max|Gerenciamento de Software|Richie Rich|3700.00\
area_max|Recrutamento|Hugh Hefner|3700.00\
area_min|Gerenciamento de Software|Marcelo Souza|1200.00\
area_min|Gerenciamento de Software|João Lenão|1200.00\
area_avg|Gerenciamento de Software|3450.00\
area_avg|Recrutamento|3000.00
 
**3. Área(s) com o maior e menor número de funcionários 
Calcular e imprimir as áreas com o maior e menor número de funcionários. Em caso de empate (mais de uma área com o mesmo número máximo ou mínimo de funcionários), todas as áreas dentro daquele critério devem ser impressas.**
  
Formato (área(s) com o maior número de funcionários):\
most_employees|<nome da área>|<número de funcionários>
 
Formato (área(s) com o menor número de funcionários)\
least_employees|<nome da área>|<número de funcionários>
 
Exemplos:\
least_employees|Gerenciamento de Software|2\
least_employees|Limpeza|2\
most_employees|Recursos Humanos|30\
most_employees|Engenharia|30
 
**4. Maiores salários para funcionários com o mesmo sobrenome 
Para cada sobrenome com mais de um funcionário, listar o(s) funcionário(s) que recebem o maior salário. Assim como nos itens anteriores, se mais de um funcionário com o mesmo sobrenome tiver o maior salário, listar todos estes.**
  
Formato:
last_name_max|<sobrenome do funcionário>|<nome completo>|<salário>
 
Exemplo:\
last_name_max|Farias|Cleverton Farias|2750.00\
last_name_max|Farias|Paulo César|2750.00
  
Arquivo: 
10K Registros

## Jogo da velha

![GvCode tictactoe](https://user-images.githubusercontent.com/73006837/131929569-c64d0f5b-353e-4d51-8340-186a2ba3bb03.png)
    
Tic-Tac-Toe é um jogo muito comum e fácil de jogar, jogado extensivamente em notebooks. A premissa do jogo é simples. É um jogo baseado em turnos, onde o objetivo é alinhar uma trifeta de círculos ou cruzes na diagonal, horizontal ou vertical em uma grade quadrada 3 × 3 para alcançar a vitória.
    
O desafio na criação deste jogo reside principalmente em se familiarizar com a indexação de array 2D e descobrir como verificar alinhamentos diagonais. Uma vez que isso seja resolvido, a codificação deve ser simplificada.
    
## Pedra, Papel, Tesoura
    
![GVCode Rock](https://user-images.githubusercontent.com/73006837/131929571-d1af48ac-ac1a-4ed1-a12d-7bb4023cdef6.png)
    
Rock, Paper, Scissors é um jogo conhecido para usar em seus projetos Python. Existem muitas maneiras de implementar este jogo em código com base em seu conhecimento de Python. Devido ao elemento aleatório anexado ao jogo, você obviamente terá que usar uma função aleatória para determinar a mão de cada jogador. Você pode começar a desenvolver este jogo com um oponente padrão da CPU e com movimentos aleatórios, e então, você pode aumentar o nível de complexidade criando uma opção para dois jogadores humanos irem um contra o outro. De qualquer forma, o fator criativo envolvido no design do jogo permitirá uma tonelada de flexibilidade em sua abordagem. Certifique-se de adicionar opções para novas tentativas e rastreamento de pontuação para aprimorar a experiência geral.

## Registro do usuário
Depois de entender as listas, a próxima etapa é entender outra estrutura de dados chave, chamada de dicionários Python. Com dicionários, você pode implementar facilmente programas que tenham funcionalidade de banco de dados. Dicionários são estruturas de dados com arquitetura NoSQL baseada em valores-chave e são ideais como objetos, que armazenam registros que precisam ser consultados.
    
Seu aplicativo deve ter vários nomes, números de contato e idades como entrada e armazená-los em um dicionário. Opcionalmente, você pode incluir utilitários de terceiros como o SQLite para armazenar a entrada de forma mais permanente em bancos de dados ou em arquivos JSON se quiser aumentar a utilidade do seu programa.

## Gerador de número de Fibonacci
A série matemática conhecida como série Fibonacci tem sido uma das questões de codificação mais populares na comunidade de programação. Essencialmente, você começa com dois números, de preferência 0 e 1, e os adiciona para criar seu terceiro número de Fibonacci. A partir daí, você simplesmente vai somando a soma e o penúltimo termo de Fibonacci para gerar o próximo.

Neste projeto, você pede a posição do número de Fibonacci exigido pelo usuário e simplesmente o gera. Uma vez gerado, você pode exibir a saída desejada para o usuário. Você pode dar um passo adiante e mostrar ao usuário toda a série até aquele ponto com o funcionamento matemático dela também. Este é um dos melhores projetos Python para se apresentar ao conceito da função recursiva.
    
## Teste

![GVCode Quiz](https://user-images.githubusercontent.com/73006837/131929596-1a2d2c2e-3534-46a2-8ba7-5dc7353a7b3b.png)
    
Neste projeto, você terá que criar um banco de questões com múltiplas escolhas para cada questão e então implementar um sistema de pontuação para os jogadores que tentarem o quiz. Tente armazenar a pontuação de cada jogador usando um arquivo ou banco de dados ao final de cada tentativa de questionário.

## Jogo de adivinhação de números
Considere este projeto como uma introdução ao uso de funções em Python. Pegue um número inicial e um número final de um jogador e gere um número aleatório entre essas duas restrições. O objetivo do jogo é que o jogador adivinhe o número que foi gerado aleatoriamente. A pontuação final do jogador será determinada pelo número de tentativas que o indivíduo levou para chegar à resposta correta. Quanto menor for o número de tentativas, maior será o valor da pontuação. A cada palpite errado, uma dica será fornecida ao jogador, informando se ele está acima do número, abaixo do número ou se o número é um múltiplo da resposta adivinhada incorretamente.

Opcionalmente, você pode criar uma função que recebe dois números e gera um número aleatório entre eles para implementar seu caso de uso. Outras funções também podem ser criadas para fins de sugestão e comparação.
    
    
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

