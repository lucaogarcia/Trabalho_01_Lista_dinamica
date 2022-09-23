UNIVERSIDADE ESTADUAL DE MARINGÁ *![](Aspose.Words.665963ca-63b5-42c7-b218-e0a33425f5c9.001.png)*Centro de Tecnologia - CTC  

Departamento de Informática - DIN

**9893-32 – ESTRUTURA DE DADOS                 BACHARELADO EM INFORMÁTICA – 2° sem /2021 Prof. Rodrigo Calvo** 

**TRABALHO 1 - AGENDA** 

**Objetivo** : Elaborar um programa para criar e manipular uma agenda. O programa deve permitir a operação de inserção, remoção e busca de usuários. Manipulação da agenda deve ser feita por meio de um TAD. 

**Descrição:** A partir de um menu, o programa deve executar as seguintes funções: 

1 – Criar uma agenda; 

2 – Inserir um usuário na agenda; 

3 – Remover um usuário da agenda; 

4 – Buscar um usuário na agenda. 

5 – Imprimir agenda 

6 – Sair do programa. 

Cada elemento da agenda (da lista) é um registro que contém os seguintes dados: 

1 – Nome do usuário (vetor fixo de 20 caracteres) 

2 – Telefone 

3 – Endereço (Rua, número) 

A seguir estão os operadores que devem estar no TAD: 

**Criar uma agenda:** O ponteiro para o primeiro elemento da agenda deve ser inicializado em NULL. 

**Inserir um usuário:** A lista deve estar em ordem alfabética. Assim, ao inserir um usuário, deve-se primeiro encontrar a sua posição e inseri-lo na lista. Para a operação de inserção, deve- se considerar os casos de inserção do único registro da lista, inserção no início, no fim e no meio da lista. 

**Remover um usuário:** O nome do usuário a ser removido deve ser fornecido.** Para remover um usuário, deve-se buscar pelo usuário na lista. Caso o usuário não se encontra na lista, imprimir  uma  mensagem  dizendo  que  o  usuário  não  está  na  lista.  Caso  contrário,  o registro desse usuário deve ser removido. Para a operação de remoção, deve-se considerar os casos de remoção do único registro da lista, remoção no início, no fim e no meio da lista. 

**Buscar um usuário:** O nome do usuário a ser buscado deve ser fornecido.** Deve-se fazer uma varredura na lista em  busca de tal  usuário.  Caso o usuário  não se encontra na lista, imprimir  uma  mensagem  dizendo  que  o  usuário  não  está  na  lista.  Caso  contrário, imprimir todos os dados relacionados do registro encontrado. 

**Apagar a agenda:** Remover todos os usuários da agenda (desalocar o registro de cada usuário). Em seguida, inicializar o ponteiro para o primeiro elemento em NULL.** 

**Imprimir a agenda:** Imprimir todos os dados relacionados aos registros da agenda (lista). **Sair do programa:** O programa deve ser finalizado. No programa principal, deve ser declarada uma variável que é um ponteiro para uma lista de elementos  (agenda).  O  menu  deve  aparecer  logo  que  o  programa  é  executado,  e  aparecer novamente quando a execução de um dos operadores é finalizado. Em seguida, o usuário deve escolher um dos operadores para ser executado. Este processo se repete até que o usuário escolha o item ‘Sair do programa’. 

**Obs**.:  Utilizar  subprogramas  e  evitar  o  uso  de  variáveis  globais.  Isto  será  considerado  na avaliação. 

**Considerações** 

1) O trabalho deverá ser feito individualmente ou em dupla; 
1) O programa e do TAD devem fazer o que foi especificado; 
1) Não será permitido trabalhos nos quais haja quaisquer tipos de cópia ou plágio. 
1) O programa deve ser implementado em C e em qualquer ambiente/compilador; 

**Modo de entrega:** Fazer upload no Classroom.**.** A primeira linha do código de cada arquivo, deve conter o nome completo e RA do(s) aluno(s) em comentário. 

**Prazo de entrega**: 20/04/2021 
