## Ubuntu-101
-------------
Lista dos Comandos de Terminal vistos no Curso Ubuntu 101

#### apt-get
Vídeo: *Parte 6 - Configurando e Instalando Programas*

Utilize para instalar e desinstalar programas/pacotes:

> Atualizar Repositórios: `apt-get update`

> Atualizar Programas/Pacotes existentes: `apt-get upgrade`

> Instalar novo Programa/Pacote: `apt-get install`

> Remover Programa/Pacote: `apt-get remove`

#### sudo
Vídeo: *Parte 6 - Configurando e Instalando Programas*

Faça operações elevadas via terminal, como um superusuário.

Use antes do comando que deseja efetuar. Exemplos:

> `sudo apt-get install <nome do pacote>`

#### clear
Vídeo: *Parte 6 - Configurando e Instalando Programas*

Limpe a tela do terminal.

> `clear`

#### pwd
Vídeo: *Parte 7 - Entendendo as Pastas do Sistema*

Consulte qual é o diretório de trabalho atual que o Terminal está trabalhando.

> `pwd`

#### ls
Vídeo: *Parte 7 - Entendendo as Pastas do Sistema*

Liste os diretórios e arquivos do caminho informado

> Para listar arquivos e pastas do diretório de trabalho atual: `ls`

> Para listar arquivos e pastas de um diretório específico: `ls <caminho>`

#### cd
Vídeo: *Parte 7 - Entendendo as Pastas do Sistema*

Altere o diretório atual de trabalho

> Para voltar a pasta anterior: `cd ..`

> Para avançar a uma pasta previamente selecionada: `cd -`

> Para avançar a uma nova pasta informando o caminho: `cd <caminho>/<nome da pasta>`

> Para ir a sua Pasta Pessoal: `cd` ou `cd ~`

> Para selecionar uma Pasta dentro da sua Pasta Pessoal: `cd ~<nome da pasta>`

#### mkdir
Vídeo: *Parte 8 - Criando e Apagando Pastas*

Crie um novo diretório/Pasta:

> Para criar no diretório atual de trabalho: `mkdir <nome da pasta>`

> Para criar usando caminho absoluto: `mkdir <caminho>/<nome da pasta>`

#### rmdir
Vídeo: *Parte 8 - Criando e Apagando Pastas*

Excluir um diretório/Pasta vazio:

> `rmdir <caminho>/<nome da pasta>`

#### rm
Vídeo: *Parte 9 - Trabalhando com Arquivos - Primeira Parte*

Excluir Arquivos ou Pastas do sistema. Esses arquivos são excluídos diretamente, sem ir para a lixeira.

> Para excluir um arquivo ou pasta vazia `rm <caminho>/<nome da pasta/arquivo>`

> Para excluir um pasta que tenha conteúdo dentro `rm -r <caminho>/<nome da pasta>`

#### nano
Vídeo: *Parte 9 - Trabalhando com Arquivos - Primeira Parte*

Editor de texto padrão do Terminal Ubuntu

> nano <caminho>/<nome do arquivo>

#### cp
Vídeo: *Parte 10 - Trabalhando com Arquivos - Segunda Parte*

Copiar arquivos:

> Copiar no mesmo diretório com novo nome: `cp <caminho>/<nome do arquivo original> <caminho>/<nome do novo arquivo>`

> Copiar em outro diretório com mesmo nome: `cp <caminho original>/<nome do arquivo> <novo caminho>/<nome do arquivo>`

> Copiar em outro diretório com novo nome: `cp <caminho original>/<nome do arquivo original> <novo caminho>/<nome do novo arquivo>`

