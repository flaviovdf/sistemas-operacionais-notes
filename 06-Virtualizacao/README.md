# Virtualização

**Qual o problema?**

Bem alto nível, executar um SO (e.g., um Linux) dentro de um outro SO (e.g.,
Windows). De forma mais precisa, virtualização permite a criação de *versões
virtuais* de dispositivos de hardware, discos, acesso à rede, dentre outros
recursos. Lembre-se que tudo pode ser feito em hardware também pode ser feito
em software (e *vice-versa*). Imagine que a ideia da virtualização é criar uma
plataforma de hardware virtual, em software, (e.g., x86) onde podemos instalar
um SO inteiro. Tal plataforma virtual deve permitir a execução de código feito
para a outra, como o Linux, sem mudar o código do mesmo para se adaptar à
virtualização.

**Conceitos Similares:**

  1. *Emulação:* Sim, estilo os jogos que você baixa na Internet. Emulação é
     o ato de traduzir instruções de uma arquitetura para outra. Por exemplo,
     instruções do Super Nintendo para o seu computador. Emulação é sim um
     meio de virtualização, um caso específico que discutiremos nas notas.
     Porém, existem outras formas de realizar o processo de virtualização,
     sendo a emulação um dos mais custosos (não temos nenhuma ajuda do
     hardware).
  1. *Simulação:* Um simulador, estilo o similador de páginas virtuais, é
     um tipo de virtualização? *Não*. Note que ali não criamos nenhum tipo
     de dispositivo virtual ou tradução de instruções. Na simulação nós
     abstraímos, de forma mais simples, o comportamento específico de um
     sistema. Podemos simular sistemas de computação até sistemas biológicos.
