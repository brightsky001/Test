# 🤖 AI 끝말잇기 웹앱 (Vercel 배포용)

Vercel 전용 설정이 완료된 정적 웹앱 및 서버리스 함수입니다.

## 📁 파일 구조 (압축 해제 후 그대로 업로드)
- `index.html`: 웹 화면 (프론트엔드)
- `vercel.json`: Vercel 라우팅 및 정적 웹사이트 인식 설정
- `api/generate.js`: Vercel 서버리스 함수 (Gemini API 호출)

## 🚀 배포 가이드
1. 압축 파일 안의 파일들을 **GitHub 저장소의 Root(최상위)**에 그대로 올려주세요.
2. Vercel에서 저장소를 불러온 후 `GEMINI_API_KEY` 환경변수를 입력하고 배포하면 완료됩니다!
