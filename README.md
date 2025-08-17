# 📊 Korean Stock Scanner

한국 주식 실시간 스캐너 - Railway 클라우드 배포 버전

## 🎯 100점 채점 시스템

- **🏛️ 기관 투자자** (35점): 신탁 + 연기금 흐름 분석
- **📊 거래량 돌파** (30점): 6개월 평균 대비 40% 이상 돌파  
- **📰 뉴스 분석** (15점): 네이버 RSS + DART 공시 분석
- **🤖 프로그램 매매** (10점): 순매수 강도 + 참여율
- **📈 기술적 분석** (10점): 52주 고점 근접도

## 🚀 Railway 배포

### 배포 방법

1. Railway 계정 생성 및 로그인
2. 새 프로젝트 생성 
3. GitHub 연결
4. 자동 배포 시작

### 환경 변수

- `PORT`: Railway에서 자동 설정

### 파일 구조

```
korean-stock-scanner/
├── app.py              # 메인 Streamlit 애플리케이션
├── requirements.txt    # Python 의존성
├── Procfile           # Railway 실행 명령어  
├── railway.toml       # Railway 설정
├── nixpacks.toml      # 빌드 설정
└── README.md          # 프로젝트 문서
```

## 📌 주요 특징

- ✅ Railway 클라우드 최적화
- ✅ 100점 종합 채점 시스템  
- ✅ 다양한 필터링 옵션
- ✅ 인터랙티브 차트
- ✅ 데이터 내보내기
- ✅ 24시간 안정적 운영

## ⚠️ 주의사항

이 도구는 투자 참고용이며, 모든 투자 결정과 그 결과에 대한 책임은 투자자 본인에게 있습니다.

---

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude <noreply@anthropic.com>