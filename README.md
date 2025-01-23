# Blog com Next.js 14 e Sanity CMS

## Tecnologias utilizadas

- [Next.js](https://nextjs.org/)

- [Tailwind.css](https://tailwindcss.com/)

- [Sanity.io](https://www.sanity.io)


## Primeiros Passos

Primeiro, adicione o ID do seu projeto Sanity e o nome do dataset ao arquivo `.env.local`:

```bash
NEXT_PUBLIC_SANITY_PROJECT_ID=seu_id_do_projeto
NEXT_PUBLIC_SANITY_DATASET=seu_nome_do_dataset
```

Se você quiser ter um sistema de comentários, você precisa adicionar o token da API do Sanity ao arquivo `.env.local`:

```bash
NEXT_PUBLIC_SANITY_TOKEN=seu_token_da_api
```

Depois, instale as dependências e inicie o servidor de desenvolvimento:

```bash
npm install
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev
```

Abra [http://localhost:3000](http://localhost:3000) no seu navegador para ver o resultado.
Abra [http://localhost:3000/studio](http://localhost:3000/studio) para o Sanity Studio.

## Deploy no Vercel

A maneira mais fácil de fazer o deploy da sua aplicação Next.js é usar a [Plataforma Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) dos criadores do Next.js.
