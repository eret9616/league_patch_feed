# 리그 오브 레전드 패치 노트 RSS 피드

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · **한국어** · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt-BR.md)

리그 오브 레전드 패치 노트를 제공하는 RSS 피드이며, Vercel에 배포되어 있습니다.

## 기능

- 리그 오브 레전드 공식 패치 노트를 자동으로 수집
- RSS 피드 생성
- 이미지 및 상세 설명 지원

## 배포

1. 이 저장소를 Fork 합니다
2. [Vercel](https://vercel.com)에서 자신의 저장소를 가져옵니다(import)
3. 배포가 완료되면 RSS 피드 주소는 다음과 같습니다: `https://your-domain/api/rss`

## 로컬 개발

```bash
# 의존성 설치
npm install

# 로컬 실행
npm run dev
```

## 기술 스택

- Node.js
- Axios
- Cheerio
- RSS
- Vercel Serverless Functions

## 참고 사항

- 리그 오브 레전드 공식 웹사이트의 이용약관을 반드시 준수하세요
- 잦은 요청을 피하기 위해 적절한 요청 간격을 설정하는 것을 권장합니다
