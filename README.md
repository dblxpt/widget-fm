# Widget-FM — Gestão Financeira (Protótipo)

Ferramenta de teste para gestão financeira mensal: registas rendimentos e saldos de contas, e a poupança é calculada automaticamente pela variação de património — sem precisares de categorizar despesas.

- **App**: [`index.html`](./gestao-financeira-prototipo.html) — HTML/CSS/JS autossuficiente, sem dependências de servidor. Os dados ficam guardados no `localStorage` do browser (com exportação/importação de backup em JSON e exportação em CSV).
- **Documentação**: ver [`DOCUMENTACAO.md`](./DOCUMENTACAO.md) para a lógica de cálculo, estrutura de dados, decisões de design e próximos passos planeados.

## Acesso online

A ferramenta está publicada via **GitHub Pages** e fica acessível diretamente no browser em:

**https://dblxpt.github.io/widget-fm/**

O deployment é automático a cada push para `main` (ver `.github/workflows/deploy-pages.yml`).

## Estado

Protótipo de teste, validado em chat. Próximos passos planeados: recriar a mesma lógica em Google Sheets e, mais tarde, evoluir para uma aplicação web com contas de utilizador registadas e dados em back-end.
