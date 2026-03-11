# 👨‍💻 ChanQ

<img src="image/me.png" alt="Kyu Chan profile" width="140" />

`Android`를 중심으로 제품 구조를 설계하고, 사용자 흐름이 보이는 화면을 구현하는 개발자입니다.  
`Jetpack Compose`, `Hilt`, `Retrofit`, `DataStore`, `Room` 기반의 실무형 앱 구조를 다루며, `Swift`를 통한 iOS 개발, 필요할 때는 `React + TypeScript`로 서비스 소개 웹까지 직접 연결합니다.

## 👉 About Me

`Android` 7~8년차 개발자로서 Java/Kotlin 기반 앱을 개발·운영해왔으며, `MVVM` + `Hilt` + `Coroutines` + `Jetpack Compose` 기반 아키텍처와 레거시(MVP, RxJava, MVC) 구조를 모두 경험했습니다.</br>
최근에는 `iOS` 앱 개발·운영 경험을 더해, 플랫폼을 넘어서 `Clean Architecture` 관점에서 유지보수성과 확장성이 높은 구조(레이어 분리, 의존성 관리, 변경에 강한 설계)를 구축하는 데 집중하고 있습니다.</br>
또한 팀/프로젝트의 생산성과 개발 효율을 높이기 위한 구조 개선과 프로세스 최적화를 지속적으로 고민하고 있습니다.

- 멀티모듈 구조와 계층 분리를 통해 확장 가능한 Android 앱을 설계합니다.
- Compose 기반 UI를 선호하며, 상태 관리와 재사용 가능한 공통 컴포넌트 설계에 집중합니다.
- 로그인, 위치, 지도, 로컬 저장소, 네트워크, 다국어 처리 등 앱 서비스 전반을 통합해서 구현해왔습니다.
- 앱 자체뿐 아니라 랜딩 페이지, 배포 구성, 운영 편의 기능까지 함께 다루는 편입니다.

## 👉 Core Strengths

### 1. Android Architecture

- `app / core / feature / build-logic` 기반 멀티모듈 설계
- `MVVM + UseCase + Repository` 중심 계층 분리
- `Gradle Kotlin DSL`, `Version Catalog`, `Convention Plugin` 활용

### 2. Modern Android UI

- `Jetpack Compose` + `Material 3` 기반 화면 구현
- 공통 UI 컴포넌트와 테마 시스템 구성
- `Navigation Compose`, 애니메이션, Edge-to-Edge UI 적용

### 3. Data and Platform Integration

- `Retrofit`, `OkHttp`, `Moshi` 기반 API 연동
- `DataStore`, `Room` 기반 로컬 데이터 설계
- `Hilt` 기반 의존성 주입

### 4. Product-minded Frontend

- `React + TypeScript + Vite` 기반 랜딩 페이지 개발
- 디바이스 분기, 다운로드 UX, QR 자동 생성 등 전환 중심 구현
- `Docker + Nginx` 기반 정적 배포 구성

## 🛠️ Tech Stack

| Area | Skills |
| --- | --- |
| Android | `Kotlin`, `Java`, `Jetpack Compose` |
| iOS | `Swift` |
| Frontend | `React`, `TypeScript`, `Vite`, `Next`, `Tailwind CSS` |
| Architecture | `MVVM`, `CleanArchitecture`, `UseCase`, `Repository`, `Multi Module` |
| DI / Async | `Hilt`, `Coroutines`, `Flow` |
| Network / Storage | `Retrofit`, `OkHttp`, `Moshi`, `DataStore`, `Room`, `Alamofire` |
| CICD / Deploy | `Github Action`,`Github WebHook`, `Docker`, `Nginx` |

## 🗂️ Featured Projects

### `SeoulMate Android `

서울 관광/챌린지 기반 Android 앱 프로젝트입니다.  
지도, 위치, 지오펜싱, 소셜 로그인, 로컬 저장소, 원격 API 연동이 결합된 서비스형 앱 구조를 다뤘습니다.

- `Jetpack Compose` 기반 멀티모듈 Android 앱
- `Hilt`, `Retrofit`, `Room`, `DataStore` 조합의 앱 아키텍처
- 위치 기반 기능, Naver Map, Firebase, 다국어 처리 적용

### `JIU JITSU Android`

도메인 확장성과 유지보수를 고려해 구조를 설계한 Android 프로젝트입니다.

- `core / feature / build-logic` 분리
- `UseCase`, `Repository`, `UiState` 중심의 계층형 설계
- 카카오/구글 로그인, 재사용 UI 컴포넌트, 타입 세이프 네비게이션 구성

### `PopPop Seoul Web`

앱 소개 및 다운로드 전환을 위한 React 기반 랜딩 페이지 프로젝트입니다.

- `React + TypeScript + Vite` 기반 SPA
- 모바일/데스크톱 환경에 따른 다운로드 분기 UX 구현
- QR 자동 생성과 `Docker + Nginx` 배포 구성

## 👉  Development Profile

제가 선호하는 개발 방식은 기능 구현보다 먼저 구조를 정리하는 것입니다.  
공통 기능은 `core`로, 화면 단위 기능은 `feature`로 분리하고, 화면에서는 상태와 이벤트를 명확하게 나누는 편입니다.

협업에서는 `GitHub Flow`와 `Conventional Commits`를 기준으로 작업을 정리합니다.  
기능 추가 시 영향 범위를 줄이고, 유지보수 가능한 구조를 만드는 데 집중합니다.

## 👉 Contact

- Email: chankyuh@gmail.com
