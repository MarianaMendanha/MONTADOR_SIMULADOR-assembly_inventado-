# MONTADOR_SIMULADOR *assembly_inventado*
Montador e simulador de assembly inventado

MANUAL DE COMPILAÇÃO DO MONTADOR E SIMULADOR 
NOTA: EXISTEM 2 ARQUIVOS .CPP SENDO UM O MONTADOR E O OUTRO O SIMULADOR
      COLOCAR ARQUIVOS NO MESMO DIRETÓRIO PARA FACILICAR USO
      
1.MONTADOR

2.SIMULADOR

A COMPILAÇÃO FUNCIONA DA SEGUINTE FORMA:

1.O arquivo montador.cpp deve ser compilado e executado para que o montador seja utilizado.
  Para montar, deve-se acessar a pasta do diretório de onde se encontra o arquivo .cpp 
  utilizando o comando cd e em seguida digitar "g++ montador.cpp -o montador" e então 
  utilizando um arquivo .asm já existente (código com a linguagem hipotética vista em sala) 
  como arquivo de entrada na linha de comando no formato "./montador myprogram.asm" para a 
  execução do programa. Caso o código .asm esteja escrito de acordo com as especificações 
  passadas, um arquivo de mesmo nome com a extensão .obj com o código objeto deste, caso o 
  código .asm não esteja escrito de acordo com as especificações passadas, é mostrado no 
  terminal os erros do programa com suas respectivas linhas e tipos de erro (léxico, sintático 
  e semântico).  

  
2.De mesma forma, O arquivo simulador.cpp deve ser compilado e executado para que o montador 
  seja utilizado. Para montar, deve-se acessar a pasta do diretório de onde se encontra o 
  arquivo .cpp utilizando o comando cd e em seguida digitar "g++ simulador.cpp -o simulador" 
  e então utilizando o arquivo .obj gerado anteriormente (código objeto do código .asm escrito
  corretamente) como arquivo de entrada na linha de comando no formato "./simulador 
  myprogram.obj" gera-se um arquivo de mesmo nome de extensão .out com os outputs do código e no   terminal aparecem o PC e acumulador após cada instrução, caso a instrução seja OUTPUT tem-se     também o output, caso a instrução seja INPUT o usuário deve colocar o input desejado no           terminal.
o output, caso a instrução seja INPUT o usuário deve colocar o input desejado no terminal.

***A IMPLEMENTAÇÃO FOI FEITA COM O USO DO VSCODE E DA LINGUAGEM C++***   

![6 - CONJUNTO DE INSTRUÇÕES DA MÁQUINA HIPOTÉTICA](https://user-images.githubusercontent.com/72531807/113185256-9fac0800-922c-11eb-84fd-fa2b32eed7ab.png)
