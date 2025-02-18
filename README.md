# 🚀 Do Git ao GitHub

## 📂 Criando o Diretório do Repositório
Primeiro, criamos uma pasta para armazenar os repositórios locais:

```bash
C:\> mkdir repos
C:\> cd repos
```

Verificamos o conteúdo do diretório recém-criado:
```bash
C:\repos> dir
```

## 🛠️ Clonando um Repositório do GitHub
Agora, clonamos um repositório existente do GitHub:

```bash
C:\repos> git clone https://github.com/seuUsuario/seu-repositorio.git
```

E acessamos a pasta do repositório clonado:
```bash
C:\repos> cd GitAoGitHub
```

## 🔍 Verificando o Status do Repositório
Antes de realizar qualquer alteração, verificamos o status do repositório:

```bash
C:\repos\GitAoGitHub> git status
```
Saída esperada:
```
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)
```
Isso indica que há arquivos não rastreados (untracked files).

## 📌 Adicionando Arquivos ao Controle do Git
Para começar a rastrear arquivos, usamos:
```bash
C:\repos\GitAoGitHub> git add .
```
Isso adiciona **todos os arquivos modificados e novos** ao controle do Git.

## ✅ Criando um Commit
Agora, registramos as alterações no repositório local com uma mensagem:

```bash
C:\repos\GitAoGitHub> git commit -m ":tada:"
```
Saída esperada:
```
[main 5deb31c] 🎉
 Committer: aluno <aluno@INTRAUECA.CEFET.COM>
...
 1 file changed, 11 insertions(+)
 create mode 100644 index.html
```
O commit salva as alterações **localmente**, mas ainda não as envia para o GitHub.

## 🚀 Enviando para o GitHub
Por fim, enviamos as alterações para o repositório remoto:

```bash
C:\repos\GitAoGitHub> git push
```

E pronto! Seu código agora está atualizado no GitHub. 🎉
