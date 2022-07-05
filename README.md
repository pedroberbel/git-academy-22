# git-academy-22


## git init
Inicialização de um projeto:
```
git init 
```
## Configurações iniciais
```bash
git config --global user.name "username"
git config --global user.email "user@email"
```

## Controle de alterações 
Para visualizar as alterações feitas, vamos usar: 
```bash
git status 
```

## Criando Commits 
Primeiramente precisamos adicionar as mudanças e enfim 'commitar':
- utilize o ponto para adicionar todas as alterações do projeto.
```bash
git add .
git commit -m "descricao das alteracoes"
```

## Branches 
Podemos ramificar o código usando branches para criar uma nova, executamos:
```bash
git switch --create <nome-nova-branch>
ou
git checkout -b <nome-nova-branch>
```
- Listando Branches criadas:
```bash 
git branch
```
- Apagando branch
```bash
git branch -D <nome-da-branch>
```

## GitHub 
- Adicionando um remote origin:
```bash 
git remote add origin <link do .git no github>
```
- Subindo alterações:
```bash
git push origin <nome-da-branch>
# caso a branch nao exista no GitHub use:
git push -u origin <nome-da-branch>
```