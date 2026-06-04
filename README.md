# ✅ Tarefas do Dia — PWA

App de tarefas simples. Cada tarefa tem botão **Pendente → Feita**. À meia-noite, todas voltam para **Pendente** automaticamente. Tarefas só somem se você excluir.

## 🚀 Publicar no GitHub Pages

### 1. Crie o repositório
```bash
git init
git add .
git commit -m "feat: app tarefas pwa"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/tarefas.git
git push -u origin main
```

### 2. Ative o GitHub Pages
Settings → Pages → **Source: GitHub Actions**

O arquivo `.github/workflows/deploy.yml` já está incluído e faz o deploy automático.

### 3. Instale como PWA
- Abra `https://SEU_USUARIO.github.io/tarefas` no celular
- Chrome Android: menu ⋮ → **"Adicionar à tela inicial"**
- Safari iOS: botão compartilhar → **"Adicionar à Tela de Início"**
