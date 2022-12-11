# To Do List

## 배포 링크

https://wanted-pre-onboarding-frontend-5od8.vercel.app/

## 프로젝트 실행 방법

1. 최상위 폴더에 .env 파일 생성

```
REACT_APP_API=https://pre-onboarding-selection-task.shop
```

2. npm install

```bash
npm install
```

3. 프로젝트 실행

```bash
npm start
```

## 디렉토리 구조

```
📦 wanted-pre-onboarding-frontend
├─ .gitignore
├─ README.md
├─ package-lock.json
├─ package.json
├─ postcss.config.js
├─ public
│  └─ index.html
├─ src
│  ├─ App.tsx                   # 페이지 라우팅
│  ├─ apis                      # API 함수
│  │  ├─ register.ts
│  │  └─ todo.ts
│  ├─ components                # 컴포넌트
│  │  ├─ Button.tsx
│  │  ├─ SignForm.tsx
│  │  ├─ Title.tsx
│  │  ├─ Todo.tsx
│  │  ├─ TodoInput.tsx
│  │  └─ TodoList.tsx
│  ├─ context                   # 상태 관리
│  │  ├─ Context.ts
│  │  └─ ContextProvider.tsx
│  ├─ hooks                     # 커스텀 훅
│  │  └─ useSign.ts
│  ├─ index.css
│  ├─ index.tsx
│  ├─ pages                     # 페이지
│  │  ├─ SignIn.tsx             # 로그인
│  │  ├─ SignUp.tsx             # 회원가입
│  │  └─ TodoPage.tsx           # Todo
│  ├─ react-app-env.d.ts
│  ├─ types                     # 타입 정의
│  │  └─ todo.ts
│  └─ utils                     # 기타 함수
│     ├─ logout.ts
│     └─ validation.ts
├─ tailwind.config.js
└─ tsconfig.json
```

©generated by [Project Tree Generator](https://woochanleee.github.io/project-tree-generator)

## 사용 라이브러리

- react-router-dom
- axios
- tailwindcss
