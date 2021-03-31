# MONTADOR_SIMULADOR *assembly_inventado*
Montador e simulador de assembly inventado

MANUAL DE COMPILAÇÃO DO MONTADOR E SIMULADOR 
NOTA: EXISTEM 2 ARQUIVOS .CPP SENDO UM O MONTADOR E O OUTRO O SIMULADOR
      COLOCAR ARQUIVOS NO MESMO DIRETÓRIO PARA FACILICAR USO
      
1.MONTADOR
2.SIMULADOR

A COMPILAÇÃO FUNCIONA DA SEGUINTE FORMA:
1.Utilizando um arquivo .asm já existente (código com a linguagem hipotética) 
  como arquivo de entrada na linha de comando no formato "./montador myprogram.asm" obtem-se
  caso o código .asm esteja escrito de acordo com as especificações passadas, um arquivo de
  mesmo nome com a extensão .obj com o código objeto deste, caso o código .asm não esteja 
  escrito de acordo com as especificações passadas, é mostrado no terminal os erros
  do programa com suas respectivas linhas e tipos de erro (léxico, sintático e semântico).  

2.De mesma forma, utilizando o arquivo .obj gerado anteriormente (código objeto do código
  .asm escrito corretamente) como arquivo de entrada na linha de comando no formato "./simulador myprogram.obj" 
  gera-se um arquivo de mesmo nome de extensão .out com os outputs do código e no terminal 
  aparecem o PC e acumulador após cada instrução, caso a instrução seja OUTPUT tem-se também
  o output, caso a instrução seja INPUT o usuário deve colocar o input desejado no terminal.

***A IMPLEMENTAÇÃO FOI FEITA COM O USO DO VSCODE E DA LINGUAGEM C++***   


