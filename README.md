# Um Curso de Sistemas Operacionais

Um repositório com pequenas notas de ensino no tópico de Sistemas Operacionais.

**Objetivo** Sumarizar os principais pontos discutidos em uma disciplina de
Sistemas Operacionais (SO). Deixar claro a *big picture* de como todas as
partes se integram utilizando o *XV6* como estudo de caso.

**Motivação** Após lecionar SO, percebi que cada livro tem uma abordagem
diferente, algo esperado. Isto é, não existe uma visão unificada com um único
caso de estudo. Quem chega mais perto disto é o [OStep](os), livro texto que
sugiro, e o [XV6 Book](xv6). Enquanto o OStep é um ótimo livro texto, o livro
do XV6 detalha aspectos de implementação. IMHO, livros como o Tanenbaum e
Siberschatz gastam muito tempo com casos de uso e exemplos históricos que
faz o leitor perder o foco do todo. *As notas de aula deste Git não substituem
um bom livro*. Como dito, o objetivo aqui é apenas em prover uma visão mais
unificada. Para estudo, complemente as notas de aula aqui descritas com um
pelo menos um bom livro. Combinar as notas, o livro OStep, e algum clássico
da área, como Tanenbaum ou Siberschatz, é uma boa abordagem.

**Inspirações** Livros texto e artigos simples que gastam pouco tempo indo para
os pontos principais: OStep, XV6 Book, Linux Kernel GitBook.
[Vide referências](Referências).

## Tópicos:

  1. Introdução
  1. Processos
     1. Estruturas de um Processo
     1. Morte e Vida de Processos
     1. Fork/Exec
     1. Sinais e Pipes
     1. Escalonamento de Processos
     1. Mensurando a Eficácia de Algoritmos de Escalonamento
  1. Concorrência
     1. Semáforos
     1. Mutexes
     1. Operações Atômicas
     1. Outras Primitivas (e.g., Barreiras, Monitores)
     1. Sistemas de processamento de eventos/mensagens
     1. Deadlocks
  1. Gerenciamento de Memória
     1. Bottom Up: Qual o papel do Hardware?
     1. Estratégias Simples de Alocação de Memória
     1. MMU Simples (Base + Limite)
     1. Segmentação
     1. Paginação
     1. Tabelas de Página
     1. Memória Virtual
  1. Persistência
     1. Dispositivos de E/S
     1. Discos
     1. RAID
     1. iNodes
     1. File Allocation Table
     1. Fast File System
     1. Log File Systems
     1. Journal File Systems
  1. Sistemas Distribuídos
     1. Visão Geral
     1. Sistemas de Arquivos Distribuídos: Caso 1 - NFS
     1. Sistemas de Arquivos Distribuídos: Caso 2 - AFS
     1. Sistemas de Arquivos Distribuídos: Caso 3 - GlusterFS, GFS e Afins
  1. Proteção e Segurança
     1. Conceitos Gerais de Proteção
     1. Conceitos Gerais de Segurança
  1. Virtualização
     1. Emuladores
     1. Hypervisors Tipo 2
     1. Paravirtualização
     1. Containers
     1. Caso de Estudo: Docker

## Slides

Aonde encontrar

## Referências

### Visão geral da matéria

  1. [Operating Systems: Three Easy Pieces - OSTEP](http://pages.cs.wisc.edu/~remzi/OSTEP/) <br>
     Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau <br>
     Version 0.91 -- ou mais recente se houver <br>
     **Apenas em inglês. Aberto!**
     
  1. Operating System Concepts (Fundamentos de Sistemas Operacionais) <br>
     Abraham Silberschatz, Peter B. Galvin and  Greg Gagne <br>
     9th Edition. Versões antigas também são boas para a disciplina <br>
     **Inglês e Português**

  1. Modern Operating Systems (Sistemas Operacionais Modernos) <br>
     Andrew S. Tanenbaum and Herbert Bos <br>
     4th Edition. Versões antigas também são boas para a disciplina <br>
     **Inglês e Português**

### Detalhes de Implementação

  1. [xv6 - Código](https://github.com/mit-pdos/xv6-public)
  1. [xv6 - a simple, Unix-like teaching operating system (livro)](https://pdos.csail.mit.edu/6.828/2016/xv6/book-rev9.pdf) <br>
     Russ Cox, Frank Kaashoek and Robert Morris <br>
     Revision 9 -- ou mais recente se houver <br>
      **Apenas em inglês. Aberto!**
  1. [Linux Kernel - Código](https://github.com/torvalds/linux)
  1. [Linux Insides - gitbook](https://www.gitbook.com/book/0xax/linux-insides/details) <br>
     (@OxAX)[https://twitter.com/0xAX]
