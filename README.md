# Product Maker - Site Futurista

Site redesenhado da ProductMaker.com.br com design futurista e profissional, mantendo o conteúdo original mas com uma apresentação visual moderna e impactante.

## 🚀 Características

- **Design Futurista**: Interface com elementos neon, glassmorphism e animações suaves
- **Responsivo**: Otimizado para desktop e mobile
- **Performance**: Construído com React + Vite para carregamento rápido
- **Animações**: Efeitos de parallax e transições com Framer Motion
- **Imagens Originais**: Assets únicos gerados especificamente para o projeto

## 🎨 Paleta de Cores

- **Primária**: `#00ffff` (Cyan elétrico)
- **Secundária**: `#00ff88` (Verde neon)
- **Accent**: `#ff0080` (Rosa/magenta)
- **Background**: `#0a1628` (Azul escuro profundo)
- **Cards**: `#1a2332` (Azul escuro secundário)

## 🛠️ Tecnologias Utilizadas

- React 18
- Vite
- Tailwind CSS
- Framer Motion
- Lucide Icons
- CSS Custom Properties

## 📦 Instalação e Uso

### Desenvolvimento Local

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev

# Abrir no navegador
http://localhost:5173
```

### Build para Produção

```bash
# Gerar build otimizado
npm run build

# Preview do build
npm run preview
```

## 🌐 Deploy no GitHub Pages

### 1. Preparar o repositório

```bash
# Inicializar git (se ainda não foi feito)
git init

# Adicionar arquivos
git add .

# Commit inicial
git commit -m "Initial commit - ProductMaker futuristic redesign"

# Conectar com repositório remoto
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git

# Push para GitHub
git push -u origin main
```

### 2. Configurar GitHub Pages

1. Vá para as configurações do repositório no GitHub
2. Na seção "Pages", selecione "GitHub Actions" como source
3. Crie o arquivo `.github/workflows/deploy.yml` (já incluído no projeto)

### 3. Configurar domínio customizado

1. No GitHub Pages settings, adicione seu domínio: `productmaker.com.br`
2. Configure os DNS do seu domínio:
   - Tipo A: `185.199.108.153`
   - Tipo A: `185.199.109.153`
   - Tipo A: `185.199.110.153`
   - Tipo A: `185.199.111.153`
   - CNAME: `www` → `SEU_USUARIO.github.io`

## 📁 Estrutura do Projeto

```
productmaker-futuristic/
├── public/
├── src/
│   ├── assets/          # Imagens originais geradas
│   ├── components/      # Componentes React
│   ├── App.jsx         # Componente principal
│   ├── App.css         # Estilos customizados
│   └── main.jsx        # Entry point
├── package.json
├── vite.config.js
└── README.md
```

## 🎯 Seções do Site

1. **Hero Section**: Apresentação principal com animação de crescimento exponencial
2. **Tecnologias**: Cards com IA, Plataformas, Dados e Automação
3. **Era dos Superficiais**: Seção sobre a necessidade evolutiva
4. **3 Blocos**: Teoria, Execução e Estratégia
5. **Era Maker**: Definição e características dos makers
6. **4 Pilares**: Fundamentos detalhados da mentalidade maker
7. **Convergência Exponencial**: Tecnologias que se amplificam
8. **Movimento Maker**: Manifesto e propósito
9. **Call to Action**: Convite para participar
10. **Código Maker**: Compromissos pessoais
11. **Transformação**: Mensagem final inspiracional

## 🔧 Customização

### Cores
Edite as variáveis CSS em `src/App.css` na seção `:root`

### Conteúdo
Modifique o texto diretamente no componente `src/App.jsx`

### Imagens
Substitua os arquivos em `src/assets/` mantendo os mesmos nomes

## 📱 Responsividade

O site é totalmente responsivo com breakpoints:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## ⚡ Performance

- Lazy loading de imagens
- Otimização de bundle com Vite
- CSS minificado
- Componentes otimizados

## 📄 Licença

Este projeto foi desenvolvido especificamente para a ProductMaker. Todos os direitos reservados.

---

**Desenvolvido com ❤️ para a revolução dos makers**

