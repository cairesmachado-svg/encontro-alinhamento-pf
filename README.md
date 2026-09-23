# Encontro de Alinhamento Técnico da Área Disciplinar — 2026

Apresentação executiva em HTML do **Relatório de Execução e Resultados**, no mesmo padrão visual (obsidian/grafite/dourado policial) do painel de alinhamento disciplinar.

- Página principal: `index.html` · logotipo em `assets/logo-pf.png`
- Sem dependências externas, CDN ou framework — HTML/CSS/JS puros, um único arquivo + 1 imagem.
- Abertura animada (brasão da PF) idêntica ao painel de referência, com botão "Pular Abertura" e opção de rever a qualquer momento.
- 25 telas dinâmicas (seguindo a estrutura do relatório), navegáveis por toque/swipe, teclado (setas, Home/End) ou pelos botões Anterior/Avançar — sem uso de pop-ups/modais.
- Layout adaptado para iPad e para o navegador interno do WhatsApp (viewport-fit=cover, áreas seguras, alvos de toque ≥40px, sem dependência de vh problemático em WebView).
- Link direto para qualquer tela via hash (`#s-N`), útil para compartilhar um tópico específico.
- Todo o conteúdo reproduz literalmente o Relatório de Execução e Resultados (numeração das seções e anexos preservada), sem dados pessoais de casos, processos ou respondentes da avaliação.
- Meta `noindex,nofollow,noarchive` incluída para desencorajar indexação por buscadores.

## Publicação no GitHub Pages

Este repositório é público e o GitHub Pages já está ativo (branch `main`, raiz `/`). O endereço é:

`https://cairesmachado-svg.github.io/encontro-alinhamento-pf/`

Novos commits em `main` atualizam o site automaticamente.

Esta é uma cópia do mesmo conteúdo publicado em `https://mcaires1980.github.io/encontro-alinhamento-pf/`.
