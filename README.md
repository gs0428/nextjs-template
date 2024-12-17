# Next.js Template

이 템플릿은 Next.js 프로젝트를 매번 새롭게 세팅하는 번거로움을 줄이고 통일된 개발 환경을 제공하기 위해 제작되었습니다.

기본적인 폴더 구조와 ESLint 및 Prettier 설정을 포함하여 효율적인 개발 경험을 제공합니다.

## 📋 개발 환경

- Framework: Next.js v15.1.0
- Frontend Library: React v19.0.0
- Linting:
  - ESLint v9.17.0
  - eslint-plugin-simple-import-sort v12.1.1
- Formatting: Prettier v3.4.2
- Styling: Tailwind CSS v3.4.1
- Language: TypeScript v5.7.2

## ✨ 주요 특징

### 일관된 Import 순서 정리

[eslint-plugin-simple-import-sort](https://github.com/lydell/eslint-plugin-simple-import-sort)를 활용하여 import 구문을 자동으로 정렬합니다. 또한 그룹별로 import 순서를 명확히 구분하여 가독성을 높였습니다.

### Prettier 연동

코드 스타일 규칙을 일관되게 유지하며 ESLint와 충돌 없는 설정이 적용되었습니다.

### Tailwind CSS 설정 포함

Tailwind CSS 기본 설정이 포함되어 있어 빠른 스타일링이 가능합니다.

## 📂 폴더 구조

```plaintext
my-app/
├── public/ # 정적 자산을 저장하는 폴더 (이미지, 아이콘, 폰트 등)
├── src/ # 소스 코드의 루트 디렉토리
│ ├── app/ # Next.js App Router 관련 파일을 저장하는 폴더 (라우팅 및 페이지 관리)
│ ├── components/ # 재사용 가능한 컴포넌트를 저장하는 폴더
│ ├── constants/ # 전역적으로 사용하는 상수값(예: API 엔드포인트, 환경 변수 등)을 저장하는 폴더
│ ├── hooks/ # 커스텀 React 훅을 저장하는 폴더 (공통적으로 사용하는 훅 로직)
│ ├── lib/ # 외부 라이브러리 관련 설정 파일을 저장하는 폴더(예: zustand 관리)
│ ├── service/ # API 요청과 관련된 비즈니스 로직을 처리하는 폴더
│ ├── types/ # 전역적으로 사용하는 TypeScript 타입 정의를 저장하는 폴더
│ └── utils/ # 전역적으로 사용하는 유틸리티 함수(예: 데이터 포맷팅 함수)를 저장하는 폴더
├── eslint.config.mjs # ESLint 설정 파일
├── .prettierrc.json # Prettier 설정 파일
├── tailwind.config.ts # Tailwind CSS 설정 파일
└── tsconfig.json # TypeScript 설정 파일
```
