# Encontro de Alinhamento Técnico da Área Disciplinar — 2026

Apresentação executiva em HTML do **Relatório de Execução e Resultados**, no mesmo padrão visual (obsidian/grafite/dourado policial) do painel de alinhamento disciplinar.

- Página principal: `index.html` · logotipo em `assets/logo-pf.png`
- Sem dependências externas, CDN ou framework — HTML/CSS/JS puros, um único arquivo + 1 imagem.
- Abertura animada (brasão da PF) idêntica ao painel de referência, com botão "Pular Abertura" e opção de rever a qualquer momento.
- 22 telas dinâmicas (uma por tópico do relatório), navegáveis por toque/swipe, teclado (setas, Home/End) ou pelos botões Anterior/Avançar — sem uso de pop-ups/modais.
- Layout adaptado para iPad e para o navegador interno do WhatsApp (viewport-fit=cover, áreas seguras, alvos de toque ≥40px, sem dependência de vh problemático em WebView).
- Link direto para qualquer tela via hash (`#s-N`), útil para compartilhar um tópico específico.
- Conteúdo fiel ao relatório oficial, sem dados pessoais de casos, processos ou respondentes da avaliação.
- Meta `noindex,nofollow,noarchive` incluída para desencorajar indexação por buscadores.

## Publicação no GitHub Pages

Este repositório é público. Para ativar o endereço web:

1. Abra **Settings** → **Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione **main** e **/(root)**.
4. Salve.

O endereço esperado é:

`https://cairesmachado-svg.github.io/encontro-alinhamento-pf/`

Depois de ativado, novos commits em `main` atualizam o site.
