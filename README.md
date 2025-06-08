DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub | Curso Versionamento de Código com Git e GitHub da [Digital Innovation One](https://www.dio.me).

## 📚 Documentação

* [Documentação Git](https://git-scm.com/docs/git/pt_BR)
* [Documentação GitHub](https://docs.github.com/)

## 🤓 Códigos

```
mkdir nome-pasta
# Criar diretório local com o nome desejado
```

```
git init
# Iniciar um repositório Git local
```

```
touch README.md
# Criar um arquivo README.md (ou qualquer outro arquivo)
```

```
git add nome-arquivo
# Adicionar arquivo específico para staging (preparar para commit)
```

```
git add .
# Adicionar todos os arquivos modificados para staging
```

```
git commit -m "mensagem"
# Salvar alterações com uma mensagem descritiva
```

```
git status
# Verificar o status atual dos arquivos do repositório
```

```
git log
# Ver histórico de commits feitos
```

```
git remote add origin https://github.com/usuario/repositorio.git
# Conectar repositório local a um repositório remoto no GitHub
```

```
git push -u origin main
# Enviar os commits locais para o repositório remoto na branch main
```

```
git pull origin main
# Baixar as alterações do repositório remoto
```

```
git branch -M main
# Renomear a branch atual para 'main'
```

```
git clone https://github.com/usuario/repositorio.git
# Clonar um repositório remoto para sua máquina local
```

```
git reset --hard HEAD~1
# Desfazer o último commit completamente (inclusive alterações no código)
```

```
git checkout nome-da-branch
# Mudar para outra branch existente
```

```
git checkout -b nova-branch
# Criar e mudar para uma nova branch
```

## 🛠️ GitHub CLI

```
gh auth login
# Autenticar com sua conta GitHub via terminal (escolha HTTPS ou SSH)
```

```
gh repo create nome-do-repositorio
# Criar um novo repositório no GitHub a partir do terminal
```

```
gh repo clone usuario/repositorio
# Clonar um repositório remoto usando GitHub CLI
```

```
gh pr create --title "Titulo da PR" --body "Descrição"
# Criar uma pull request diretamente do terminal
```

```
gh issue list
# Listar todas as issues abertas no repositório
```

```
gh repo view
# Ver informações detalhadas sobre o repositório atual
```

```
gh help
# Ver todos os comandos disponíveis do GitHub CLI
```

> O GitHub CLI é uma ferramenta poderosa que permite interagir com o GitHub diretamente pelo terminal, otimizando o fluxo de trabalho e evitando mudanças constantes de contexto entre navegador e terminal.
