# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# ✅ TodoList (ver.1 - mockData 유지)

## 📌 프로젝트 소개  
React 기반 프론트엔드 웹 애플리케이션으로, 사용자가 하루 동안의 할 일을 기록하고 관리할 수 있는 TodoList 서비스입니다.  
초기 데이터(mockData)를 유지하는 방식으로 구현된 첫 번째 버전입니다.  

## ✨ 주요 기능
- `useState` 기반 CRUD (생성, 수정, 삭제)  
- 초기 데이터(mockData) 유지  
- CSS를 활용한 UI 스타일링  
- GitHub Pages / Vercel 배포  

## 🖼️ 구현 화면
- Todo 작성 화면 (할 일 입력 및 추가)  
- Todo 목록 화면 (CRUD 기능 반영)  
- 새로고침 시 mockData가 유지되는 구조 확인  

## 🛠️ 사용 기술
- **Frontend**: React, JavaScript  
- **State Management**: useState  
- **Styling**: CSS  
- **Deployment**: GitHub Pages / Vercel  

## 🔗 실행 링크  
👉 [TodoList ver.1 실행하기](https://todo-list-mauve-seven-17.vercel.app/)


# ✅ TodoList (ver.2 - LocalStorage 반영)

## 📌 프로젝트 소개  
React 기반 프론트엔드 웹 애플리케이션으로, 사용자가 하루 동안의 할 일을 기록하고 관리할 수 있는 TodoList 서비스입니다.  
초기 데이터 저장 없이 LocalStorage를 활용하여 데이터 영속성을 구현한 두 번째 버전입니다.  

## ✨ 주요 기능
- Todo **생성(Create), 수정(Update), 삭제(Delete), 완료(Toggle)** 기능  
- `useReducer + Context API` 기반 전역 상태 관리  
- LocalStorage 기반 데이터 영속성 (새로고침 후에도 유지)  
- CSS를 활용한 UI 스타일링  
- GitHub Pages / Vercel 배포  

## 🖼️ 구현 화면
- Todo 작성 화면 (할 일 입력 및 추가)  
- Todo 목록 화면 (CRUD 및 완료 처리 반영)  
- LocalStorage 동기화 후 새로고침 시 데이터 유지 확인  

## 🛠️ 사용 기술
- **Frontend**: React, JavaScript  
- **State Management**: useReducer, Context API  
- **Data Persistence**: LocalStorage  
- **Styling**: CSS  
- **Deployment**: GitHub Pages / Vercel  

## 🔗 실행 링크  
👉 [TodoList ver.2 실행하기](https://todo-list-97jzq6m3r-suras-projects-ef281e86.vercel.app/)  


