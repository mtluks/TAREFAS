# ✅ Tarefas do Dia — PWA

App de tarefas com checklist. **Checklists somem automaticamente à meia-noite.**

## 🎨 Paleta de Cores
- `#0F0F0F` — Fundo principal
- `#202020` — Cards
- `#5DD62C` — Verde principal (ações)
- `#337418` — Verde escuro (checklist)
- `#F8F8F8` — Texto

## 🚀 Publicar no GitHub Pages

### 1. Crie um repositório no GitHub
```bash
git init
git add .
git commit -m "feat: app de tarefas PWA"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
git push -u origin main
```

### 2. Ative o GitHub Pages
1. Vá em **Settings → Pages**
2. Em **Source**, selecione **GitHub Actions**
3. O workflow `.github/workflows/deploy.yml` vai publicar automaticamente

### 3. Acesse e instale como PWA
- URL: `https://SEU_USUARIO.github.io/SEU_REPO`
- No celular: abra no browser → menu → **"Adicionar à tela inicial"**

## 📱 Funcionalidades
- ✅ Criar tarefas com checklist
- ✅ Marcar tarefas como concluídas
- ✅ Checklists auto-resetam à meia-noite
- ✅ Progresso visual (barra global + mini barra por tarefa)
- ✅ Funciona offline (Service Worker)
- ✅ Instalável como PWA
