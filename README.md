# 💵 달러 투자 대시보드

USD/KRW 환율과 달러 인덱스(DXY) 데이터를 기반으로 달러 투자 적합성을 분석하는 대시보드입니다.

## 기능

- **투자 적합성 탭**: 원달러 환율, 달러 인덱스, 갭 비율, 적정환율 4개 지표로 매수 적합성 판단
- **적정환율 분석 탭**: DXY 기반 적정환율 차트, 갭 추이, 달러인덱스 추이 시각화
- **기간 선택**: 1개월 / 3개월 / 6개월 / 1년
- **실시간 데이터**: Yahoo Finance API

## Vercel 배포 방법

### 1단계: GitHub에 올리기

```bash
cd dollar-dashboard
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/본인계정/dollar-dashboard.git
git push -u origin main
```

### 2단계: Vercel에서 배포

1. [vercel.com](https://vercel.com) 접속 → GitHub 계정으로 로그인
2. **"Add New Project"** 클릭
3. 방금 올린 `dollar-dashboard` 레포 선택
4. Framework Preset: **Vite** (자동 감지됨)
5. **"Deploy"** 클릭 → 1~2분 후 배포 완료!

배포 후 `https://dollar-dashboard-xxxxx.vercel.app` 같은 주소가 생성됩니다.

## 로컬 실행

```bash
npm install
npm run dev
```

http://localhost:5173 에서 확인 가능합니다.
