# Feed RSS de las Notas del Parche de League of Legends

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · **Español** · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt-BR.md)

Un feed RSS para las notas del parche de League of Legends, desplegado en Vercel.

## Características

- Extrae automáticamente las notas oficiales del parche de League of Legends
- Genera un feed RSS
- Admite imágenes y descripciones detalladas

## Despliegue

1. Haz un fork de este repositorio
2. Importa tu repositorio en [Vercel](https://vercel.com)
3. Una vez desplegado, la URL de tu feed RSS será: `https://tu-dominio/api/rss`

## Desarrollo local

```bash
# Instalar dependencias
npm install

# Ejecutar localmente
npm run dev
```

## Tecnologías

- Node.js
- Axios
- Cheerio
- RSS
- Vercel Serverless Functions

## Notas

- Asegúrate de cumplir con los términos de uso del sitio web oficial de League of Legends
- Se recomienda establecer un intervalo de solicitud razonable para evitar solicitudes frecuentes
