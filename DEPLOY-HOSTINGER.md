# Deploy no Hostinger — digitalavello.shop

## Estrutura para upload

Envie estes arquivos e pastas para a raiz do domínio (public_html ou pasta do digitalavello.shop):

```
├── index.html
└── images/
    ├── bonus-mensagem.png
    ├── bonus-oratoria.png
    ├── garantia-7-dias.png
    ├── livro-biblia-memorizada.png
    └── livro-biblia-na-sua-mente.png
```

---

## Método 1: File Manager (recomendado)

1. Acesse o **hPanel** da Hostinger e faça login.
2. Abra o **Gerenciador de Arquivos**.
3. Vá até a pasta do domínio **digitalavello.shop** (geralmente `public_html` ou `domains/digitalavello.shop/public_html`).
4. Faça upload do `index.html` na raiz.
5. Crie a pasta `images` e envie todas as imagens dentro dela.

---

## Método 2: FTP

1. Use um cliente FTP (FileZilla, WinSCP).
2. Dados do FTP estão no hPanel em **Contas FTP** ou **Detalhes de hospedagem**.
3. Conecte e envie os arquivos para o diretório do domínio.

---

## Método 3: Git (se disponível no seu plano)

1. No hPanel, abra **Git**.
2. Crie um repositório ou conecte um existente.
3. Use o token de deploy na configuração da Hostinger.
4. Defina a pasta de build/public como a raiz com `index.html`.

---

## Após o deploy

- Acesse **https://digitalavello.shop/** e teste a página.
- Confirme se o **HTTPS** está ativo (geralmente automático na Hostinger).
- Se o domínio ainda não estiver configurado, em **Domínios** adicione digitalavello.shop e siga as instruções de DNS.
