# UE5_PCGEnvironment

Unreal Engine 5의 PCG(Procedural Content Generation)를 활용해 환경(지면, 도로, 식생, 구조물 등)을 자동 생성하는 테스트 프로젝트입니다.

이 프로젝트는 반복적인 환경 배치 작업을 줄이고 규칙 기반 생성과 퍼포먼스 검증을 동시에 수행하는 것을 목표로 합니다.

---

##  목적

- PCG 기반 환경 자동 생성 파이프라인 구축
- 반복 가능한 테스트 필드 제작
- 퍼포먼스 및 최적화 검증
- 실무 환경 제작 워크플로 연구

---

##  Engine Version

- Unreal Engine 5.7 (권장: 5.3 이상)
- PCG Plugin 활성화 필요

---

##  주요 기능

### 1. PCG 기반 환경 생성
- 스플라인 기반 도로 생성
- 지면 위 자동 메시 배치
- 규칙 기반 랜덤 분포

### 2. 메시 자동 배치 시스템
- Static Mesh 필터링 및 배열화
- 태그 기반 분류 배치
- 밀도/스케일/랜덤 회전 제어

### 3. 최적화 고려
- Nanite 대응
- LOD 기반 메시 사용
- Overdraw 최소화 고려
- 반복 배치 시 성능 체크

---

##  실행 방법

1. 레포 클론

```bash
git clone https://github.com/CastleBison/UE5_PCGEnvironment.git
