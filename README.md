# Supabase Todo 따라하기

## 1. 프로젝트 설정
강의 커리큘럼에 맞는 넥스트 14.2.4 버전으로 설치 후 @material-tailwind/react 관련 의존성 다운그레이드.

## 2 .material-tailwind/react를 사용해 UI 생성
layout.tsx / ui.tsx에서 의도한 화면을 출력하도록 만들었다.

## 3. Supabase 회원가입 후 데이터베이스 테이블 등록
```
NEXT_PUBLIC_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY
NEXT_SUPABASE_SERVICE_ROLE
NEXT_SUPABASE_DB_PASSWORD
```
- Settings - Data API - API Setting 에서 Key 등록이 가능하다.
- npx supabase login으로 token을 받아와 인증한다.
- npm run generate-types 명령어를 사용해 types_db.ts를 생성한다.

## 4. React Query, Supabase 필수 라이브러리 설정
React Query, middleware 설정을 통해 비동기 형식으로 데이터 입출력 가능.

## 5. CRUD 생성
CRUD Server Action 에서 정의한 함수를 사용해 데이터 통신이 가능하게 만든다.
