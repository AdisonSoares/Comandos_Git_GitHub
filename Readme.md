## DOWNLOADS/CADASTROS:

*Cadastro no GitHub:https://github.com

*Baixar o GitHub Desktop: https://desktop.github.com

*Baixar o Git: https://git-scm.com



## CONFIGURAÇÕES NO GITBASH:

- `Configurar o usuário remoto no repositório local, primeiro uso do git:`

  *git config --global user.email "email de criação do github"
  
  *git config --global user.name "Nome do usuário"
  
  **Imagem ilustrativa 



## FLUXO GITBASH:

- `Criar um novo repositório local:`

  *git init 
  
  **Imagem ilustrativa

- `Mudar o nome da branch master para main:`

  *git branch -M (main)
  
  **Imagem ilustrativa   

- `Adicionar modificações no repositório local:`

  *git add .
	
  *git add (nome do arquivo)
	
  **Imagem ilustrativa

- `Confirmar modificações no repositório local, criar versões de arquivo:`

  *git commit -m (comentários das alteraçoes)
	
  **Imagem ilustrativa

- `Gravar o endereço de envio do arquivo local ao github:`
	
  *git remote add origin (link do repositorio criado no github)
	
  **Imagem ilustrativa  

- `Enviar o arquivo comitado para o github:`
	
  *git push --set-upstream origin (branch)
	
  *git push -u origin (branch)

  *git push origin (branch)

  *git push

  **Imagem ilustrativa   

- `Atualizar o servidor local com as alteracoes feitas no servidor remoto:`
	
  *git pull
	
  **Imagem ilustrativa  

- `Criar uma ramificação/branch nova:`
	
  *git branch (branch)
	
  **Imagem ilustrativa

- `Selecionar uma ramificaçao/branch:`
	
  *git checkout (branch)
	
  **Imagem ilustrativa

- `Enviar uma ramificação/branch comitada ao repositório remoto:`
	
  *git push --set-upstream origin (branch) 

  *git push -u origin (branch)

  *git push origin (branch)
	
  *git push

  **Imagem ilustrativa

- `Visualizar as diferenças entre branchs antes de fazer o merge:`
	
  *git diff (branch origem) (branch destino)
	
  **Imagem ilustrativa

- `Preparar as ramificações/branchs depois de resolver os conflitos para comitar:`
	
  *git add .
	
  *git add (nome do arquivo)

  **Imagem ilustrativa

- `Unir uma ramificação/branch secundaria à ramificação/branch main:`
	
  *git merge (branch)
	
  **Imagem ilustrativa



## FUNCIONALIDADES GITBASH:

- `Adicionar e comitar ao mesmo tempo`

  *git commit -am (comentários das alteraçoes)  

  **Imagem ilustrativa

- `Criar nova branch com base em outra e fazer checkout automatico:`

  *git checkout -b (branch nova)

  **Imagem ilustrativa  

- `Deletar uma ramificação/branch:`
	
  *git branch -D (branch)
	
  **Imagem ilustrativa

- `Visulizar os repositorios remotos:`

  *git remote -v

  **Imagem ilustrativa   

- `Desfazer um commit do arquivo:`

  *git rm --cached (nome do arquivo)

  **Imagem ilustrativa 

- `Guardar arquivos para não serem comitadas:`

  *touch .gitignore  

  **Imagem ilustrativa    

- `Verificar atualização do repositório local:`
	
  *git status
	
  **Imagem ilustrativa

- `Verificar histórico e id de commits:`
	
  *git log
	
  **Imagem ilustrativa

- `Verificar histórico de commits em uma linha cada:`
	
  *git log --oneline
	
  **Imagem ilustrativa

- `Verificar histórico de versoes:`
	
  *git reflog
	
  **Imagem ilustrativa

- `Voltar/Navegar entre commits do repositorio local:`

  *git checkout (id completo do comit escolhido) -- (nome do arquivo)

  *git reset --hard (7 caracteres id da commit)

  **Imagem ilustrativa
  
