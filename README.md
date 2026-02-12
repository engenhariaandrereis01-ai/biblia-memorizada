# Bíblia Memorizada — Landing Page

Landing page do Método Bíblia Memorizada para [digitalavello.shop](https://digitalavello.shop/).

## Deploy no Netlify

1. Crie uma conta no [Netlify](https://netlify.com) (se ainda não tiver).
2. Faça **push** deste repositório para o GitHub.
3. No Netlify: **Add new site** → **Import an existing project** → **GitHub**.
4. Conecte o repositório `biblia-memorizada`.
5. Configuração automática (já definida no `netlify.toml`):
   - **Build command:** deixe vazio (site estático)
   - **Publish directory:** `.` (raiz)
6. Clique em **Deploy**.
7. Em **Domain settings**, adicione `digitalavello.shop` como domínio customizado e configure os DNS conforme indicado pelo Netlify.

## Local

```bash
pnpm install
pnpm run dev
```

Acesse: http://localhost:3001
