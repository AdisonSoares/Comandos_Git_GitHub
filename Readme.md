## DOWNLOADS/CADASTROS:

*Cadastro no GitHub: https://github.com

*Baixar o GitHub Desktop: https://desktop.github.com

*Baixar o Git: https://git-scm.com



## CONFIGURAÇÕES NO GITBASH:

- `Criar uma chave privada publica:`

  *ssh-keygen -t rsa -b 4096 -C (email cadastrado no github)

- `Configurar o usuário remoto no repositório local, primeiro uso do git:`

  *git config --global user.email "email de criação do github"
  
  *git config --global user.name "Nome do usuário"  
   
- `Gravar dados para não precisar colocar email e senha ao fazer push`

  *git config credential.helper store


## FLUXO GITBASH:

- `Criar um novo repositório local:`

  *git init 
  

- `Mudar o nome da branch master para main:`

  *git branch -M (main)
  
- `Adicionar modificações no repositório local:`

  *git add .
	
  *git add (nome do arquivo)
	

- `Confirmar modificações no repositório local, criar versões de arquivo:`

  *git commit -m (comentários das alteraçoes)
	

- `Gravar o endereço de envio do arquivo local ao github:`
	
  *git remote add origin (link do repositorio criado no github)
	
- `Enviar o arquivo comitado para o github` e
- `Enviar uma branch/ramificação comitada ao repositório remoto:`
	
  *git push --set-upstream origin (branch)
	
  *git push -u origin (branch)

  *git push origin (branch)

  *git push

- `Atualizar o servidor local com as alteracoes feitas no servidor remoto:`
	
  *git pull
	
- `Criar uma branch/ramificação nova:`
	
  *git branch (branch)
	
- `Selecionar uma branch/ramificaçao:`
	
  *git checkout (branch)
	
- `Comparar o que foi mudado no arquivo antes de commitar:`
	
  *git diff
	
- `Preparar as branchs/ramificações depois de resolver os conflitos para comitar:`
	
  *git add .
	
  *git add (nome do arquivo)

- `Unir uma branch/ramificação secundaria à branch/ramificação main:`
	
  *git merge (branch)
	

## FUNCIONALIDADES GITBASH:

### ARQUIVAMENTO
- `Adicionar e comitar ao mesmo tempo`

  *git commit -am (comentários das alteraçoes)  

- `Guardar arquivos para não serem comitadas:`

  *touch .gitignore  

- `Copiar um repositório local/remoto:`
	
  *git clone (link do repositorio clonado)
		
- `Criar nova branch com base em outra e fazer checkout automatico:`

  *git checkout -b (branch nova)

  
### EDIÇAO
- `Descartar mudanças feitas antes de adicionar:`

  *git checkout (arquivo modificado)

- `Descartar mudanças feitas depois de adicionar:`

  *git reset HEAD

- `Desfazer um commit do arquivo:`

  *git rm --cached (nome do arquivo)

- `Voltar ao estado antes do commit:`

  *git revert --no-edit (id do ultimo commit)    

- `Voltar/Navegar entre commits do repositorio local:`

  *git checkout (7 caracteres id da commit)

  *git reset --soft (7 caracteres id da commit)

  *git reset --mixed (7 caracteres id da commit)  

- `Sobrescrever alteracoes locais:`
	
  *git checkout --(arquivo)
	
- `Retornar um arquivo deletado antes de adicionar:`
	
  *git checkout --(arquivo)
	
- `Retornar um arquivo deletado antes de adicionar e comitar:`
	
  *git checkout (id completo do arquivo deletado) --(nome do arquivo deletado)
	
- `Desfazer uma edição antes do commit em um arquivo especifico:`
	
  *git checkout HEAD -- (arquivo)
	

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
	
  *git show (id completo da commit)
	
- `Visualizar o nome da(s) branch(s):`
	
  *git branch

- `Visualizar o nome dos arquivos que foram editados:`
	
  *git diff --name-only
	
- `Visualizar o que foi modificado dentro de um arquivo especifico:`
	
  *git diff (arquivo)
	
- `Visualizar as diferenças entre branchs antes de fazer o merge:`
	
  *git diff (branch origem) (branch destino)
	
### EXCLUSAO
- `Deletar uma branch/ramificação:`
	
  *git branch -D (branch)
 
  *git push origin :(branch)
	
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

  *mkdir (pasta\subdiretorio\subdiretorio)

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

  *vim (arquivo.extensao)

- `Sair do modo edição e salvar:`

  *wq

- `Criar arquivos e documentos:`

  *touch (nome e extensao)

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

  *Repositories (outro perfil) -> Fork -> Repositories (proprio perfil)

- `Alterar um repositorio de outro:`

  *Contribute -> Open pull request -> Create pull request -> Comentario -> Create pull request

- `Aceitar um pull request:`

  *Pull requests -> Seleciona -> Merge pull request

- `Não aceitar um pull request:`

  *Pull requests -> Seleciona -> Close pull request

      