- `Verificar diferenças entre commits:`
	
  *git log -p
	
  **Imagem ilustrativa

- `Gravar dados para não precisar colocar email e senha ao fazer push`

  *git config credential.helper store

  **Imagem ilustrativa

- `Verificar ultimo ponto da commit:`
	
  *git show
	
  **Imagem ilustrativa

- `Verificar edições dentro da commit:`
	
  *git show (id completo da commit)
	
  **Imagem ilustrativa

- `Remover todas as alteracoes e commits locais:`
	
  *git fetch origin
	
  *git reset --hard origin/master
	
  **Imagem ilustrativa

- `Copiar um repositório local/remoto:`
	
  *git clone (link do repositorio clonado)
		
  **Imagem ilustrativa

- `Verificar o nome da(s) branch(s):`
	
  *git branch
	
  **Imagem ilustrativa

- `Sobrescrever alteracoes locais:`
	
  *git checkout --(arquivo)
	
  **Imagem ilustrativa  

- `Retornar um arquivo deletado antes de adicionar:`
	
  *git checkout --(arquivo)
	
  **Imagem ilustrativa  

- `Retornar um arquivo deletado antes de adicionar e comitar:`
	
  *git checkout (id completo do arquivo deletado) --(nome do arquivo deletado)
	
  **Imagem ilustrativa   


## COMANDOS DE TERMINAL:

- `Listar os conteudos do diretorio:`
	
  *ls
	
  **Imagem ilustrativa 

- `Listar os conteudos visíveis e invisíveis do diretorio:`
	
  *ls -al
	
  **Imagem ilustrativa   

- `Exibir conteudo do diretório atual:`

  *dir

  **Imagem ilustrativa  

- `Exibir o caminho do diretório atual:`

  *pwd

  **Imagem ilustrativa  

- `Mudar o diretorio atual:`
	
  *cd
	
  **Imagem ilustrativa

- `Mudar para o diretorio anterior:`
	
  *cd ..
	
  **Imagem ilustrativa  

- `Limpar a tela:`

  *clear

  **Imagem ilustrativa

- `Criar uma pasta:`

  *mkdir (pasta)

  **Imagem ilustrativa    

- `Criar uma pasta e subdiretorios:`

  *mkdir (pasta\subdiretorio\subdiretorio)

  **Imagem ilustrativa  

- `Copiar/Duplicar uma arquivo:`

  *copy

  **Imagem ilustrativa    

- `Mover/Renomear uma arquivo:`

  *move

  **Imagem ilustrativa      

- `Deletar um arquivo:`

  *del

  **Imagem ilustrativa    

- `Deletar uma pasta vazia:`

  *rmdir

  **Imagem ilustrativa  

- `Deletar uma pasta nao vazia:`

  *rmdir /s

  **Imagem ilustrativa  

- `Editar um arquivo dentro do diretorio:`

  *vim (arquivo.extensao)

  **Imagem ilustrativa

- `Sair do modo edição e salvar:`

  *wq

  **Imagem ilustrativa

- `Sair do terminal:`

  *exit

  **Imagem ilustrativa   


 

## FLUXO GITHUB:

- `Criar um repositorio:`

  *New

  *Repositories -> New

  **Imagem ilustrativa

- `Clonar um repositorio de outro:`

  *Repositories (outro perfil) -> Fork -> Repositories (proprio perfil)

  **Imagem ilustrativa

- `Alterar um repositorio de outro:`

  *Contribute -> Open pull request -> Create pull request -> Comentario -> Create pull request

  **Imagem ilustrativa  

- `Aceitar um pull request:`

  *Pull requests -> Seleciona -> Merge pull request

  **Imagem ilustrativa   

- `Não aceitar um pull request:`

  *Pull requests -> Seleciona -> Close pull request

  **Imagem ilustrativa    