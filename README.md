# Meu Blog (Astro Sidey)

Blog pessoal em pt-BR baseado no tema Astro Sidey. Foco em textos, interface
minimalista e navegacao simples.
nicolascouto.com
---

## Recursos

- **Conteudo em MDX** com componentes reutilizaveis
- **Rotas automaticas** a partir da estrutura de pastas
- **RSS** gerado automaticamente em `/rss.xml`
- **Layout minimalista** voltado para leitura
- **Datas em pt-BR** (fuso America/Sao_Paulo)

## Como rodar

```bash
npm install
npm run dev
```

Abra `http://localhost:4321` no navegador.

## Estrutura de conteudo

| Arquivo                               | URL                 |
| ------------------------------------- | ------------------- |
| `src/content/pages/home.mdx`          | `/`                 |
| `src/content/pages/sobre.mdx`         | `/sobre`            |
| `src/content/writings/1-ola-mundo.mdx`| `/writings/1-ola-mundo` |

Observacao: a data no frontmatter deve ficar no formato ISO `YYYY-MM-DD`.

## Configuracao rapida

Edite [sidey.config.ts](sidey.config.ts) para ajustar titulo do site, descricao
e links do menu.

## Licenca

MIT. Veja [LICENSE](./LICENSE) para detalhes.
