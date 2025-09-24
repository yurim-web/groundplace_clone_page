# 🏖️ Groundplace Clone - Private Pool Villa

> **제주도 프라이빗 풀빌라 그라운드플레이스 웹사이트 클론 프로젝트**

[![React](https://img.shields.io/badge/React-19.0.0-blue.svg)](https://reactjs.org/)
[![GSAP](https://img.shields.io/badge/GSAP-3.12.5-green.svg)](https://greensock.com/gsap/)
[![Swiper](https://img.shields.io/badge/Swiper-11.1.15-orange.svg)](https://swiperjs.com/)
[![License](https://img.shields.io/badge/License-Private-red.svg)]()

## 🌟 프로젝트 소개

그라운드플레이스는 제주도 한경면에 위치한 프라이빗 풀빌라입니다. 이 프로젝트는 원본 웹사이트를 React와 GSAP을 활용하여 클론 코딩한 것으로, 부드러운 애니메이션과 인터랙티브한 사용자 경험을 구현했습니다.

### 🎯 주요 특징

- **🎬 인터랙티브 슬라이더**: Swiper.js를 활용한 자동 재생 메인 이미지 슬라이더
- **✨ 부드러운 애니메이션**: GSAP ScrollTrigger를 활용한 스크롤 기반 애니메이션
- **🖼️ 동적 이미지 갤러리**: 마우스 호버 시 이미지가 변경되는 인터랙티브 갤러리
- **🎥 비디오 배경**: 제주도 아름다운 풍경을 보여주는 비디오 섹션
- **📱 웹 전용 디자인**: 데스크톱 환경에 최적화된 풀스크린 레이아웃

## 🚀 라이브 데모

**[🌐 웹사이트 바로가기](https://yurim-web.github.io/groundplace_clone_page/)**

> **📝 참고**: 원본 소스코드는 [grandplace_home](https://github.com/yurim-web/grandplace_home) 저장소에, 배포용 빌드 파일은 [groundplace_clone_page](https://github.com/yurim-web/groundplace_clone_page) 저장소에 있습니다.

## 🛠️ 기술 스택

| 기술 | 버전 | 용도 |
|------|------|------|
| **React** | 19.0.0 | 프론트엔드 프레임워크 |
| **GSAP** | 3.12.5 | 애니메이션 라이브러리 |
| **Swiper** | 11.1.15 | 슬라이더 컴포넌트 |
| **CSS3** | - | 스타일링 |
| **Create React App** | 5.0.1 | 빌드 도구 |

## 📁 프로젝트 구조

```
src/
├── components/
│   ├── common/
│   │   ├── MainSwiper.jsx      # 메인 슬라이더 컴포넌트
│   │   └── MainSlide.jsx       # 개별 슬라이드 컴포넌트
│   ├── css/
│   │   ├── common.css          # 공통 스타일
│   │   ├── page1.css           # 페이지별 스타일
│   │   └── styles.css          # Swiper 스타일
│   ├── fonts/
│   │   └── NotoSerif-Regular.ttf
│   └── layout/
│       ├── Page1.jsx           # 메인 소개 페이지
│       ├── Page2.jsx           # 프라이빗 스페이스 소개
│       ├── Page3.jsx           # 특별 서비스 갤러리
│       ├── Page4.jsx           # 비디오 배경 페이지
│       ├── Video_page.jsx      # 비디오 섹션
│       └── Footer.jsx          # 푸터
├── App.jsx                     # 메인 앱 컴포넌트
├── index.jsx                   # 앱 진입점
└── index.css                   # 글로벌 스타일
```

## 🎨 주요 기능

### 1. 메인 슬라이더 (MainSwiper)
- 7개의 아름다운 제주도 이미지 자동 순환
- 네비게이션 버튼과 페이지네이션
- 부드러운 전환 효과

### 2. 특별 서비스 갤러리 (Page3)
- 5가지 특별 서비스 소개
- 마우스 호버 시 이미지 동적 변경
- 인터랙티브 갤러리 효과

### 3. GSAP 애니메이션
- 스크롤 기반 요소 애니메이션
- 바운스 효과가 있는 이미지 애니메이션
- 텍스트 페이드인 애니메이션
- 스크롤 트리거를 활용한 고급 애니메이션

### 4. 비디오 섹션
- 제주도 풍경을 보여주는 배경 비디오
- 풀스크린 비디오 경험

## 🚀 설치 및 실행

### 필수 요구사항
- Node.js (v14 이상)
- npm 또는 yarn

### 설치 과정

1. **저장소 클론**
   ```bash
   git clone https://github.com/yurim-web/grandplace_home.git
   cd grandplace_home
   ```

2. **의존성 설치**
   ```bash
   npm install
   ```

3. **개발 서버 실행**
   ```bash
   npm start
   ```

4. **브라우저에서 확인**
   ```
   http://localhost:3000
   ```

### 빌드 및 배포

```bash
# 프로덕션 빌드
npm run build

# 테스트 실행
npm test
```

## 🎯 학습 목적

이 프로젝트는 다음 기술들을 학습하기 위해 제작되었습니다:

- ✅ **React 컴포넌트 구조 설계**
- ✅ **GSAP 애니메이션 라이브러리 활용**
- ✅ **Swiper.js 슬라이더 구현**
- ✅ **CSS 스타일링과 레이아웃**
- ✅ **이미지 최적화 및 경로 관리**
- ✅ **스크롤 기반 인터랙션 구현**


## 📄 라이선스

Copyright© 그라운드플레이스. All Rights Reserved.  
DESIGNED & PHOTO BY 언제나,디자인

> **주의**: 이 프로젝트는 학습 목적으로 제작된 클론 코딩 프로젝트입니다. 상업적 사용을 금지합니다.

## 📞 문의

프로젝트에 대한 문의사항이 있으시면 언제든지 연락해주세요!

---

<div align="center">

**🏖️ Groundplace Clone - React와 GSAP을 활용한 웹 개발 학습 프로젝트 🚀**

[![Source Code](https://img.shields.io/badge/Source%20Code-Repository-black?style=for-the-badge&logo=github)](https://github.com/yurim-web/grandplace_home)
[![Build Files](https://img.shields.io/badge/Build%20Files-Deploy%20Repo-blue?style=for-the-badge&logo=github)](https://github.com/yurim-web/groundplace_clone_page)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Website-green?style=for-the-badge&logo=vercel)](https://yurim-web.github.io/groundplace_clone_page/)

</div>
