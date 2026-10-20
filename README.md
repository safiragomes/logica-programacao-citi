# Trilha do Chico Pitico (CITi)

Site estático de um único arquivo (`index.html`). Não precisa de servidor nem de banco de dados.

- Qualquer pessoa com o link acessa. Não há login.
- O progresso fica salvo no navegador de cada pessoa (`localStorage`), então quem sai e volta continua de onde parou. Fica limitado a esse navegador: não há como levar o progresso para outro aparelho.
- Ninguém, inclusive a organização, vê os dados dos jogadores.

## Deploy

**GitHub Pages**: crie um repositório, envie estes arquivos para a branch `main` e em Settings > Pages escolha "GitHub Actions". O workflow em `.github/workflows/pages.yml` publica sozinho.

**Netlify, Cloudflare Pages ou Vercel**: arraste a pasta (ou conecte o repositório) sem comando de build e com diretório de saída `.`.

Para atualizar o conteúdo, substitua o `index.html` e faça o deploy de novo.
