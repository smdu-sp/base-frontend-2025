<p align="center">
  <a href="https://www.prefeitura.sp.gov.br/cidade/secretarias/licenciamento/" target="blank"><img src="https://www.prefeitura.sp.gov.br/cidade/secretarias/upload/chamadas/URBANISMO_E_LICENCIAMENTO_HORIZONTAL_FUNDO_CLARO_1665756993.png" width="200" alt="SMUL Logo" /></a>
</p>
<p align="center">Base de desenvolvimento Frontend - SMUL/ATIC</p>

## Descrição

Base de desenvolvimento frontend de SMUL/ATIC:

- NEXT: https://nextjs.org/docs
- SHADCN: https://ui.shadcn.com/docs

## Instalação

```bash
npm install
# ou
yarn install
# ou
pnpm install
# ou
bun install
```

## Criando o arquivo .env

```bash
copy example.env .env
```

```bash
node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"
```

Copie o código gerado para o campo AUTH_SECRET no arquivo .env

## Rodando a aplicação

Por padrão, a aplicação rodará na porta 3001.

```bash
# atualiza a cada mudança nos arquivos
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev
```

```bash
# modo de desenvolvimento
npm run start
# ou
yarn start
# ou
pnpm start
# ou
bun start
```

Abra [http://localhost:3000](http://localhost:3000) com o navegador.