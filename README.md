Aulas GPSL
==========

Repositório contendo os slides e exemplos que serão usados em aulas do gpsl.

Roteiros
========

Aqui estão dois roteiros de aulas, a inicial para os bixos no primeiro semestre
e a avançada no segundo. O roteiro a ser seguido para cada aula é:

Bixos
-----
Aula 00: SL
TODO: Aula 01: Linux 
Aula 02: Shell
TODO: Aula 03: Desktops
TODO: Aula 04: Editores

Avançada
--------
 - Aula 0: Conceitos

*Coding Style*
==============

Tente seguir o mesmo estilo se for contribuir com "código" para as aulas, mas
lembre-se que essas regras podem ser quebradas dada uma boa justificativa.

- Mantenha o texto entre 72 e 80 colunas, exceto em construções complexas (e.g.
  tabelas)
- Cada conjunto de slides deve ter seu próprio diretório. Slides das aulas para
  os bixos devem ter _bixos-_ prefixado no nome.
- Imagens que serão usadas em mais de uma aula devem ir para o diretório
  'imagens' na raiz, caso contrário crie um diretório 'imagens' no diretório da
  aula
- Coisas de latex que serão reaproveitadas devem ir para o diretório _lib_ na
  raiz
- Quando for usar imagens, tente sempre usar graphviz ou tikz, mas se não souber
  usar coloque o png ou svg no repositório (svg's devem ser convertidos para png
  no makefile)
- Para simular a interação de um shell em um slide, inclua _lib/shell.tex_ e
  use da seguinte manera:

    `\begin{center}`  
    `\begin{shell}`  
    `\usercmd{sudo su}`  
    `\comment{adicionando módulo}`  
    `\rootcmd{modprobe _module_}`  
    `\end{shell}`  
    `\end{center}`  

Licença
=======

Todo material disponível aqui é disponibilizado sob CC-BY 3.0, exceto
caso outra licença seja especificada explicitamente, e o copyright é
de todos os contribuidores.

Autores
=======

Ivan Sichmann Freitas, Sérgio Durigan Júnior, Gabriel Krisman Bertazi.
