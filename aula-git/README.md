# Aula de Git

Listas dos principais comandos utilizados:


## Passos iniciais:

**1º.** realizar a configuração do Git presente no arquivo  ``.gitconfig``:
```bash
git config --global user.name "Seu Nome" 

git config --global user.email "Seu email"
```
**2º.** listar as configurações setadas anteriormente
```bash
git config --list
```

## Lidando com um repositório local:

Criar um novo repositório:
```bash
git init
```

Verificar o estado do repositório:

```bash
git status
```

Adicionar um arquivo/diretório específico
```bash
git add meuTexto.txt
git add meuDiretorio
```

Para adicionar todos os arquivos ao repositório:

```bash
git add .
```
ou
```bash
git add -A
```

Remover um arquivo/diretório:
```bash
git rm meuArquivo.txt
git rm meuDiretorio
```

Para adicionar uma mensagem(indentificação) nas alterações a serem feitas no projeto:

```bash
git commit -m "escreva  aqui a sua mensagem"
```

Enviar as alterações para um repositório remoto(serve apenas para o primeiro push):
```bash
git push origin master
```

Push posteriores:
```bash
git push 
```

Visualizar o histórico de modificações no projeto 

```bash
git log
```

Atualizar o repositório loca:
```bash
git pull
```

## Lidando com Branches

Criar e selecionar uma nova branch:
```bash
git checkout -b "nomeDaBranch"
```

Lista todas as branches criadas:
```bash
git branch
```

Alterar branch:
```bash
git checkout "nomeDaBranch"
```

Excluir uma branch(você deve trocar de branch para poder realizar a exclusão)
```bash
git branch -D "nomeDaBranch"
```







