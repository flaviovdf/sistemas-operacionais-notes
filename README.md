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
    1. Deadlocks
    
  1. Gerenciamento de Memória
    1. Bottom Up: Qual o papel do Hardware?
    1. Estratégias Simples de Alocação de Memória
    1. MMU Simples (Base + Limite)
    1. Segmentação
    1. Paginação
    1. Tabelas de Página
    1. Memória Virtual
    
  1. Persistências
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
    
  1. Virtualização
    1. Como implementar
    1. Emuladores
    1. Máquinas Virtuais
    1. Hypervisors
    1. Containers
    1. Caso de Estudo: Docker
    
  1. Proteção e Segurança
    1. Conceitos Gerais de Proteção
    1. Conceitos Gerais de Segurança

## Slides

Aonde encontrar

## Referências

### Visão geral da matéria

  1. OStep
  1. Siberschatz
  1. Tanenbaum

### Detalhes de Implementação

  1. XV6
  1. FreeBSD
  1. Linux Kernel Development
  1. Linux GitBook
