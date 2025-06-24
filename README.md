# 심플 환율 계산기 웹앱

🇻🇳🇰🇷🇺🇸 여러 나라 통화를 지원하는 심플하고 직관적인 환율 계산기입니다.  
기준 통화를 선택하고, 큰 숫자 패드를 이용해 금액을 입력하면  
선택한 통화를 기준으로 다양한 나라 환산 금액과 소비 예시를 한눈에 확인할 수 있습니다.

---

## 주요 기능

- 다양한 국가의 통화와 국기, 국가명 표시  
- 기준 통화 선택 가능 (USD, KRW, VND 등)  
- 큰 숫자 패드로 편리한 금액 입력  
- 실시간 환율 API 연동 (ExchangeRate-API 사용)  
- 모바일 최적화 및 심플한 UI/UX  
- 로그인 없이 누구나 바로 사용 가능

---

## 기술 스택

- HTML / CSS / JavaScript (Vanilla)  
- 환율 API: [ExchangeRate-API](https://www.exchangerate-api.com/)  
- 배포: GitHub Pages, Vercel 등 정적 웹 호스팅 서비스

---

## 설치 및 실행 방법

1. GitHub에서 저장소 클론 또는 다운로드  
2. `index.html` 파일을 브라우저에서 열거나,  
3. Vercel, Netlify 등 정적 웹 호스팅에 배포  
4. 기준 통화를 선택하고, 숫자 패드로 금액 입력하여 환율 계산 가능

---

## 환율 API 키

- API 키는 소스코드 내 `apiKey` 변수에 설정되어 있습니다.  
- 무료 API 키 발급은 [ExchangeRate-API](https://www.exchangerate-api.com/)에서 받으실 수 있습니다.

---

## 커스터마이징

- 국가 및 통화 정보는 `countries` 객체에서 관리합니다.  
- 소비 예시는 `consumptionExamples` 객체에서 조정 가능합니다.  
- 스타일은 CSS 부분에서 자유롭게 수정하실 수 있습니다.

---

## 라이선스

MIT License

---

## 문의

프로젝트 관련 문의는 [깃허브 이슈](https://github.com/your-repo/issues) 또는 이메일로 연락 바랍니다.

---

© 2025 지누
