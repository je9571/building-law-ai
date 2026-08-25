# 건축 인허가 법규 AI 메모

## GitHub Pages로 배포
1. 이 폴더의 `index.html`을 GitHub 저장소에 업로드합니다.
2. Settings → Pages → Deploy from branch → main/root를 선택합니다.
3. 배포된 사이트에서 Gemini API 키를 입력합니다.

## 주의
GitHub Pages는 정적 사이트이므로 API 키를 완전히 숨길 수 없습니다. 개인 테스트용으로만 사용하고, 공개 서비스는 Cloudflare Worker/Netlify Function/Vercel Function 같은 서버 프록시를 사용하세요. API 키에는 사용량 제한과 HTTP referrer 제한을 설정하세요.

## 모델
현재 예시는 `gemini-2.0-flash`를 사용합니다. Google AI Studio에서 사용 가능한 모델명으로 변경할 수 있습니다.
