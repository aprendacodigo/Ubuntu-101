##Alterando a variável de ambiente PS1
A variável PS1 é a que controla como é mostrado o prompt de comando no Terminal.

No Ubuntu, por padrão ela é:

`\[\e]0;\u@\h: \w\a]${debian_chroot:+($debian_chroot)}\u@\h:\w\$`

As opções disponíveis para alterá-la são:

* \a : caracter ASCII 007
* \d : a data no formato "Semana Mês Dia" (exemplo "Sex Jul 24")
* \D{format} :	O tempo atual no formato usando strftime(3). Se deixar em branco, será usado o formato da máquina. As chaves são obrigatórias.
* \e : caracter ASCII 033
* \h : o nome da máquina (primeiro nível do domínio)
* \H : o nome completo da máquina
* \j : o número de processos que o terminal está rodando
* \l : the basename of the shell’s terminal device name
* \n : nova linha
* \r : quebra de linha
* \s : the name of the shell, the basename of $0 (the portion following the final slash)
* \t : a hora atual no formato 24-horas HH:MM:SS
* \T : a hora atual no formato 12-horas HH:MM:SS
* \@ : a hora atual no formato am/pm
* \A : a hora atual no formato 24-horas HH:MM
* \u : a conta de usuário logada
* \v : a versão do bash (exemplo: 2.00)
* \V : a versão do bash, com versão e patch (exemplo: 2.00.0)
* \w : o diretório de trabalho atual, com $HOME abreviado por "~"
* \W : o nome do diretório atual, sem o caminho, com $HOME abreviado por "~"
* \! : o número desse comando no histórico
* \# : o número de comando do comando
* \$ : se o usuário for superusuario mostra #, senão mostra $
* \nnn : o caracter correspondente ao código nnn
* \\ : mostra a barra invertida
* \[ : inicia uma sequencia de caracteres
* \] : termina a sequencia de caracteres
* \$(__git_ps1) : mostra o branch do Git
