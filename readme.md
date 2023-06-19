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

7-Git Commit -m :envia arquivo selecionado com git add para github.

8-Git Push : enviar arquivos para repositório remoto.
9-Git Branch -D <branchname> : Excluir uma branch.

10-Git Fetch : Verificar alterações ou atualizações da branch.

11-Git Pull : Sincronizar/atualizar todo o conteúdo feito.

SSH - GitBash
Verificar se existe chave : ssh.ls -al ~/.ssh
Adicionar uma nova chave. : (ID)ssh-keygen -t ed25519 -C "your_email@example.com"
Inicializar agente-ssh.eval : "$(ssh-agent -s)"
Adicionar chave ssh ao agente : .ssh-add ~/.ssh/id_ed25519

SSH - GitBash
Copiar chave ssh : .clip < ~/.ssh/id_ed25519.pub
Adicionar chave no github : Github -> Settings -> SSH and GPG keys -> New SSH key -> Colar*Coloque um título que identifique. a chave*
Testar conexão : ssh -T git@github.com ->digite : yes
