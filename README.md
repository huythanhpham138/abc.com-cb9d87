# 핑크헤어

이 폴더는 Boom Homepage가 AI로 생성한 **정적 사이트 소스 코드**입니다 (75 페이지).
GitHub에 올린 뒤 빌드 없이 그대로 배포할 수 있습니다.

## 구조
- `index.html` — 전체 페이지 링크 허브
- `<지역>/<서비스>/<검색의도>/index.html` — 각 SEO 페이지 (canonical URL과 동일 경로)
- `sitemap.xml`, `robots.txt` — 검색엔진 제출용
- `.github/workflows/deploy.yml` — GitHub Pages 자동 배포

## 배포 (GitHub Pages)
1. 이 폴더를 새 GitHub 저장소에 push 합니다.
2. 저장소 **Settings → Pages → Source: GitHub Actions** 선택.
3. push 하면 포함된 워크플로가 자동으로 배포합니다.

## 다른 호스팅
- **Vercel / Netlify / Cloudflare Pages**: 저장소를 import 하면 빌드 명령 없이 정적 호스팅됩니다.

## 점검 링크
- Rich Results: https://search.google.com/test/rich-results
- PageSpeed: https://pagespeed.web.dev/
- Schema: https://validator.schema.org/
