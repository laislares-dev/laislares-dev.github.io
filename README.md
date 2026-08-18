# Portfólio - Laís Lares

Portfólio profissional minimalista com design em azul e branco. Mostra experiência em BIM/Revit e desenvolvimento Python.

## 🚀 Como Ativar no GitHub Pages

### Passo 1: Criar um novo repositório
1. Vá para [github.com/new](https://github.com/new)
2. **Nome do repositório:** `laislares-dev.github.io`
3. Selecione "Public"
4. Clique em "Create repository"

### Passo 2: Upload dos arquivos
Você pode fazer isso de 3 formas:

#### Opção A: Via Git (Recomendado)
```bash
git clone https://github.com/seu-usuario/laislares-dev.github.io.git
cd laislares-dev.github.io
# Copie os arquivos (index.html, style.css, _config.yml) aqui
git add .
git commit -m "Initial commit: Portfolio setup"
git push origin main
```

#### Opção B: Upload direto no GitHub
1. No repositório criado, clique em "Add file" → "Upload files"
2. Selecione:
   - `index.html`
   - `style.css`
   - `_config.yml`
3. Commit as mudanças

#### Opção C: Usando GitHub Desktop
1. Clone o repositório no GitHub Desktop
2. Copie os arquivos para a pasta
3. Faça commit e push

### Passo 3: Verificar se está online
- Aguarde 1-2 minutos
- Acesse: `https://laislares-dev.github.io`
- Pronto! Seu portfólio está no ar 🎉

## 📁 Estrutura de Arquivos

```
laislares-dev.github.io/
├── index.html       # Página principal
├── style.css        # Estilos
├── _config.yml      # Configuração Jekyll
└── README.md        # Este arquivo
```

## 🎨 Design

- **Cores:** Azul escuro (#10142d) e Branco (#ffffff)
- **Responsivo:** Mobile, Tablet, Desktop
- **Rápido:** HTML/CSS puro, sem dependências

## 📝 Como Personalizar

### Mudar informações pessoais
Edite o `index.html` e procure por:
- `lareslais@gmail.com` → seu email
- `+55 31 9 8208-1309` → seu telefone
- Links do GitHub, LinkedIn, etc

### Adicionar novos projetos
Na seção "Projetos em Desenvolvimento" (dentro do `index.html`), copie uma `project-card` e edite:
```html
<article class="project-card">
  <div class="project-header">
    <h3>Nome do Projeto</h3>
    <span class="badge">Status</span>
  </div>
  <p class="project-description">Descrição curta</p>
  <!-- ... -->
</article>
```

### Mudar cores
No `style.css`, procure por `:root` e mude:
```css
:root {
  --primary: #10142d;  /* Azul escuro */
  --white: #ffffff;    /* Branco */
  /* ... */
}
```

## 📱 Seções Incluídas

- ✅ Hero com CTA
- ✅ Sobre
- ✅ Projetos
- ✅ Skills/Competências
- ✅ Experiência (Timeline)
- ✅ Formação
- ✅ Contato

## 🔗 Links Importantes

- GitHub: https://github.com/laislares-dev
- LinkedIn: https://www.linkedin.com/in/laislares
- Email: lareslais@gmail.com

---

**Versão:** 1.0 | **Atualizado:** Agosto 2026
