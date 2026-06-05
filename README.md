# AVOI — Site institucional

Site institucional da **AVOI SERVIÇOS DIGITAIS LTDA** (CNPJ 55.063.975/0001-50).
Páginas estáticas em HTML, sem dependências de build. Basta hospedar os arquivos.

## Arquivos

- `index.html` — página principal (home)
- `termos-de-uso.html` — Termos de Uso
- `politica-pld-ft.html` — Política de PLD/FT
- `docs/` — pasta para os PDFs das demais políticas (ver abaixo)

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `avoi-site`).
2. Envie todos estes arquivos para a raiz do repositório.
3. No GitHub: **Settings → Pages**.
4. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`. Salve.
6. Em ~1 minuto o site estará no ar em `https://SEU-USUARIO.github.io/avoi-site/`.

> O arquivo `.nojekyll` já está incluído para o GitHub Pages servir os arquivos como estão.

## Documentos pendentes (pasta /docs)

O rodapé tem links para políticas que ainda não foram fornecidas. Coloque os PDFs
na pasta `docs/` com exatamente estes nomes para que os links funcionem:

- `docs/politica-de-privacidade-avoi.pdf`
- `docs/politica-kyc-avoi.pdf`
- `docs/politica-kyt-avoi.pdf`
- `docs/politica-kyp-avoi.pdf`
- `docs/politica-gestao-de-risco-avoi.pdf`
- `docs/politica-anticorrupcao-avoi.pdf`
- `docs/aviso-de-riscos-avoi.pdf`
- `docs/informacoes-regulatorias-avoi.pdf`

(Os Termos de Uso e a Política de PLD/FT já estão como páginas HTML e não precisam de PDF.)

## Observações importantes

- O logo está embutido nos HTML (data URI); não há arquivos de imagem externos.
- O formulário de contato é apenas client-side (validação). Para receber mensagens,
  conecte-o a um serviço de e-mail/back-end (ex.: Formspree) antes de publicar.
- Os textos legais e regulatórios devem ser validados por assessoria jurídica
  antes da publicação definitiva.
