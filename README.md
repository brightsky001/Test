# 🤖 AI 끝말잇기 웹앱 (Gemini API + Vercel)

Vercel에 바로 배포할 수 있는 AI 끝말잇기 웹 프로그램입니다.

## 📁 프로젝트 구조
- `index.html`: 게임 인터페이스 및 프론트엔드 로직
- `api/generate.js`: Vercel Serverless Function (Gemini API 연동)
- `package.json`: Node.js 프로젝트 설정 파일

## 🚀 배포 방법 (Vercel)
1. 이 폴더의 파일들을 GitHub 저장소에 푸시합니다.
2. Vercel에서 `Import Project`를 수행합니다.
3. **Environment Variables** 설정에서 아래 항목을 추가합니다:
   - `GEMINI_API_KEY`: 사용자 Gemini API Key
4. 배포(Deploy) 후 바로 접속하여 게임을 플레이하실 수 있습니다.
