# 🛠 Guia Básico de Git

Este guia contém comandos essenciais para uso diário no repositório.

## 📌 Clonando o repositório
```bash
git clone https://github.com/seu-usuario/repositorio.git
cd repositorio
```

## 🔄 Criando uma nova branch
```bash
git checkout -b minha-feature
```

## 📤 Enviando alterações
```bash
git add .
git commit -m "feat: adiciona nova funcionalidade"
git push origin minha-feature
```

## 🔄 Atualizando a branch com a última versão do `main`
```bash
git checkout main
git pull origin main
git checkout minha-feature
git merge main
```

## 🚀 Fazendo um Pull Request
1. Acesse o repositório no GitHub.
2. Clique em **"New Pull Request"**.
3. Selecione sua branch e preencha a descrição seguindo o **[Template de Pull Request](../.github/pull_request_template.md)**.
4. Envie para revisão.  
