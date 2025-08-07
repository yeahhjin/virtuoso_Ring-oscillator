# virtuoso_Ring-oscillator


### 📘 아날로그 집적회로 설계 프로젝트

### 🔧 프로젝트 개요

본 프로젝트는 **Cadence Virtuoso 환경**에서 수행한 아날로그 회로 설계 실습 과제로, 인버터와 링 오실레이터 회로를 중심으로 스케매틱 설계, 시뮬레이션 설정 및 파형 분석을 수행하였습니다.

**디지털 집적회로 과목의 후속 실습 과목**으로서, 이번 아날로그 집적회로 과제를 통해 **이론으로 배운 회로 동작을 직접 구성하고 검증**하는 실질적 설계 경험을 쌓을 수 있었습니다.

---

### 🧪 주요 설계 내용 및 툴 사용

1. **인버터 회로 설계**
    - Cadence Virtuoso에서 스케매틱 회로 구성
    - 심볼 생성 및 전원 + 펄스 소스 연결
    - **ADE Maestro 환경**에서 DC/Transient Analysis 수행
    - 시뮬레이션 결과를 통해 파형 분석 및 동작 검증
2. **링 오실레이터 회로 설계**
    - 인버터를 직렬로 연결해 링 오실레이터 구성
        - 인버터 심볼 제작 및 파형
          
            <img width="1920" height="1080" alt="Screenshot from 2024-12-09 16-02-10" src="https://github.com/user-attachments/assets/4eecd7bd-ce58-44a9-a8b4-377552b1b7c1" />
      
            
        - 링오실레이터 스케마틱
     
            <img width="1312" height="621" alt="스크린샷 2025-08-07 141006" src="https://github.com/user-attachments/assets/240a0221-9778-4d5e-87c5-1ca8d4e6400f" />

            
    - 전압원 및 제어신호 삽입
    - 시뮬레이션 환경 설정 후 **오실레이션 주기 및 안정성 확인**
  
        <img width="412" height="485" alt="Screenshot from 2024-12-16 17-01-37" src="https://github.com/user-attachments/assets/2e3dd252-2e5f-42fb-a310-43b13a4bc6ec" />
        
    - 출력 파형 기반으로 진동 주기 분석
  
        <img width="999" height="836" alt="Screenshot from 2024-12-16 17-00-53" src="https://github.com/user-attachments/assets/b290ffdf-bc98-4805-8072-2683a3580b5f" />

        

---

### 🧠 학습 내용 및 성과

- 아날로그 회로에서의 소자 연결 방식, 신호 흐름, 파형 해석 과정을 **직접 체험**함
- ADE 시뮬레이션 환경을 활용해 설계 → 검증 → 분석으로 이어지는 흐름을 실습
- 디지털 회로 설계와 비교해 **아날로그 회로의 민감도 및 타이밍 특성**을 체감함
- 실제 동작 결과를 통해 설계가 올바르게 이루어졌는지 확인할 수 있었으며, **설계 오차에 대한 디버깅 경험도 포함**
