# Feed RSS das Notas de Atualização de League of Legends

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · **Português**

Um feed RSS para as notas de atualização de League of Legends, hospedado na Vercel.

## Recursos

- Coleta automaticamente as notas de atualização oficiais de League of Legends
- Gera um feed RSS
- Compatível com imagens e descrições detalhadas

## Implantação

1. Faça um fork deste repositório
2. Importe seu repositório na [Vercel](https://vercel.com)
3. Após a implantação, a URL do seu feed RSS será: `https://seu-dominio/api/rss`

## Desenvolvimento local

```bash
# Instalar as dependências
npm install

# Executar localmente
npm run dev
```

## Tecnologias

- Node.js
- Axios
- Cheerio
- RSS
- Vercel Serverless Functions

## Observações

- Certifique-se de cumprir os termos de uso do site oficial de League of Legends
- Recomenda-se definir um intervalo de requisição adequado para evitar requisições frequentes
