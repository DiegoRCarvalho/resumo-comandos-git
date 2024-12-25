# Git Resumo

## Define seu nome de usuário.

~~~
git config --global user.name "Seu Nome"
~~~

## Define seu email.

~~~
git config --global user.email "seuemail@example.com"
~~~

## Define seu editor de configurações do git.

- ```--local```
- ```--global```
- ```--system```

~~~
git config --global core.editor code
~~~

## Edite as configurações do seu git.

~~~
git config --global --edit
~~~

Exemplo de arquivo com atalhos que mais gosto.

~~~
[user]
  name = SeuNomeDeUsuario
  email = usuario@email.com
[init]
  defaultBranch = main
[core]
  editor = code --wait

[alias]
  s = !git status -s
  c = !git add --all && git commit -m
  l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'

[push]
  followTags = true
~~~

## Criar um repositório Git vazio.

~~~
git init
~~~

## Criar e selecionar uma nova branch.

~~~
git checkout -b nomeNovaBranch
~~~

## Ver todas as branches existentes e descobrir qual está selecionada.

~~~
git branch -a
~~~

## Para selecionar uma branch diferente.

~~~
git checkout nomeDaBranch
~~~

## Para clonar um repositório.

~~~
git clone url-do-repositorio
~~~

## Verificar o status das mudanças.

~~~
git status
~~~

## Ver o histórico de commits.

~~~
git log
~~~

## Adiciona todos os arquivos que ainda não estão rastreados ao repositório do Git.

~~~
git add .
~~~

## Adiciona arquivos específicos que ainda não estão rastreados ao repositório do Git.

~~~
git add arquivo1 arquivo2 arquivo3
~~~

## Fazer um commit.

~~~
git commit -m "Mensagem descritiva das mudanças"
~~~

## Alterar a mensagem do último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git commit --amend -m "nova mensagem"
~~~

## Adicionar novos arquivos ao último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git add novoArquivo
git commit --amend --no-edit
~~~

## Atualizar o repositório local com as mudanças remotas.

~~~
git push
~~~

## Enviar mudanças para o repositório remoto.

~~~
git pull
~~~

## Enviar a branch local nomeDaBranch para o repositório remoto (no exemplo, chamado origin).

Estabelece o rastreamento entre a branch local nomeDaBranch e a branch remota origin/formularios. Isso significa que, a partir de então, comandos como git pull e git push funcionarão diretamente, sem precisar especificar o repositório e a branch remota.

~~~
git push --set-upstream origin nomeDaBranch
~~~

## Unir uma branch ao repositório principal (merge).
~~~
git checkout nome-da-branch-principal
git merge nome-da-branch-que-sera-adicionada-a-main
~~~
# Git Resumo

## Define seu nome de usuário.

~~~
git config --global user.name "Seu Nome"
~~~

## Define seu email.

~~~
git config --global user.email "seuemail@example.com"
~~~

## Define seu editor de configurações do git.

- ```--local```
- ```--global```
- ```--system```

~~~
git config --global core.editor code
~~~

## Edite as configurações do seu git.

~~~
git config --global --edit
~~~

Exemplo de arquivo com atalhos que mais gosto.

~~~
[user]
  name = SeuNomeDeUsuario
  email = usuario@email.com
[init]
  defaultBranch = main
[core]
  editor = code --wait

[alias]
  s = !git status -s
  c = !git add --all && git commit -m
  l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'

[push]
  followTags = true
~~~

## Criar um repositório Git vazio.

~~~
git init
~~~

## Criar e selecionar uma nova branch.

~~~
git checkout -b nomeNovaBranch
~~~

## Ver todas as branches existentes e descobrir qual está selecionada.

~~~
git branch -a
~~~

## Para selecionar uma branch diferente.

~~~
git checkout nomeDaBranch
~~~

## Para clonar um repositório.

~~~
git clone url-do-repositorio
~~~

## Verificar o status das mudanças.

~~~
git status
~~~

## Ver o histórico de commits.

~~~
git log
~~~

## Adiciona todos os arquivos que ainda não estão rastreados ao repositório do Git.

~~~
git add .
~~~

## Adiciona arquivos específicos que ainda não estão rastreados ao repositório do Git.

~~~
git add arquivo1 arquivo2 arquivo3
~~~

## Fazer um commit.

~~~
git commit -m "Mensagem descritiva das mudanças"
~~~

