# Inicializando git local

Primeiro confira se o git está instalado:

```bash
git --version
```
Configure colocando seu nome e email :

```
>git config --global user.name "Meu Nome"
>git config --global user.email "MeuEmail@gmail.com"

```
Inicializando - Local

```
c:\users\Meu Nome>cd documents
c:\users\Meu Nome>cd documents>mkdir exemplogit
c:\users\Meu Nome>cd documents\mkdir exemplogit>git init
Initialized empty Git repository in c:/Users/Meu Nome/Documents/exemplogit/.git
```

Comandos Git
````

1-Git Status: Mostra o que está acontecendo com git add e git commit.

2-Git Add<filename ou .> :  Informa ao Git que você deseja incluir atualizações em um arquivo específico no próximo commit.

3-Git restore --staged<filename ou .> : o git restore descartará quaisquer alterações locais não confirmadas nos arquivos correspondentes e, assim, restaurará seu último estado confirmado. Com a opção --staged, o arquivo será removido apenas da Staging Area - mas não alterará suas modificações.

4-Git branch <branchname.> : O nome padrão do branch no Git é master ou main;serve para criar uma nova branch.

5-Git Checkout <branch name> : pode ser usado para criar,mudar,e conferir branches já feitos.

6-Git Checkout -b : Cria uma nova branch.

7-Git Commit -m : informar mensagem.

8-Git Push : enviar arquivos para repositório remoto.
9-Git Branch -D <branchname> : Excluir uma branch.

10-Git Fetch : Verificar alterações ou atualizações da branch.

11-Git Pull : Sincronizar/atualizar todo o conteúdo feito.

