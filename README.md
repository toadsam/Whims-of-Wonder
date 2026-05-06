# Whims of Wonder

현대 판타지 RPG를 목표로 만든 Unity 프로젝트입니다. 플레이어 상태 머신, 입력 처리, ScriptableObject 기반 데이터 분리, 3D RPG 조작 구조를 실험합니다.

## 프로젝트 개요

`Whims-of-Wonder`는 현대 판타지 분위기의 RPG 프로토타입입니다. 플레이어 이동과 상태 전환을 중심으로, RPG 캐릭터 조작의 기본 골격을 직접 구현하는 데 초점을 둡니다.

## 주요 구현 영역

- 플레이어 상태 머신 구조
- Idle, Walk 등 상태별 코드 분리
- Unity Input System 기반 입력 처리
- ScriptableObject 기반 플레이어 데이터 관리
- 3D 캐릭터 조작과 애니메이션 데이터 연결

## 기술 스택

- Unity `2022.3.2f1`
- C#
- Unity Input System
- ScriptableObject
- Unity Animator

## 폴더 구조

```text
.
├── Assets/
│   ├── Scripts/
│   │   └── Characters/Player/
│   ├── ScripableObjects/
│   ├── InputActions/
│   └── Scenes/
├── Packages/
├── ProjectSettings/
└── README.md
```

## 실행 방법

1. Unity Hub에서 `2022.3.2f1` 버전을 설치합니다.
2. 저장소 루트 폴더를 Unity 프로젝트로 엽니다.
3. `Assets/Scenes` 아래의 시작 씬을 엽니다.
4. Play 버튼으로 실행합니다.

## 개발 메모

현재 저장소는 현대 판타지 RPG의 기초 시스템을 쌓는 단계입니다. 이후에는 전투, 퀘스트, 인벤토리, 월드 상호작용 같은 RPG 시스템을 추가하면서 README에 구현 범위를 계속 갱신하면 좋습니다.

## 개선 아이디어

- 게임 기획 요약 추가
- 조작법과 시작 씬 명시
- 구현 완료/진행 중 기능 체크리스트 추가
- 플레이 영상 또는 스크린샷 추가
