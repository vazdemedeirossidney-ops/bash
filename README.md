# bash

## Inicializar Repositório Git para LogiTrack

Execute os seguintes comandos para inicializar e configurar o repositório:

```bash
git init
git add .
git commit -m "Initial commit: Estrutura LogiTrack"
git branch -M main
git remote add origin https://github.com/vazdemedeirossidney-ops/logitrack-app.git
git push -u origin main
```

## Descrição dos Comandos

- `git init` - Inicializa um novo repositório Git local
- `git add .` - Adiciona todos os arquivos ao staging area
- `git commit -m "..."` - Cria um commit com a mensagem especificada
- `git branch -M main` - Renomeia a branch atual para "main"
- `git remote add origin ...` - Adiciona o repositório remoto
- `git push -u origin main` - Envia os commits para a branch main no repositório remoto
