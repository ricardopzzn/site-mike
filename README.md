# Estrutura do projeto

- `index.html`: arquivo fonte do site.
- `assets/`: identidade visual e fotografias usadas pelo site.
- `assets/archive/`: original duplicado mantido como arquivo.
- `docs/links-referencias.txt`: links e dados de referência.
- `dist/`: versão pronta para publicação; a configuração em `.openai/hosting.json` aponta para esta pasta.

Ao editar o site, atualize `index.html` e copie a versão para `dist/index.html`. Mantenha em `dist/assets/` os arquivos referenciados pelo HTML publicado.
