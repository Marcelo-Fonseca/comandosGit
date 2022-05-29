#Arquivo Md  extenção Markdown,  é uma linguagem de marcação.
#Comandos GIT 
git --version -> verifica a versão instalada na maquina.
git config --global user.name "Seu Nome"
git config --global user.email seuEmail@test.com 
git list -> lista que foi feito.
git status -> mostra que esta acontecendo"mudanças a serem commitadas.

git init-> incializa o git na pasta
git add -> envia os arquvos celecionados para a area de  stage um espaço de espera, aguardando para commit .comm
mudar o nome de (Master) Para (Main)
git branch -M "main"
git commit -A = pega todos os arquivos adiciona no stage local de espera aguardando commit
git push -u origin main
git 


#Passo a Passo
 1º Passo configurar usuário.
git config --global user.name “Seu nome”
git config --global user.email seuEmail@test.com 
obs”esse email deve ser o mesmo cadastrado no github não colocar dentro “ ”. ”
git config --list   -> para listar o que foi feito.

2º Passo criar pasta do projeto
“dentro da pasta, precisa inicializar o git”
Abrir terminal git bach here 
git init -> vai criar uma pasta oculta, .git “não apagar esta pasta”
code . -> abre o vs code dentro da pasta, criar seus arquivos.

3º Passo verificar que está acontecendo e colocar branch  em espera
git status -> mostra o que está acontecendo com os arquivos
git add -A -> pega todos os arquivos e coloca em espera  
git add -”nome do "Arquivo" -> pega o arquivo específico  e coloca em espera. 

4º Passo Fazer Commit (obs “”)
git commit -m “primeiro commit” -> essa mensagem é o título deste commit.

5º Passo Criar o repositório no GitHub (obs “Criar com o mesmo nome da pasta do projeto assim evita conflitos”)
seguir passos para criação do repositório e clicar no botão  criar repositório.
voltar no terminal bash 
6º Passo Fazer Comunicação repositório pc com GitHub (obs “Faz a comunicação Repositório local com  Repositorio no GitHub ”)
git branch -M  “main”-> Mudar o nome principal(MASTER) para “main” ou seja renomear a branch principal. 
copiar link no GitHub https://github.com/marcelo-Fonseca/comandosGit.git (obs: para colar o link no terminal Ctrl +shift + insert 
git remote add origin https://github.com/marcelo-Fonseca/comandosGit.git ->. colar o link copiado do GitHub 

4º Passo Fazer Push (obs “ Vai empurrar todos os arquivos commitados para o repositório no GitHub”)
git push -u origin main 
