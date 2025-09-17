# 🌟 Portfólio - Jacqueline dos Santos Vivot

Portfólio pessoal desenvolvido em React + TypeScript + Vite + Tailwind CSS.

## 🚀 Como Publicar no GitHub Pages

### 1. **Preparar o Repositório**
```bash
# Clone ou baixe este projeto
# Navegue até a pasta do projeto
cd portfolio-jacqueline

# Instale as dependências
npm install
```

### 2. **Configurar o GitHub**
1. Crie um novo repositório no GitHub (ex: `portfolio-jacqueline`)
2. **IMPORTANTE**: No arquivo `vite.config.ts`, altere a linha:
   ```typescript
   base: '/portfolio-jacqueline/', // Substitua pelo nome do SEU repositório
   ```
3. Faça commit de todos os arquivos:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   git push -u origin main
   ```

### 3. **Deploy para GitHub Pages**
```bash
# Faz o build e publica no GitHub Pages
npm run deploy
```

### 4. **Configurar GitHub Pages**
1. Vá para **Settings** do seu repositório
2. Clique em **Pages** no menu lateral
3. Em **Source**, selecione **Deploy from a branch**
4. Escolha a branch **gh-pages**
5. Clique em **Save**

### 5. **Acessar o Site**
Seu site estará disponível em:
```
https://SEU-USUARIO.github.io/SEU-REPOSITORIO/
```

## 🛠️ Scripts Disponíveis

```bash
# Desenvolvimento local
npm run dev

# Build de produção
npm run build

# Preview do build
npm run preview

# Deploy para GitHub Pages
npm run deploy
```

## 📁 Estrutura do Projeto

```
portfolio-jacqueline/
├── public/
├── src/
│   ├── components/          # Componentes React
│   ├── imports/            # Arquivos importados do Figma
│   ├── styles/             # Estilos globais
│   ├── App.tsx             # Componente principal
│   └── main.tsx            # Ponto de entrada
├── index.html              # Template HTML
├── package.json            # Dependências
├── tailwind.config.js      # Configuração Tailwind
├── vite.config.ts          # Configuração Vite
└── README.md               # Este arquivo
```

## 🎨 Tecnologias Utilizadas

- **React 18** - Biblioteca JavaScript
- **TypeScript** - Tipagem estática
- **Vite** - Build tool moderna
- **Tailwind CSS** - Framework CSS utilitário
- **GitHub Pages** - Hospedagem gratuita

## 📱 Recursos

- ✅ Design responsivo
- ✅ Animações suaves
- ✅ Tipografia customizada (Inknut Antiqua)
- ✅ Estrelas decorativas animadas
- ✅ Seções sobre experiência e projetos
- ✅ Links para projetos no Figma

## 🔧 Personalização

Para personalizar o conteúdo:

1. **Textos**: Edite o arquivo `src/imports/Portifolio.tsx`
2. **Cores**: Modifique as cores no `src/styles/globals.css`
3. **Imagens**: Substitua as imagens na pasta `src/assets/`

## 📞 Contato

- **Email**: [seu-email@exemplo.com]
- **LinkedIn**: [Seu LinkedIn]
- **GitHub**: [Seu GitHub]

---

**Desenvolvido com ❤️ por Jacqueline dos Santos Vivot**