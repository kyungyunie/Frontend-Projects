# React Native Weather App

React Native와 OpenWeather API를 활용한 실시간 날씨 앱입니다.  
도시 검색을 통해 나라별 시간대를 반영한 시간별 예보와 5일간의 날씨 예보를 확인할 수 있으며,  
날씨 상태에 따라 UI가 동적으로 변경됩니다.

---

## 기술 스택

- React Native (Expo)
- AsyncStorage
- Axios
- OpenWeather API
- Moment.js

---

## 주요 기능

- 자동 완성 검색 기능 (입력한 글자가 포함된 도시 추천)
- 한글 → 영어 변환 검색 지원 (한국 & 해외 도시 검색 가능)
- 나라별 시간대 반영 및 현재 시간 기준 정렬된 시간별 예보 제공
- 5일간의 날씨 예보 (최고/최저 기온 계산 및 표시)
- 날씨 상태별 UI 변경 (배경색 & 날씨 이모티콘 적용)
- AsyncStorage 활용해 최근 검색한 도시 저장
- KeyboardAvoidingView 및 TouchableWithoutFeedback으로 UX 개선

---

## 프로젝트 설명

React Native 기반으로 개발된 날씨 예보 앱입니다.  
OpenWeather API를 통해 날씨 데이터를 받아오며, 입력한 도시명에 따라 시간대가 자동 반영됩니다.  
사용자의 편의를 위해 자동 완성 기능과 검색 히스토리를 저장하는 기능을 제공하며,  
날씨 상태에 따라 배경 및 날씨 아이콘이 변경되어 시각적으로도 직관적인 UI를 구성했습니다.

