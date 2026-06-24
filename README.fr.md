# Flux RSS des Notes de Patch de League of Legends

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · **Français** · [Deutsch](README.de.md) · [Português](README.pt-BR.md)

Un flux RSS pour les notes de patch de League of Legends, déployé sur Vercel.

## Fonctionnalités

- Récupère automatiquement les notes de patch officielles de League of Legends
- Génère un flux RSS
- Prend en charge les images et les descriptions détaillées

## Déploiement

1. Forkez ce dépôt
2. Importez votre dépôt sur [Vercel](https://vercel.com)
3. Une fois déployé, l'URL de votre flux RSS sera : `https://votre-domaine/api/rss`

## Développement local

```bash
# Installer les dépendances
npm install

# Lancer en local
npm run dev
```

## Stack technique

- Node.js
- Axios
- Cheerio
- RSS
- Vercel Serverless Functions

## Remarques

- Veillez à respecter les conditions d'utilisation du site officiel de League of Legends
- Il est recommandé de définir un intervalle de requête raisonnable afin d'éviter les requêtes trop fréquentes
