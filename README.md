# SALOMON Convention Workbook

살로몬 코리아 26FW 시즌 제품 교육용 웹앱

## 파일 구조

```
/
├── index.html              ← 웹앱 전체
├── data/
│   ├── products.js         ← 제품 데이터
│   └── frames_manifest.js  ← 이미지 프레임 매니페스트
└── web_images/             ← 제품 이미지 폴더
```

## 배포

Vercel CLI 사용:
```bash
npx vercel . --prod --yes
```
