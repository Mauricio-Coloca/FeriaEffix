# AVOI — Site institucional

Site institucional da **AVOI SOCIEDADE PRESTADORA DE SERVIÇOS DE ATIVOS VIRTUAIS LTDA** (CNPJ 55.063.975/0001-50).
Páginas estáticas em HTML, sem dependências de build. Basta hospedar os arquivos.

## Arquivos

- `index.html` — página principal (home)
- `termos-de-uso.html` — Termos de Uso (Versão 1.0 · Junho/2026)
- `politica-pld-ft.html` — Política de PLD/FT (Versão 3.0 · Junho/2026)
- `privacidade.html` — Política de Privacidade / LGPD (Versão 1.0 · Junho/2026)
- `cookies.html` — Política de Cookies (Versão 1.0 · Junho/2026)
- `elegibilidade.html` — Política de Elegibilidade de Ativos Virtuais (Versão 1.0 · Junho/2026)
- `docs/` — versões oficiais **assinadas** (PDF) das cinco políticas

Cada página de política exibe o bloco de assinaturas da Diretoria e um link
"Ver versão oficial assinada (PDF)" que aponta para o respectivo arquivo em `docs/`.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `avoi-site`).
2. Envie todos estes arquivos (incluindo a pasta `docs/`) para a raiz do repositório.
3. No GitHub: **Settings → Pages**.
4. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`. Salve.
6. Em ~1 minuto o site estará no ar em `https://SEU-USUARIO.github.io/avoi-site/`.

## Observações importantes

- O logo está embutido nos HTML (data URI); não há arquivos de imagem externos.
- O formulário de contato é apenas client-side (validação). Para receber mensagens,
  conecte-o a um serviço de e-mail/back-end (ex.: Formspree) antes de publicar.
- As páginas HTML reproduzem o texto das políticas para leitura no site. A **assinatura
  digital verificável** existe apenas nos PDFs da pasta `docs/`; por isso cada página
  enlaça a versão assinada. Em caso de divergência, prevalece a versão oficial assinada.