## Alterar a mensagem do último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git commit --amend -m "nova mensagem"
~~~

## Adicionar novos arquivos ao último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git add novoArquivo
git commit --amend --no-edit
~~~

## Atualizar o repositório local com as mudanças remotas.

~~~
git push
~~~

## Enviar mudanças para o repositório remoto.

~~~
git pull
~~~

## Enviar a branch local nomeDaBranch para o repositório remoto (no exemplo, chamado origin).

Estabelece o rastreamento entre a branch local nomeDaBranch e a branch remota origin/formularios. Isso significa que, a partir de então, comandos como git pull e git push funcionarão diretamente, sem precisar especificar o repositório e a branch remota.

~~~
git push --set-upstream origin nomeDaBranch
~~~

## Unir uma branch ao repositório principal (merge).
~~~
git checkout nome-da-branch-principal
git merge nome-da-branch-que-sera-adicionada-a-main
~~~
# Git Resumo

## Define seu nome de usuário.

~~~
git config --global user.name "Seu Nome"
~~~

## Define seu email.

~~~
git config --global user.email "seuemail@example.com"
~~~

## Define seu editor de configurações do git.

- ```--local```
- ```--global```
- ```--system```

~~~
git config --global core.editor code
~~~

## Edite as configurações do seu git.

~~~
git config --global --edit
~~~

Exemplo de arquivo com atalhos que mais gosto.

~~~
[user]
  name = SeuNomeDeUsuario
  email = usuario@email.com
[init]
  defaultBranch = main
[core]
  editor = code --wait

[alias]
  s = !git status -s
  c = !git add --all && git commit -m
  l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'

[push]
  followTags = true
~~~

## Criar um repositório Git vazio.

~~~
git init
~~~

## Criar e selecionar uma nova branch.

~~~
git checkout -b nomeNovaBranch
~~~

## Ver todas as branches existentes e descobrir qual está selecionada.

~~~
git branch -a
~~~

## Para selecionar uma branch diferente.

~~~
git checkout nomeDaBranch
~~~

## Para clonar um repositório.

~~~
git clone url-do-repositorio
~~~

## Verificar o status das mudanças.

~~~
git status
~~~

## Ver o histórico de commits.

~~~
git log
~~~

## Adiciona todos os arquivos que ainda não estão rastreados ao repositório do Git.

~~~
git add .
~~~

## Adiciona arquivos específicos que ainda não estão rastreados ao repositório do Git.

~~~
git add arquivo1 arquivo2 arquivo3
~~~

## Fazer um commit.

~~~
git commit -m "Mensagem descritiva das mudanças"
~~~

## Alterar a mensagem do último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git commit --amend -m "nova mensagem"
~~~

## Adicionar novos arquivos ao último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git add novoArquivo
git commit --amend --no-edit
~~~

## Atualizar o repositório local com as mudanças remotas.

~~~
git push
~~~

## Enviar mudanças para o repositório remoto.

~~~
git pull
~~~

## Enviar a branch local nomeDaBranch para o repositório remoto (no exemplo, chamado origin).

Estabelece o rastreamento entre a branch local nomeDaBranch e a branch remota origin/formularios. Isso significa que, a partir de então, comandos como git pull e git push funcionarão diretamente, sem precisar especificar o repositório e a branch remota.

~~~
git push --set-upstream origin nomeDaBranch
~~~

## Unir uma branch ao repositório principal (merge).
~~~
git checkout nome-da-branch-principal
git merge nome-da-branch-que-sera-adicionada-a-main
~~~
# Git Resumo

## Define seu nome de usuário.

~~~
git config --global user.name "Seu Nome"
~~~

## Define seu email.

~~~
git config --global user.email "seuemail@example.com"
~~~

## Define seu editor de configurações do git.

- ```--local```
- ```--global```
- ```--system```

~~~
git config --global core.editor code
~~~

## Edite as configurações do seu git.

~~~
git config --global --edit
~~~

Exemplo de arquivo com atalhos que mais gosto.

~~~
[user]
  name = SeuNomeDeUsuario
  email = usuario@email.com
[init]
  defaultBranch = main
[core]
  editor = code --wait

[alias]
  s = !git status -s
  c = !git add --all && git commit -m
  l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'

[push]
  followTags = true
~~~

## Criar um repositório Git vazio.

~~~
git init
~~~

## Criar e selecionar uma nova branch.

