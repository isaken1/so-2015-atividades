======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Isaac Kennedy Diniz Gomes
:Matrícula: 20121144010702
:Data: 01/07/2015

cat
  Mostrar arquivos de texto

cd
  cd "NomeDoDiretorio"/"NomeDoDiretorio"/... - Mudar para...
  cd - Voltar para diretório principal
  cd ../../... - Voltar diretórios
  
cowsay
  cowsay -f - Mostra a saída do comando cowsay (vaca) personalizado

echo "Texto"
  Imprime um texto no terminal

env
  Imprime lista de variáveis de ambiente

exit
  Fecha (termina) um processo ou aplicação

help
  Abre uma lista de comandos do SHell

HISTTIMEFORMAT="%d/%m/%y
  Muda o formato em que a horário é exibido no comando history

hostname
  Mostra o nome da máquina

ifconfig
  Interfaces de redes

last
  Mostra os usuários logados

lastb
  Descrição do comando

ls
  Lista os arquivos e diretóriosdo diretório atual

mkdir
  mkdir "NomeDoDiretório" - Cria um diretório

nome="fulano"
  Cria uma variável "nome" e atribui o valor "fulano"

passwd
  Muda a senha

pwd
  Mostra o diretório atual


set
  É utilizada para determinar e/ou mudar variáveis de ambiente
  set variavel=valor


tree
  lista os conteúdos de diretórios em formato de árvore
  tree -argumentos diretorio...
  tree -a imprimir todos (inclui ocultos) -d apenas diretorios 
  

tty
  Imprime o nome do arquivo atrelado ao terminal vinculado à saída padrão


vim
  Abre um arquivo de text ou código usando o editor vim


wait
  Espera um determinado processo ou periodo de tempo terminar.

wall
  "write all" imprime uma mensagem para todos os usuários logados.
  wall "mensagem ou arquivo" 
  wall -t TIMEOUT define um timeout para a função ser executada

which
  Mostra o diretório de determinado comando bash

while
  Laço while normal em linguagens de programação
  while [condiçao]; do
    ...
  done

who
  Imprime uma lista de usuarios logados na tela e suas informações.

whoami
  Imprime o usuario na tela
  
write
  Envia uma mensagem ou conteúdo de arquivo para determinado usuário logado
  write nome_do_usuario 
