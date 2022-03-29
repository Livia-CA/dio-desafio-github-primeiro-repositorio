# Comandos vistos no curso...



------

### Link para o site de download do Git

- https://git-scm.com/downloads 

------

### Link para o Github

- https://github.com/

------



## Ajuda

##### Geral

```
git help
```

##### Comando específico

```
git help add
git help commit
git help <qualquer_comando_git>
```

## Configuração

### Geral

##### Setar usuário

```
git config --global user.name "(name)"
```

##### Setar email

```
git config --global user.email (email)
```

##### Listar configurações

```
git config --list
```

## Repositório Local

### Criar novo repositório

```
git init
```

### Verificar estado dos arquivos/diretórios

```
git status
```

### Adicionar arquivo/diretório (staged area)

##### Adicionar um arquivo em específico

```
git add (meu_arquivo.txt)
```

##### Adicionar um diretório em específico

```
git add (meu_diretorio)
```

##### Adicionar todos os arquivos/diretórios

```
git add .	
```

### Comitar arquivo/diretório

##### Comitar um arquivo

```
git commit (meu_arquivo.txt)
```

##### Comitar vários arquivos

```
git commit (meu_arquivo.txt meu_outro_arquivo.txt)
```

##### Comitar informando mensagem

```
git commit (meuarquivo.txt) -m "(minha mensagem de commit)"
```

### Remover arquivo/diretório

##### Remover arquivo

```
git rm (meu_arquivo.txt)
```

##### Remover diretório

```
git rm -r (diretorio)
```

## Repositório Remoto

### Exibir os repositórios remotos

```
git remote

git remote -v
```

### Vincular repositório local com um repositório remoto

```
git remote add origin (link github)
```

### Exibir informações dos repositórios remotos

```
git remote show origin
```

### Enviar arquivos/diretórios para o repositório remoto

O primeiro **push** de um repositório deve conter o nome do repositório remoto e o branch.

```
git push -u origin master
```

Os demais **pushes** não precisam dessa informação

```
git push
```

### Atualizar repositório local de acordo com o repositório remoto

##### Atualizar os arquivos no branch atual

```
git pull
```

##### Buscar as alterações, mas não aplica-las no branch atual

```
git fetch
```

### Clonar um repositório remoto já existente

```
git clone (link github)
```

