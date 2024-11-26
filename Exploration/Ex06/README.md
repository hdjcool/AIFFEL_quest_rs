# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 황동주
- 리뷰어 : 김준석


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          ㅁ 모델 구성을 위한 전처리 단계  
        <img width="671" alt="image" src="https://github.com/user-attachments/assets/45c6d968-88eb-4c0b-8002-d0052b691615"><br>
        <img width="684" alt="image" src="https://github.com/user-attachments/assets/af46f8eb-79c4-4066-bd63-da6d8672c3d5"><br>
        -> 불용어 제거에 대한 생각과 근거를 잘 정리해주셨다고 생각합니다.  
        <img width="422" alt="image" src="https://github.com/user-attachments/assets/6ce74352-86af-4ace-b952-8d6f46039f65"><br>
        -> 평균과 표준편차를 활용하여 Maxlen을 설정하신점이 좋았습니다.  
          <img width="553" alt="image" src="https://github.com/user-attachments/assets/7f34b418-305b-4b9f-ac16-d08b5c60be63"><br>
          <img width="550" alt="image" src="https://github.com/user-attachments/assets/543dc958-5959-4f03-9fbe-53adddffd359"><br>
          <img width="682" alt="image" src="https://github.com/user-attachments/assets/6ee42e2b-9d55-49cf-8e12-1132908384bb"><br>

            ㅁ 텍스트 요약모델 학습
          <img width="577" alt="image" src="https://github.com/user-attachments/assets/77e370d3-cb73-4962-a1c0-a04156a3599e"><br>
          <img width="363" alt="image" src="https://github.com/user-attachments/assets/aed3fcfb-c2d7-497e-95c2-f433b5d5676a"><br>
          -> train,val loss 시각화를 통해 모델의 학습을 잘 나타내주셨습니다.  
        <img width="675" alt="image" src="https://github.com/user-attachments/assets/a7100db8-3aca-4874-a811-1dc04864c72d"><br>
        <img width="687" alt="image" src="https://github.com/user-attachments/assets/a6ea9e13-427f-41c8-bc24-5f6476289ead"><br>
        <img width="659" alt="image" src="https://github.com/user-attachments/assets/b31dbff5-9b33-4c41-a182-ae7490561c49"><br>
        -> 실제 요약문과의 비교와 회고를 잘 작성해 주셨습니다!
          ㅁ 정량적 평가
          <img width="545" alt="image" src="https://github.com/user-attachments/assets/73b7be75-580b-4d11-9c03-4b9b3f63f1d2"><br>

          <img width="698" alt="image" src="https://github.com/user-attachments/assets/63c05236-bb87-45d6-b2fb-7a88f7681ec0"><br>
          <img width="697" alt="image" src="https://github.com/user-attachments/assets/2cfbdccd-cf73-4c2f-b1cc-f4521cd4c0b6"><br>

          -> 실제 정량평가 지표로 BLEU 점수를 활용하신 점이 좋았습니다.  

          ㅁ Extractive 요약  
          <img width="690" alt="image" src="https://github.com/user-attachments/assets/7e63fb35-4354-4c11-aa52-a2b9c09b0dac"><br>
          -> 추출적 요약도 잘 완성해주셨습니다.

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        <img width="619" alt="image" src="https://github.com/user-attachments/assets/bd0908f4-ad3d-45b3-8fbb-3a04775620f0"><br>
        <img width="692" alt="image" src="https://github.com/user-attachments/assets/fee40949-a8f8-46b8-83de-b5969df2aa6c"><br
        -> 문제점 파악과, 디버깅을 시도해보려고 하신점이 보였습니다. 

- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        <img width="673" alt="image" src="https://github.com/user-attachments/assets/14cb0ef3-ee24-4aa0-b463-38d9adf2b860"><br>
        -> 위 회고 뿐만 아니라, 매 실험 결과마다 본인의 생각을 잘 정리해주시고 문제점이 있다면 파악하고 어떻게 해결해 볼 지 기록을 남기신 점들이 잘 작성되었다고 생각합니다.
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          -> 리뷰어 입장에서 바라볼 때, 코드가 명시적으로 잘 짜여져있고, 시각적으로도 이해하기 쉽게 잘 작성되었습니다.

# 회고(참고 링크 및 코드 개선)
-> 동주님의 코드를 볼때마다 코드작성 및 회고에 대해 배울점이 많습니다!ㅎㅎ 각 실험결과에 대한 코멘트 덕분에 저또한 몰랐던 부분에 대해 공부할 수 있었습니다. 고생많으셨습니다!!







