DOWNLOADS/CADASTROS:

*Cadastro no GitHub:https://github.com

*Baixar o GitHub Desktop: https://desktop.github.com

*Baixar o Git: https://git-scm.com



CONFIGURAÇÕES NO GITBASH, DEPOIS DE CRIAR O GITHUB:

- Configurar o usuário remoto no repositório local, primeiro uso do git:

  *git config --global user.email "email de criação do github"
  
  *git config --global user.name "Nome do usuário"
  
  **Imagem ilustrativa 



SINTAXE GIT/COMANDOS GITBASH ou GITHUB DESKTOP:

- Criar um novo repositório local:

  *git init 
  
  **Imagem ilustrativa

- Mudar o nome da branch master para main:

  *git branch -M <main>
  
  **Imagem ilustrativa   

- Adicionar modificações no repositório local:

  *git add .
	
  *git add <nome do arquivo>
	
  **Imagem ilustrativa

- Confirmar modificações no repositório local, criar versões de arquivo:

  *git commit -m "comentários das alteraçoes"
	
  **Imagem ilustrativa

- Gravar o endereço de envio do arquivo local depois de criar um repositório remoto no github:
	
  *git remote add origin <link do repositorio criado no github>
	
  **Imagem ilustrativa  

-Definir para qual branch deve ser enviado do arquivo local para o remoto:
	
  *git push --set-upstream origin main  
	
  **Imagem ilustrativa

- Enviar o arquivo comitado para o github tendo a branch principal renomeada
para main:
	
  *git push -u origin main
	
  **Imagem ilustrativa 

- Enviar o arquivo comitado para o github depois do primeiro commit:

  *git push
  
  **Imagem ilustrativa   

- Atualizar o servidor local com as alteracoes feitas no servidor remoto:
	
  *git pull
	
  **Imagem ilustrativa  

- Criar uma ramificação/branch nova:
	
  *git branch <branch>
	
  **Imagem ilustrativa

- Selecionar uma ramificaçao/branch:
	
  *git checkout <branch>
	
  **Imagem ilustrativa

- Deletar uma ramificação/branch:
	
  *git branch -d <branch>
	
  **Imagem ilustrativa

- Enviar uma ramificação/branch ao repositório remoto:
	
  *git push origin <branch>
	
  **Imagem ilustrativa

- Visualizar as diferenças entre ramificações/branchs antes de fazer o merge:
	
  *git diff <branch origem> <branch destino>
	
  **Imagem ilustrativa

- Preparar as ramificações/branchs depois de resolver os conflitos:
	
  *git add .
	
  *git add <nome do arquivo>

  **Imagem ilustrativa

- Unir uma ramificação/branch secundaria à ramificação/branch main:
	
  *git merge <branch>
	
  **Imagem ilustrativa



DICAS GITBASH ou GITHUB DESKTOP:

- Verificar atualização do repositório local:
	
  *git status
	
  **Imagem ilustrativa

- Verificar histórico e id de commits:
	
  *git log
	
  **Imagem ilustrativa

- Verificar histórico de commits em uma linha cada:
	
  *git log --oneline
	
  **Imagem ilustrativa

- Verificar histórico de versoes:
	
  *git reflog
	
  **Imagem ilustrativa

- Voltar/Navegar entre commits do repositorio local:

  *git reset --hard <7 primeiros digitos do id da commit escolhida>

  **Imagem ilustrativa
 
- Verificar diferenças entre commits:
	
  *git log -p
	
  **Imagem ilustrativa

- Remover todas as alterações e commits locais:
	
  *git fetch origin
	
  *git reset --hard origin/master
	
  **Imagem ilustrativa

- Copiar um repositório local/remoto:
	
  *git clone /caminho/para/o/repositório
	
  *git clone usuario@servidor:/caminho/para/o/repositório
	
  **Imagem ilustrativa

- Verificar o nome da(s) branch(s):
	
  *git branch
	
  **Imagem ilustrativa

- Rotular o commit:
	
  *git tag 1.0.0 <10 caracteres id commit>
	
  **Imagem ilustrativa

- Sobrescrever alteracoes locais:
	
  *git checkout -- <arquivo>
	
  **Imagem ilustrativa

- Interface gráfica padrão:
	
  *gitk
	
  **Imagem ilustrativa

- Usar saídas do git coloridas:
	
  *git config color.ui true
	
  **Imagem ilustrativa

- Exibir log em apenas uma linha por commit:
	
  *git config format.pretty oneline
	
  **Imagem ilustrativa  

- Fazer inclusões interativas:
	
  *git add -i
	
  **Imagem ilustrativa  

