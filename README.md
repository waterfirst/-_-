# 동의보감 AI 도우미 (Korean Medicine Doctor)

동의보감 AI 도우미는 한의학의 고전인 동의보감을 현대적으로 해석하고 이해하기 쉽게 설명해주는 대화형 웹 애플리케이션입니다.

## 주요 기능

- 🤖 AI 기반 동의보감 지식 제공
- 📚 동의보감 원문 기반 답변
- 💬 실시간 대화형 인터페이스
- ✨ 마크다운 형식의 구조화된 답변
- 🔍 한의학 용어 쉬운 설명

## 기술 스택

- **Frontend**: React + TypeScript
- **Styling**: Tailwind CSS
- **AI**: Google Gemini API
- **Icons**: Lucide React
- **Markdown**: React Markdown
- **Build Tool**: Vite

## 시작하기

1. 저장소 클론
```bash
git clone https://github.com/your-username/korean-medicine-doctor.git
cd korean-medicine-doctor
```

2. 의존성 설치
```bash
npm install
```

3. 환경 변수 설정
```bash
# .env 파일 생성
VITE_GEMINI_API_KEY=your_gemini_api_key
```

4. 개발 서버 실행
```bash
npm run dev
```

## 프로젝트 구조

```
korean-medicine-doctor/
├── src/
│   ├── components/      # React 컴포넌트
│   ├── data/           # 동의보감 데이터
│   ├── lib/            # 유틸리티 및 API 통신
│   └── App.tsx         # 메인 애플리케이션
├── public/             # 정적 파일
└── package.json        # 프로젝트 설정
```

## 기여하기

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 라이선스

MIT License - 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 주의사항

이 애플리케이션은 교육 목적으로만 사용되어야 하며, 의학적 조언을 대체할 수 없습니다. 건강상의 문제는 반드시 전문 의료인과 상담하시기 바랍니다.
