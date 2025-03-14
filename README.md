# To-Do App

간단한 할 일 관리 애플리케이션으로, Kotlin과 MVVM 아키텍처를 기반으로 개발되었습니다. 이 앱은 사용자가 할 일을 추가, 수정, 삭제 할 수 있는 기능을 제공합니다. Room 데이터베이스를 활용하여 할 일 데이터를 저장하고 관리합니다.

## 주요 기능

- 할 일 추가, 수정 및 삭제
- Room Database를 활용한 데이터 저장
- MVVM 아키텍처 적용으로 유지보수 용이

## 기술 스택

- **언어**: Kotlin
- **아키텍처**: MVVM (Model-View-ViewModel)
- **데이터베이스**: Room
- **UI**: Jetpack Compose / XML (구현 방식에 따라 수정 가능)

## 프로젝트 구조

- **adapters/** - RecyclerView 또는 UI 구성 요소의 어댑터
- **converters/** - Room Database에서 사용할 타입 변환기
- **dao/** - Room 데이터 접근 객체 (DAO)
- **database/** - 데이터베이스 설정 및 구성
- **models/** - 애플리케이션에서 사용하는 데이터 모델
- **repository/** - ViewModel과 데이터베이스 간 데이터 처리 레이어
- **utils/** - 유틸리티 함수 및 도우미 클래스
- **viewmodels/** - UI와 상호작용하는 ViewModel 클래스
- **MainActivity.kt** - 애플리케이션의 진입점


## 기능 설명

- **할 일 추가**: 사용자가 입력한 텍스트를 기반으로 새로운 할 일을 추가합니다.
- **할 일 수정**: 기존 할 일 항목을 수정합니다.
- **할 일 삭제**: 선택한 할 일을 삭제합니다.


