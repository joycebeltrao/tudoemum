# Tudo em Um — página de vendas

Página estática (HTML + CSS + JS puro, sem build). Funciona direto na Vercel.

## Estrutura
```
index.html      página completa
img/            imagens (mockup, prints, foto, emblema do Notion)
```

## Link de checkout
O link da Kiwify já está preenchido. Para trocar, abra `index.html`, procure por `CHECKOUT_URL` perto do final do arquivo e substitua o endereço entre as aspas.

## Imagem de compartilhamento (opcional)
O `og:image` usa `img/mockup.webp`. Para aparecer ao compartilhar o link, troque por uma URL completa com o seu domínio (ex.: `https://seudominio.com.br/img/mockup.webp`).

## Subir no GitHub
1. Crie um repositório novo (ex.: `tudo-em-um`), vazio.
2. Envie os arquivos: botão **Add file → Upload files**, arraste `index.html`, `README.md` e a pasta `img`, e clique em **Commit changes**.

## Publicar na Vercel
1. Em vercel.com, clique em **Add New → Project** e escolha o repositório `tudo-em-um`.
2. Em **Framework Preset**, deixe **Other**. Não precisa de build command nem output directory.
3. Clique em **Deploy**. A cada novo commit no GitHub, a Vercel publica de novo sozinha.
4. Domínio próprio: **Settings → Domains → Add**.
