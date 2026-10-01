# Conecta+

Projeto acadêmico de desenvolvimento front-end criado para a Experiência Prática IV. O projeto demonstra organização de código, responsividade, acessibilidade, otimização e preparação para publicação.

## Tecnologias

- HTML5 semântico
- CSS3 responsivo
- JavaScript
- Vite para build e minificação
- Git/GitHub para versionamento

## Funcionalidades

- Navegação semântica e responsiva
- Navegação por teclado e foco visível
- Link para saltar diretamente ao conteúdo principal
- Modo claro/escuro com preferência armazenada no navegador
- Formulário com validação no front-end
- Feedback acessível com `aria-live`
- Layout adaptável para desktop, tablet e smartphone

## Estrutura

```text
projeto_frontend_ep4/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── conecta-preview.svg
├── dist/
├── package.json
├── vite.config.js
├── README.md
├── CHANGELOG.md
└── .gitignore
```

## Instalação e execução

Com Node.js instalado, execute:

```bash
npm install
npm run dev
```

Para gerar a versão de produção:

```bash
npm run build
```

A versão otimizada é gerada na pasta `dist/`, com HTML, CSS e JavaScript preparados para publicação.

## Acessibilidade

O projeto utiliza HTML5 semântico, link de salto para o conteúdo principal, labels associados aos campos, foco visível, navegação por teclado, `aria-label` em controles interativos e feedback com `aria-live`. A interface também possui modo escuro e cores selecionadas para favorecer a legibilidade.

## Versionamento

Versão final: `v1.0.0`

Commit sugerido:
`feat: versão final do projeto`

## Licença

Projeto acadêmico para fins educacionais.
