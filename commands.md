# Comandos Git

### Configurar informações

<p>git config --global user.name Nome Sobrenome</p>
<p>git config --global user.email meu_email@exemplo</p>


### Criando o repositório

**Baixa o código fonte de um repositório remoto.**
<p>git clone "https://link-do-nome-do-repositório"</p>

**Inicia um repositório na sua máquina.**
<p>git init</p>


### Criando a branch

**Cria uma branch.**
<p>git branch "nome-da-branch"</p>

**Cria uma branch e já entra nela.**
<p>git checkout -b "nome-da-branch"</p>


### Trabalhando com branchs

**Atualiza a branch com as informações do repositório remoto.**
<p>git pull origin "nome-da-branch"</p>

**Mostra o histórico de commits.**
<p>git merge "outra-branch-que-deseja-trazer-recursos-contidos-nela"</P>

**Lista as branchs.**
<p>git branch ou git branch --list</p>

**Apaga a branch.**
<p>git branch -d "nome-da-branch"</p>

**Altera para a branch selecionada.**
<p>git checkout "nome-da-branch"</p>

**Mostra o status da branch atual.**
<p>git status</p>

**Permite salvar as modificações, trocar de branch.**
<p>git stash</p>

**Permite trazer as modificações salvas, com git stash.**
<p>git stash apply</p>


### Adicionando arquivos, escrevendo mensagens e enviando para o repositório

**Adiciona tudo, para ser commitado.**
<p>git add .</p>

**Adiciona apenas o arquivo em questão, para o commit.**
<p>git add "nome-do-arquivo"</p>

**Envia o codigo para o repositório remoto.**
<p>git push -u "local-remoto" "nome-da-branch"</p>

**Define a mensagem de referência na adição de dados.**
<p>git commit -m "mensagem do commit"</p>

**Sobe as alteração da branch para o repositório remoto.**
<p>git push origin "nome-da-branch"</p>


### Revertendo commits

**Mostra o histórico de commits.**
<p>git log -- oneline"</p>

**Reverte um commit especifico.**
<p>git revert numero-do-commit</P>
<p>após = shift + q</p>
