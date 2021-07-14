# Aqui você encontra instruções de comandos do Git, terminal Linux e Windows, com algumas explicações como funciona cada comando

###### Meus **contatos**

  * meu instagram: [@talysonxx](https://instagram.com/talysonxx)
  * meu email: talysonoficial12@gmail.com
  * meu linkedIn:  [Talyson André](https://www.linkedin.com/in/talyson-andré-101897170/)



## Comandos Git

**Primeira vez no git:**

* git config --global user.email "email@gmail"
* git config --global user.name "nome"

_pra mudar (apagar):_

* git config --global --unset user.email

* git config --global --unset user.name

* git config --list
  (lista as configurações)

* git config --global core.editor code -wait
  (visual studio code)

* git config --global core.editor subl -wait
  (adicionando editor no git; sublime text)

* git config user.name

* git config user.email

* git config user.core.editor

**Criando um repositorio local:**

* git init (inicio)

* git add *

* git add .
  (adiciono todos os arquivos no git)

* git status

* git commit -m "mensagem do commit"

**Depois de criar o repositório remoto no git, passe os seguintes comandos para relacioná-lo ao remoto:**

* git remote add origin linkDoRepositorioDoGitHub.git
  (adicionando repositório remoto ao servidor)
* git branch -M main
* git remote -v
  (lista urls dos repositórios remotos)
* git push -u origin main
  (levando commits do remoto para o servidor)
* git pull origin main
  (trazendo commits do servidor para o local)

**Trazendo do remoto para o local:**

* git clone linkNoGitHub.git nomeDaPastaOndeVãoFicarOsArquivos

**:**

* git diff
  (vejo as alterações nos arquivos)

* git log -1
  (histórico de commits, "q" para fechar; último commit)

**Caso você queira ignorar um arquivo ao fazer o commit:**

* echo > .gitignore
  (criando um arquivo .gitignore (no windows, no caso); nele você adiciona quais você não quer rastrar, exemplo: test_2.html/)

**Voltando em algum ponto da história:**

* git log
  (pra você ver os arquivos e histórico do commit, pra saber aonde quer voltar)

* git checkout codigoDoCommit
  (voltando pro passado, no tempo do commit)

* git checkout main
  (voltando pro presente)

**Criando ramificações:**
* git branch
(lista as ramificações)

* git branch nomeDaRamificação
  (cria uma ramificação com esse nome)

* git checkout nomeDaRamificação
  (entra na ramificação com o nome)

**Fazendo merges (unindo branchs):**

* (fique dentro da ramificação em que você quer que tu vá pra ela)
  git murge nomeDaRamificação

**Deletando branchs:**

* git branch -D nomeDaRamificação

**:**

* xxxx