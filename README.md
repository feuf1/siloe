PARA INICIAR O NOVO PACKET COM GIT NA MÁQUINA
### git init

DEFINIR O NOME E O EMAIL DO USUARIO
### git config --local user.name feuf1
### git config --local user.email felipefernandesfeu@gmail.com

BAIXAR OS ARQUIVOS DO GIT
### git clone --branch <branch_name> <repository_url>
### git clone --branch 1.0 https://github.com/feuf1/3_f_solucoes_siloe.git

BAIXAR AS ALTERAÇÕES DO GIT
### git pull

LIMPARA AREA DO TERMINAL 
### cls

VERIFICAR A BRANCH
### git branch

ADICIONAR O ARQUIVO CRIADO, ADICIONANDO ARQUIVO AO ÍNDICE DE PREPARAÇÃO (STAGING ÁREA). 
o ÍNDICE DE PREPARAÇÃO É UMA ÁREA INTERMEDIÁRIA ENTRE O DICIONARIO DE TRABALHO (WORKING DIRECTORY) E O REPOSITÓRIO GIT. 
### git add <file>
### git add README1.md

ADICIONA TODOS OS ARQUIVOS DE UMA SÓ VEZ
### git add .

VERIFICA O STATUS DO ARQUIVO NO REPOSTÓRIO
### git status

REPRESENTA UM CONJUNTO DE ALTERAÇÕES EM UM PONTO ESPECÍFICOS DA HISTÓRIA DO SEU PROJETO, REGISTRA APENAS AS ALTERAÇÕES ADICIONADAS AO ÍNDICE DE PREPARAÇÃO.
O COMANDO -m PERMITE QUE INSIRA A MENSAGEM DE commit DIRETAMENTE NA LINHA DE COMANDO 
### git commit -m "criar página inicial do site"