![GitHub](https://img.shields.io/github/license/AdisonSoares/Comandos_Git_GitHub)

## DOWNLOADS/CADASTROS:

*Cadastro no GitHub: https://github.com

*Baixar o GitHub Desktop: https://desktop.github.com

*Baixar o Git: https://git-scm.com

## REGRAS PARA COMMITS SUAS MENSAGENS E ORGANIZAÇÃO DE ARQUIVOS

*Commitar ao fanalizar um arquivo com o mesmo tema, podendo ir adicionando e commitar ao final e fazer uma mensagem de resumo.

*Cada arquivo modificado deve ter uma mensagem referente ao proprio arquivo e não a outros arquivos modificados caso tenham temas diferentes.

*Arquivos devem ser organizados por ordem numerica ou tema alfabetico, de preferencia nomeando com inicial maiuscula a menos que um convenção ensine o contrario.




## CONFIGURAÇÕES NO GITBASH:

- `Criar uma chave privada publica:`

  *ssh-keygen -t rsa -b 4096 -C (email cadastrado no github)

- `Configurar o usuário remoto no repositório local, primeiro uso do git:`

  *git config --global user.email "Email de criação do github"
  
  *git config --global user.name "Nome do usuário"  
  
  *git config --global core.editor "code.exe" 
   
- `Gravar dados para não precisar colocar email e senha ao fazer push`

  *git config credential.helper store

- `Mudar o nome da branch master para main de forma permanente:`

  *git config --global init.defaultBranch main


## FLUXO GITBASH:

- `Criar um novo repositório local:`

  *git init 
  

- `Mudar o nome da branch master para main:`

  *git branch -M (Main)


- `Adicionar modificações no repositório local:`

  *git add .
	
  *git add (Nome do arquivo)
	

- `Confirmar modificações no repositório local, criar versões de arquivo:`

  *git commit -m (Comentários das alteraçoes)
	

- `Gravar o endereço de envio do arquivo local ao github:`
	
  *git remote add origin (Link do repositorio criado no github)
	
- `Enviar o arquivo comitado ao github: `
	
  *git push --set-upstream origin (Branch)
	
  *git push -u origin (Branch)

  *git push origin (Branch)

  *git push

- `Resolver problemas com o push:`

  *git push origin main -f

- `Atualizar o servidor local com as alteracoes feitas no servidor remoto:`
	
  *git pull
	
- `Criar uma branch/ramificação nova:`
	
  *git branch (Branch)
	
- `Selecionar uma branch/ramificaçao:`
	
  *git checkout (Branch)
	
- `Comparar o que foi mudado no arquivo antes de commitar:`
	
  *git diff
	
- `Preparar as branchs/ramificações depois de resolver os conflitos para comitar:`
	
  *git add .
	
  *git add (Nome do arquivo)

- `Unir uma branch/ramificação secundaria à branch/ramificação main:`
	
  *git merge (Branch)
	

## FUNCIONALIDADES GITBASH:

### ARQUIVAMENTO
- `Adicionar e comitar ao mesmo tempo`

  *git commit -am (Comentários das alteraçoes)  

- `Guardar arquivos para não serem comitadas:`

  *touch .gitignore  

- `Copiar um repositório local/remoto:`
	
  *git clone (Link do repositorio clonado)
		
- `Criar nova branch com base em outra e fazer checkout automatico:`

  *git checkout -b (Branch nova)

- `Fazer download das alterações que estão no github:`

  *git fetch

  
### EDIÇAO
- `Descartar mudanças feitas antes de adicionar:`

  *git checkout (Arquivo modificado)

- `Descartar mudanças feitas depois de adicionar:`

  *git reset HEAD

- `Desfazer um commit do arquivo:`

  *git rm --cached (Nome do arquivo)

- `Voltar ao estado antes do commit:`

  *git revert --no-edit (Id do ultimo commit)    

- `Voltar/Navegar entre commits do repositorio local:`

  *git checkout (7 caracteres id da commit)

  *git reset --soft (7 caracteres id da commit)

  *git reset --mixed (7 caracteres id da commit)  

- `Sobrescrever alteracoes locais:`
	
  *git checkout --(Arquivo)
	
- `Retornar um arquivo deletado antes de adicionar:`
	
  *git checkout --(Arquivo)
	
- `Retornar um arquivo deletado antes de adicionar e comitar:`
	
  *git checkout (Id completo do arquivo deletado) --(Nome do arquivo deletado)
	
- `Desfazer uma edição antes do commit em um arquivo especifico:`
	
  *git checkout HEAD -- (Arquivo)
	

### VISUALIZAÇAO
- `Visualizar atualização do repositório local:`
	
  *git status
	
- `Visualizar histórico e id de commits:`
	
  *git log
	
- `Visualizar histórico de versoes:`
	
  *git reflog
	
- `Visualizar histórico de commits de forma grafica:`
	
  *git log --graph
	
- `Visualizar histórico de commits em uma linha cada, ignorando o commit atual:`
	
  *git log --oneline
	
- `Verificar histórico de commits da branch principal de forma grafica em uma linha:`
	
  *git log --oneline --graph
	
- `Verificar histórico de commits de forma grafica em uma linha de outras branchs:`
	
  *git log --oneline --graph --all
	
- `Visualizar histórico de commits em uma linha cada, incluindo o commit atual:`
	
  *git log --oneline --all
	
- `Visualizar histórico de commits em uma linha cada, incluindo o commit atual e o que foi modificado:`
	
  *git log --oneline --all --decorate
	
- `Visualizar os repositorios remotos:`

  *git remote

- `Visualizar os repositorios remotos de forma detalhada:`

  *git remote -v

- `Visualizar ultimo ponto da commit:`
	
  *git show
	
- `Visualizar diferenças entre commits:`
	
  *git log -p
	
- `Visualizar edições dentro da commit:`
	
  *git show (Id completo da commit)
	
- `Visualizar o nome da(s) branch(s):`
	
  *git branch

- `Visualizar o nome dos arquivos que foram editados:`
	
  *git diff --name-only
	
- `Visualizar o que foi modificado dentro de um arquivo especifico:`
	
  *git diff (Arquivo)
	
- `Visualizar as diferenças entre branchs antes de fazer o merge:`
	
  *git diff (Branch origem) (Branch destino)
	
### EXCLUSAO
- `Deletar uma branch/ramificação:`
	
  *git branch -D (Branch)
 
  *git push origin :(Branch)
	
- `Deletar uma commit do repositorio local:`

  *git reset --hard (7 caracteres id da commit)

- `Remover todas as alteracoes e commits locais:`
	
  *git fetch origin
	
  *git reset --hard origin/master
	

## COMANDOS DE TERMINAL:

- `Listar os conteudos do diretorio:`
	
  *ls
	
- `Listar os conteudos visíveis e invisíveis do diretorio:`
	
  *ls -al
	
- `Exibir conteudo do diretório atual:`

  *dir

- `Exibir o caminho do diretório atual:`

  *pwd

- `Mudar o diretorio atual:`
	
  *cd

- `Mudar para o diretorio anterior:`
	
  *cd ..
	
- `Limpar a tela:`

  *clear

- `Criar uma pasta:`

  *mkdir (pasta)
 
- `Criar uma pasta e subdiretorios:`

  *mkdir (Pasta\Subdiretorio\Subdiretorio)

- `Copiar/Duplicar uma arquivo:`

  *copy

- `Mover/Renomear uma arquivo:`

  *move    

- `Deletar um arquivo:`

  *del

- `Deletar uma pasta vazia:`

  *rmdir

- `Deletar uma pasta nao vazia:`

  *rmdir /s

- `Editar um arquivo dentro do diretorio:`

  *vim (Arquivo.extensao)

- `Sair do modo edição e salvar:`

  *wq

- `Criar arquivos e documentos:`

  *touch (Nome e extensao)

- `Abrir o VSCode no diretorio do projeto depois de configurar:`

  *code .

- `Sair do terminal:`

  *exit


## FLUXO GITHUB:

- `Cadastrar uma chave publica para atualização do github por meio do git:`

  *Settings -> SSH and GPG Keys
  -> New SSH key 
  ->Title(Local de criação)

  -> Key (Colar a chave publica) 

  -> Add SSH key

- `Criar um repositorio:`

  *New

  *Repositories -> New

- `Clonar um repositorio de outro:`

  *Repositories (Outro perfil) -> Fork -> Repositories (Proprio perfil)

- `Alterar um repositorio de outro:`

  *Contribute -> Open pull request -> Create pull request -> Comentario -> Create pull request

- `Aceitar um pull request:`

  *Pull requests -> Seleciona -> Merge pull request

- `Não aceitar um pull request:`

  *Pull requests -> Seleciona -> Close pull request

- `Criar um novo arquivo dentro do repositorio:`

  *Create new file -> nomear -> commitar -> commit new file

- `Criar um novo arquivo dentro do repositorio com nova pasta:`

  *Create new file -> nomear/ -> nomear -> commitar -> commit new file
- `Criar um novo arquivo dentro do repositorio:`

  *Create new file -> nomear -> commitar -> commit new file

- `Criar um novo arquivo dentro do repositorio com nova pasta:`

  *Create new file -> nomear/ -> nomear -> commitar -> commit new file  

- `Hospedar gratuitamente um site de forma limitada:`

  *Repositories -> New -> Manage topcs 
  -> Criar palavras chave
  -> Upload files  
  -> Commit changes 
  -> Settings -> Github pages
  -> None -> Master/Main branch
  -> Link criado
  -> Copiar o link 
  -> Editar titulo -> Web Site (colar)
  
- `Criar um projeto estilo kanban:`

  *Projects -> Create a project
  -> Nomear
  -> Descrever
  -> Create project
  -> Add a column 
  -> 1° "To Do"
  -> Create column
  -> Add a column
  -> 2° "In Progress"
  -> Create column
  -> Add a column
  -> 3° "Done"
  -> Create column
  -> Criar cartao -> + -> Add


## GITHUB NO ECLIPSE

- `Criar um repositorio do eclipse:`

  *Botao direito no projeto -> Team -> Share Projects
  -> Selecionar local do repositorio -> Create -> Cancel

- `Integrar o eclipse ao github:`

  *Add file (Dentro do github) -> Upload files 
  -> Cola/Seleciona a pasta do repositorio
  -> Commit changes

- `Resolver o problema do push no eclipse:`

  *Settings(Dentro do github) -> Developer settings ->
  -> Personal acess tokens -> Generete new tokken
  -> Nomear -> Data Expiration -> Select scopees
  -> repo -> adminrepo_hook -> delete_repo -> Generate tokken
  -> Salvar o tokken -> Ao enviar o commit -> Password
  -> Colar tokken
     
- `Resolver o problema do acento das palavras clonadas:`

  *Botao direito no projeto -> Properties -> Resource -> Text from container 
  ->Other -> UTF-8 

- `Exibir a area de trabalho do git:`

  *Window -> Show View -> Other -> Git -> Git Staging -> Open
  -> Git Repositores -> Open


## GITHUB NO VSCODE

- `Integrar o vs code ao git:`

  *Clica no simbolo de ramificação -> Initialize Repository 

- `Integrar o vs code ao git:`

  *Clica nos tres ponto -> Show git output -> Terminal
  -> Git remote add origin (link do repositorio remoto)
