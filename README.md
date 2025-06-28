```markdown
# 💬 streamlabs-boilerplate

> Um boilerplate simples para desenvolvedores customizarem facilmente o **widget de chat** do Streamlabs.

Este repositório serve como ponto de partida para personalizar a aparência e comportamento do chat que aparece nas transmissões ao vivo via Streamlabs. Edite rapidamente o estilo, animações e estrutura sem complicações.

## 📁 Estrutura do Projeto
```

index.html        # Estrutura base do widget de chat
package.json      # Scripts e dependências opcionais (Vite)
src/
├── main.js       # Lógica de manipulação do chat
└── style.css     # Estilos visuais e animações

## 🚀 Como Usar

### 🔧 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/streamlabs-boilerplate.git
cd streamlabs-boilerplate
````

### 🧪 2. Teste localmente

#### Opção 1 — Método simples

Abra o arquivo `index.html` diretamente no navegador:

```bash
start index.html  # Windows
open index.html   # Mac/Linux
```

#### Opção 2 — Usando Vite (recomendado)

> Para desenvolvedores que desejam live reload, modularização e ambiente moderno:

```bash
npm install
npm run dev
```

Acesse: [http://localhost:5173](http://localhost:5173)

---

## 🎨 Personalização

Edite os arquivos em `src/` para alterar comportamento e aparência:

* `main.js`: lógica de entrada de mensagens, animações, filtros, etc.
* `style.css`: cores, fontes, layout, transições.

Você pode usar as classes e eventos do Streamlabs para customizações mais avançadas.

---

## 📦 Requisitos

* Node.js v16 ou superior (caso use Vite)

---

## 🤝 Contribuição

Pull requests são bem-vindos! Sinta-se à vontade para sugerir melhorias que ajudem a comunidade de streamers e devs.

---

## 📄 Licença

Distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.