# Comandos Git

### Criando o repositório

**Baixa o código fonte de um repositório remoto.**
git clone "https://link-do-nome-do-repositório"

**Inicia um repositório na sua máquina.**
git init


### Criando a branch

**Cria uma branch.**
git branch "nome-da-branch"

**Cria uma branch e já entra nela.**
git checkout -b "nome-da-branch"


### Trabalhando com branchs

**Atualiza a branch com as informações do repositório remoto.**
git pull origin "nome-da-branch"

**Mostra o histórico de commits.**
git merge "outra-branch-que-deseja-trazer-recursos-contidos-nela"

**Lista as branchs.**
git branch ou git branch --list

**Apaga a branch.**
git branch -d "nome-da-branch"

**Altera para a branch selecionada.**
git checkout "nome-da-branch"

**Mostra o status da branch atual.**
git status

**Permite salvar as modificações, trocar de branch.**
git stash

**Permite trazer as modificações salvas, com git stash.**
git stash apply


### Adicionando arquivos, escrevendo mensagens e enviando para o repositório

**Adiciona tudo, para ser commitado.**
git add .

**Adiciona apenas o arquivo em questão, para o commit.**
git add "nome-do-arquivo"

**Envia o codigo para o repositório remoto.**
git push -u "local-remoto" "nome-da-branch"

**Define a mensagem de referência na adição de dados.**
git commit -m "mensagem do commit"

**Sobe as alteração da branch para o repositório remoto.**
git push origin "nome-da-branch"


### Revertendo commits

**Mostra o histórico de commits.**
git log -- oneline"

**Reverte um commit especifico.**
git revert numero-do-commit
após = shift + q
