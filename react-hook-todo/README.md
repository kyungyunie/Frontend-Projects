# React Hook Todo

React로 구현한 Todo 리스트 프로젝트로, UI 개선부터 상태 관리 로직 분리까지 점진적인 발전 과정을 담은 통합 프로젝트입니다.  
초기 UI 설계부터 Custom Hook을 통한 코드 분리 및 재사용성 향상까지의 흐름을 체계적으로 구현하였습니다.

---

## 기술 스택
- React
- CSS Modules
- React Custom Hook
- LocalStorage

---

## 주요 기능
- 할 일 추가, 삭제, 수정
- 완료된 할 일 체크 및 스타일 변경
- 전체 / 진행 중 / 완료 항목 필터링
- Custom Hook(`useTodos.js`)을 통한 상태 관리 로직 분리
- LocalStorage 연동으로 새로고침 후에도 데이터 유지
- 컴포넌트 구조 개선 및 스타일 모듈화(CSS Modules)

---

## 프로젝트 설명

이 프로젝트는 React 기반의 Todo 리스트 구현을 통해 **UI 구성 → 기능 확장 → 코드 분리**의 순서를 따라가며 구조를 개선해 나간 결과물입니다.

1. **초기 단계**에서는 React 컴포넌트 설계와 CSS Modules를 통해 UI와 기능을 구성하고, 기본적인 Todo 관리 기능(추가, 삭제, 수정, 필터 등)을 구현하였습니다.

2. **후속 개선 단계**에서는 상태 관리 로직을 `useTodos.js`라는 Custom Hook으로 분리하여 **컴포넌트는 UI에 집중**하고, **상태와 로직은 Hook 내부에서 처리**되도록 구조를 개선하였습니다. 또한 LocalStorage를 연동하여 데이터 유지가 가능하도록 설계했습니다.

