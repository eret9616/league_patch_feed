# League of Legends Patchnotes RSS-Feed

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · **Deutsch** · [Português](README.pt-BR.md)

Ein RSS-Feed für die Patchnotes von League of Legends, bereitgestellt auf Vercel.

## Funktionen

- Ruft die offiziellen Patchnotes von League of Legends automatisch ab
- Erzeugt einen RSS-Feed
- Unterstützt Bilder und ausführliche Beschreibungen

## Bereitstellung

1. Forke dieses Repository
2. Importiere dein Repository auf [Vercel](https://vercel.com)
3. Nach der Bereitstellung lautet die URL deines RSS-Feeds: `https://deine-domain/api/rss`

## Lokale Entwicklung

```bash
# Abhängigkeiten installieren
npm install

# Lokal ausführen
npm run dev
```

## Tech-Stack

- Node.js
- Axios
- Cheerio
- RSS
- Vercel Serverless Functions

## Hinweise

- Bitte halte dich an die Nutzungsbedingungen der offiziellen League-of-Legends-Website
- Es wird empfohlen, ein angemessenes Anfrageintervall festzulegen, um häufige Anfragen zu vermeiden
