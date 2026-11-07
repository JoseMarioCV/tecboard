modificações e novas funcionalidades
    feat ou feature/descricao-da-modificacao
EX:
"git branch" vizualiza onde voce esta
"git branch feat/descricao-da-modificacao" cria uma branch a ser modificada
"git checkout feat/descricao-da-modificacao" acessa a branch
"git branch -m feat/reanomear branch" consegue renomear a branch
"git status" identifica o que foi modificado
"git add ." adiciona a modificação no stage
"git commit -m "Explicar-o-que-foi-feito"" cria um ponto de restauração na maquina 
"git push origin" manda o codigo para o github e cria o link de acesso para o pull request
"git pull" tras o codigo com as modificaçõe do pull request do projeto

correção de problema
    fix bugfix/descrção-do-problema

modificação urgente na main
    hotfix/descricao-do-problema
 
 rincipais comandos do fluxo Git/GitHub
Comando	Descrição
git checkout -b nome-da-branch	Cria e muda para uma nova branch a partir da atual.
git branch	Lista todas as branches existentes no repositório local.
git status	Mostra os arquivos modificados e o estado da branch atual.
git add .	Adiciona todas as modificações para serem incluídas no próximo commit.
git add nome-do-arquivo	Adiciona apenas um arquivo específico.
git commit -m "mensagem"	Cria um commit com as mudanças adicionadas.
git log --oneline	Exibe o histórico de commits de forma resumida.
git push origin nome-da-branch	Envia a branch e seus commits para o repositório remoto (GitHub).
git checkout main	Volta para a branch main.
git pull origin main	Atualiza a main local com as últimas alterações do repositório remoto.
