# Complex_Networks_USP
#### [English version here!](https://github.com/brunereduardo/GameXp_DB_USP/blob/master/Documentos/English/README.md)

<p> O projeto tem como objetivo principal o desenvolvimento de um sistema de banco de dados que ofereça suporte para a organização do evento <a href="https://www.gamexp.com.br/">GAMES XP</a>. O foco do projeto é a base de dados do sistema, projetada para persistência de dados. Além disso, com o objetivo de integrar conhecimento de disciplinas distintas e aproximar o projeto de um cenário mais prático e real.<br>Para mais informações, basta procurar pelo arquivo .PDF na pasta <a href="https://github.com/brunereduardo/GameXp_DB_USP/tree/master/Documentos">Documentos.</a></br></p>
<p>O projeto pertence aos seguintes desenvolvedores:<br></br>
<br><a href="https://github.com/brunereduardo">Bruner Eduardo Augusto Albrecht</a></br>
<br><a href="https://github.com/CarlosSantosJr">Carlos R Dos Santos Junior</a></br>
<br>Marcelo Foresto Porto da Costa</br>
<br><a href="https://github.com/illiamw">William Luis Alves Ferreira</a></br></p>

<p>Com base na gramática da linguagem P--, disponível nos .PDF em Documents, enriquecida com
o comando “for”, desenvolvemos o analisador léxico para esta linguagem. Foram produzidos os autômatos projetados (usando a ferramenta JFlap) e o código-fonte correspondente aos autômatos projetados (na linguagem de programação python).</p>

<p>O analisador léxico aceita um arquivo txt com o programa escrito em P-- e produz um outro arquivo txt com a saída, com um par cadeia-token por linha (indicando os
erros léxicos, se houver). Para mais informações, basta procurar pelo arquivo .PDF na pasta <a href="https://github.com/brunereduardo/Compiler_Py_USP/tree/master/Documents">Documents.</a></p>

## Instruções para Compilar o Codigo-Fonte
 Para preparar o terreno para a compilação, respeitando a linguagem utilizada, *python*, os  passos  essenciais dos códigos fonte dos analisadores sintático- ***syntacticAnalyzer.py*** - e léxico- ***LexicalAnalyzer.py*** -, são basicamente: ter a versão basica, python 3 ou superior, para que se possa ter acesso a um interpretador da linguagem utilizada e, assumindo que se tenha acesso a um terminal ou uma IDE para Python, basta rodar o código do compilador - ***compiler.py*** -para que o mesmo utilize o analisador léxico, o analisador sintático e o armazenamento de erros - ***Erros.py***-, na entrada do arquivo txt a ser analisado. Por fim, o compilador gera a saida - saida.txt  -com as análises feitas pelo léxico e sintático, com o intuito de ser utilizado em futuras implementações. Abaixo temos um exemplo de execução, no qual basta fazer o uso da linha de comando a seguir:
```
python3  compiler.py caminho/nome_do_arquivo_de_entrada.txt 
```
<p><b>O projeto pertence aos seguintes desenvolvedores:</b></p><a href="https://github.com/brunereduardo">Bruner Eduardo Augusto Albrecht</a><br></br>
<a href="https://github.com/CarlosSantosJr">Carlos R Dos Santos Junior</a><br></br>
<a href="https://github.com/ClaytonMiccas">Clayton Miccas Junior</a>
