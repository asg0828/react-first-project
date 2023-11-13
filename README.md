# First Project

라이브러리, 디렉토리 구조, 환경 설정 등 개발에 필요한 모든 것을 처음부터 끝까지 완성할 첫번쨰 프로젝트

## Installation

https://github.com/asg0828/react-first-project.git

## Getting Started

yarn start

## Tech Stack

- react
- react-router-dom
- react-query
- react-redux
- @/reduxjs/toolkit
- axios
- i18next
- react-app-alias
- craco
- styled-components
- mui

## Project Structure

|-- public/: 정적 자산 및 HTML 파일을 저장하는 곳입니다. 웹팩 또는 빌드 도구를 통해 자동으로 빌드된 파일이 이 디렉토리에 배포됩니다.
|-- src/: 애플리케이션의 소스 코드가 있는 디렉토리입니다.
| |--api/: 데이터를 가져오거나 외부 API와 상호 작용하는 서비스 모듈을 저장합니다.
| |--assets/: 이미지, 글꼴 등과 같은 정적 자산을 저장합니다.
| |--components/: 재사용 가능한 리액트 컴포넌트를 저장합니다.
| |--constans/: URL이나 정규식 패턴과 같은 재사용 가능하고 변경할 수 없는 문자열이 포함되어 있습니다.
| |--context/: 구성 요소 트리를 통해 데이터를 제공하는 데 사용되는 컨텍스트입니다.
| |--features/: 상태 관리와 관련된 로직을 기능 단위로 구분하여 저장합니다.
| |--pages/: 각 라우트에 해당하는 페이지 컴포넌트를 저장합니다.
| |--hooks/: 커스텀 훅을 관리합니다.
| |--utils/: 프로젝트 전체에서 사용되는 유틸리티 함수나 헬퍼 함수를 저장합니다.
| |--App.tsx: 루트 컴포넌트로서 애플리케이션의 전체 구조를 정의합니다.
| |--index.tsx: 애플리케이션의 진입점으로서 DOM에 리액트 앱을 렌더링합니다.
| |--store.ts: 리덕스의 모든 슬라이스를 가져오고 스토어를 구성합니다.
tests/: 테스트 파일을 저장하는 디렉토리입니다.
.gitignore: Git으로 관리하지 않아야 할 파일과 디렉토리를 설정합니다.
package.json: 프로젝트의 의존성 및 스크립트 등을 정의합니다.
README.md: 프로젝트에 대한 문서를 작성합니다.
