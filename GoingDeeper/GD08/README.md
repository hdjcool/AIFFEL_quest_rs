# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 황동주
- 리뷰어 : 이창민


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 1. tfrecord를 활용한 데이터셋 구성과 전처리를 통해 프로젝트 베이스라인 구성을 확인하였다.
        - <img width="704" alt="스크린샷 2025-01-06 오전 10 18 02" src="https://github.com/user-attachments/assets/5de29968-9926-41a9-879b-7b44c266de04" />
        - <img width="782" alt="스크린샷 2025-01-06 오전 10 18 43" src="https://github.com/user-attachments/assets/ea346dcb-2cbe-4562-acd1-c14f6ea66355" />
        - <img width="768" alt="스크린샷 2025-01-06 오전 10 20 09" src="https://github.com/user-attachments/assets/385963d3-f415-44a9-bd2f-90a4db31ac6c" />
        - 2. simplebaseline 모델을 정상적으로 구현하였다.
        - <img width="786" alt="스크린샷 2025-01-06 오전 10 21 18" src="https://github.com/user-attachments/assets/723089b9-2660-43f6-ab49-f5d924dd5700" />
        - <img width="655" alt="스크린샷 2025-01-06 오전 10 21 54" src="https://github.com/user-attachments/assets/19fd749c-6e9e-4500-bafe-aecc777f6003" />
        - <img width="689" alt="스크린샷 2025-01-06 오전 10 22 47" src="https://github.com/user-attachments/assets/833eec47-5025-4d2c-8e2d-c93b1d3b22a1" />
        - <img width="871" alt="스크린샷 2025-01-06 오전 10 23 18" src="https://github.com/user-attachments/assets/bcb44c34-74a4-43fb-a623-0338f2bcbcfd" />
        - 3. Hourglass 모델과 simplebaseline 모델을 비교분석한 결과를 체계적으로 정리하였다.
        - <img width="692" alt="스크린샷 2025-01-06 오전 10 24 15" src="https://github.com/user-attachments/assets/ee3f0432-2772-4ca0-99f0-7476e2c900ef" />
        - <img width="853" alt="스크린샷 2025-01-06 오전 10 26 47" src="https://github.com/user-attachments/assets/858c5389-4857-48cf-bc01-26df93093885" />
        - <img width="824" alt="스크린샷 2025-01-06 오전 10 27 13" src="https://github.com/user-attachments/assets/451562d7-15d4-4983-adbb-f1f7c7ea9a75" />
        - <img width="764" alt="스크린샷 2025-01-06 오전 10 28 00" src="https://github.com/user-attachments/assets/24ad2fa5-3916-4559-acce-c8f5c408cfd3" />
        - TFRecord를 데이터셋으로 사용한 베이스라인 구축, Simplebaseline 모델 정상 학습, 두 모델 비교(회고)까지 루브릭에 맞게 완벽히 수행했다.


    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - simplebaseline 모델에서 사용하기 위해 기존 코드에서 수정한 파트(함수 train)에서 주석을 통해 변경 부분을 보기 쉽게 명시했다.
        - <img width="689" alt="스크린샷 2025-01-06 오전 10 22 47" src="https://github.com/user-attachments/assets/a7e8a988-88d8-40f6-b282-459195b703ed" />


        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 에러가 난 부분과 해결 과정을 마크 다운에 정리했다.
        - <img width="842" alt="스크린샷 2025-01-06 오전 10 37 00" src="https://github.com/user-attachments/assets/1848a5d5-e8ec-4369-b430-19c0e9296995" />
        - <img width="815" alt="스크린샷 2025-01-06 오전 10 37 23" src="https://github.com/user-attachments/assets/07d9b60d-66d7-458a-82c3-a334d82edb16" />
        - <img width="850" alt="스크린샷 2025-01-06 오전 10 37 55" src="https://github.com/user-attachments/assets/f9a40740-dfd8-4ec6-a9ae-18b938655d78" />
        - 그리고 epoch를 늘린 추가 실험 또한 잘 정리되어있다.
        - <img width="854" alt="스크린샷 2025-01-06 오전 10 41 35" src="https://github.com/user-attachments/assets/db8512cd-8694-44d2-a298-63dbc77c380e" />
        - <img width="699" alt="스크린샷 2025-01-06 오전 10 42 05" src="https://github.com/user-attachments/assets/c879366f-6762-49b0-b96b-2942f41f53da" />
        - <img width="816" alt="스크린샷 2025-01-06 오전 10 42 22" src="https://github.com/user-attachments/assets/8be33d45-5789-435b-b204-49bdeca9e5ad" />
        - <img width="723" alt="스크린샷 2025-01-06 오전 10 42 41" src="https://github.com/user-attachments/assets/eae77540-6c27-4f6d-bc5b-51dff5c01145" />




        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 프로젝트 실습 및 추가 실험의 분석 결과와 회고를 적절하게 작성했다.
        - <img width="764" alt="스크린샷 2025-01-06 오전 10 28 00" src="https://github.com/user-attachments/assets/595c710d-d16e-4d9e-9ac7-4d730d5d8374" />


        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 추가적으로 사용한 metric인 class PCKh에 사용된 코드가 깔끔하게 잘 작성된 것 같다.
        - <img width="662" alt="스크린샷 2025-01-06 오전 10 44 56" src="https://github.com/user-attachments/assets/b67a3038-5e6c-4fbb-812b-0b378036fc5e" />




# 회고(참고 링크 및 코드 개선)
```
개인적으로 이번 프로젝트를 진행하면서 개인적으로 회고에서 아쉽다고 했던 부분들이 통주님의 추가 실험을 통해 해소된 것 같다.
에포크가 늘었을 때 결과에서 성능 개선을 확인해볼 수 있었고, 본 교안에 없었던 metric을 통해 수치적으로 성능을 확인할 수도 있었다.

특히 기록을 남기면서 디버깅을 진행하기 쉽지 않았는데, 정신없는 와중애도 매우 자세히 기록을 남기며 프로젝트를 진행했다는 부분이 인상깊었다.
```
