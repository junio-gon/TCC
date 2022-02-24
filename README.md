# TCC
# inital commit
# subi na branch 01

GIT:
--> Cadastrar-se no site do github: https://github.com/
--> Criar o seu repositório (projeto)
--> Copiar o endereço para clonagem do projeto
 ==> Abrir o git bash e executar os comandos:
	$ git clone <insira_a_url_do_projeto> [comando para clonar os projetos]
	$ cd <nome_da_pasta_do_projeto> [comando para entrar na pasta do projeto]
	$ git config --global user.name "<seu_nome>" [comando para adicionar suas credenciais - nome]
	$ git config --global user.email "seu_e-mail" [comando para adicionar suas credenciais - email]
	$ git add . [comando para adicionar as alterações]
	$ git commit -m "comentário sobre as alteracoes feitas" [comando confirmar as alterações feitas]
	$ git pull [comando para puxar a última versao do código]
	$ git push -u [comando para empurrar sua branch para o repositório remoto] / OU / $ git push --set-upstream origin <sua_branch> [somente no primeiro commit]
--> Criar as branches para o desenvolvimento dos trabalhos
--> fazer o merge das branches após a criação do pull request 