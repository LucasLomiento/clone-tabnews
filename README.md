# clone-tabnews

Repositório de teste do WriteDocs: a documentação vive na pasta `docs/`, que o projeto `test-project` do
dashboard de dev lê e publica.

- `docs/writedocs.json` — a configuração do site (nome e menu).
- `docs/*.mdx` — as páginas. Cada item de `pages` no `writedocs.json` é o caminho de um arquivo, sem a
  extensão, a partir de `docs/`.

Um push na `main` que mexe em `docs/` sincroniza o conteúdo e dispara um build.

O código do clone do TabNews que estava aqui continua no histórico (commit `d62f902`).