~~~
git checkout -b nomeNovaBranch
~~~

## Ver todas as branches existentes e descobrir qual está selecionada.

~~~
git branch -a
~~~

## Para selecionar uma branch diferente.

~~~
git checkout nomeDaBranch
~~~

## Para clonar um repositório.

~~~
git clone url-do-repositorio
~~~

## Verificar o status das mudanças.

~~~
git status
~~~

## Ver o histórico de commits.

~~~
git log
~~~

## Adiciona todos os arquivos que ainda não estão rastreados ao repositório do Git.

~~~
git add .
~~~

## Adiciona arquivos específicos que ainda não estão rastreados ao repositório do Git.

~~~
git add arquivo1 arquivo2 arquivo3
~~~

## Fazer um commit.

~~~
git commit -m "Mensagem descritiva das mudanças"
~~~

## Alterar a mensagem do último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git commit --amend -m "nova mensagem"
~~~

## Adicionar novos arquivos ao último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git add novoArquivo
git commit --amend --no-edit
~~~

## Atualizar o repositório local com as mudanças remotas.

~~~
git push
~~~

## Enviar mudanças para o repositório remoto.

~~~
git pull
~~~

## Enviar a branch local nomeDaBranch para o repositório remoto (no exemplo, chamado origin).

Estabelece o rastreamento entre a branch local nomeDaBranch e a branch remota origin/formularios. Isso significa que, a partir de então, comandos como git pull e git push funcionarão diretamente, sem precisar especificar o repositório e a branch remota.

~~~
git push --set-upstream origin nomeDaBranch
~~~

## Unir uma branch ao repositório principal (merge).
~~~
git checkout nome-da-branch-principal
git merge nome-da-branch-que-sera-adicionada-a-main
~~~
# Git Resumo

## Define seu nome de usuário.

~~~
git config --global user.name "Seu Nome"
~~~

## Define seu email.

~~~
git config --global user.email "seuemail@example.com"
~~~

## Define seu editor de configurações do git.

- ```--local```
- ```--global```
- ```--system```

~~~
git config --global core.editor code
~~~

## Edite as configurações do seu git.

~~~
git config --global --edit
~~~

Exemplo de arquivo com atalhos que mais gosto.

~~~
[user]
  name = SeuNomeDeUsuario
  email = usuario@email.com
[init]
  defaultBranch = main
[core]
  editor = code --wait

[alias]
  s = !git status -s
  c = !git add --all && git commit -m
  l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'

[push]
  followTags = true
~~~

## Criar um repositório Git vazio.

~~~
git init
~~~

## Criar e selecionar uma nova branch.

~~~
git checkout -b nomeNovaBranch
~~~

## Ver todas as branches existentes e descobrir qual está selecionada.

~~~
git branch -a
~~~

## Para selecionar uma branch diferente.

~~~
git checkout nomeDaBranch
~~~

## Para clonar um repositório.

~~~
git clone url-do-repositorio
~~~

## Verificar o status das mudanças.

~~~
git status
~~~

## Ver o histórico de commits.

~~~
git log
~~~

## Adiciona todos os arquivos que ainda não estão rastreados ao repositório do Git.

~~~
git add .
~~~

## Adiciona arquivos específicos que ainda não estão rastreados ao repositório do Git.

~~~
git add arquivo1 arquivo2 arquivo3
~~~

## Fazer um commit.

~~~
git commit -m "Mensagem descritiva das mudanças"
~~~

## Alterar a mensagem do último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git commit --amend -m "nova mensagem"
~~~

## Adicionar novos arquivos ao último commit (apenas se ainda não enviou para o repositório remoto).

~~~
git add novoArquivo
git commit --amend --no-edit
~~~

## Atualizar o repositório local com as mudanças remotas.

~~~
git push
~~~

## Enviar mudanças para o repositório remoto.

~~~
git pull
~~~

## Enviar a branch local nomeDaBranch para o repositório remoto (no exemplo, chamado origin).

Estabelece o rastreamento entre a branch local nomeDaBranch e a branch remota origin/formularios. Isso significa que, a partir de então, comandos como git pull e git push funcionarão diretamente, sem precisar especificar o repositório e a branch remota.

~~~
git push --set-upstream origin nomeDaBranch
~~~

## Unir uma branch ao repositório principal (merge).
~~~
git checkout nome-da-branch-principal
git merge nome-da-branch-que-sera-adicionada-a-main
~~~
