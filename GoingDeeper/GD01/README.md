# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 황동주
- 리뷰어 : 김준석


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부  
    1. Resnet34,50 모델 구현이 정상적으로 진행 되었는가? O  
     <img width="370" alt="image" src="https://github.com/user-attachments/assets/6089adba-e1dc-48f2-afa1-8934ea4ff197" /><br>
     <img width="393" alt="image" src="https://github.com/user-attachments/assets/2bd690d3-00c6-43ce-aeee-795e7a6b181b" /><br>
     <img width="483" alt="image" src="https://github.com/user-attachments/assets/9cbc4501-7f48-46a1-8b19-41d542cbfdf3" /><br>
     <img width="490" alt="image" src="https://github.com/user-attachments/assets/6abdd6b6-22ba-4f02-8fe4-dc61bcaf3360" /><br>
     <img width="481" alt="image" src="https://github.com/user-attachments/assets/e4118a3b-001b-4fb8-94d6-e99593e3340d" /><br>

    2. 구현한 Resnet모델을 활용하여 Image Classification 모델 훈련이 가능한가? O  
    <img width="549" alt="image" src="https://github.com/user-attachments/assets/fe32102b-ec29-4504-960b-aa7b9c9c16b1" /><br>

    3. Ablation Study 결과가 바른 포맷으로 제출되었는가? O  
    <img width="308" alt="image" src="https://github.com/user-attachments/assets/7920d6f7-cf0c-4d5a-919f-42bd36ac12e4" /><br>
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
    -> 처음 basic_block 코드를 구상할때, PlainNet까지 한번에 만들 수 있는 함수를 구상하신 점이 좋았습니다.  
      <img width="434" alt="image" src="https://github.com/user-attachments/assets/5a4d9b45-1a19-4150-8dfb-b4f5cf215555" /><br>
    -> ResNet-50에 사용되는 bottleneck_block 구조 또한, PlainNet을 고려하여 훌륭히 작성해 주셨습니다.  
      <img width="347" alt="image" src="https://github.com/user-attachments/assets/7ff5a714-9fcc-471f-ab6a-d9291d0bcbea" /><br>
    -> 데이터 및 task의 목적에 맞게끔 모델을 수정하신 부분이 핵심적으로 잘 작성하셨다고 생각합니다.  
      <img width="450" alt="image" src="https://github.com/user-attachments/assets/7405069a-b7f8-4cf3-af6e-db0a709db102" /><br>



        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
    -> cats_vs_dogs 데이터 셋을 다운로드 받는 과정에서, 어떤 부분이 오류가 있는지 발견 하신뒤 이를 해결하신 점이 보입니다.  
      <img width="523" alt="image" src="https://github.com/user-attachments/assets/3626529b-6dbc-4ae0-b250-b57fe59945c9" /><br>
    -> ResNet-34와 ResNet-50을 비교해보는 추가 실험을 진행하셨고, 이에 대한 분석을 잘 말씀해주셨습니다.  
      <img width="538" alt="image" src="https://github.com/user-attachments/assets/4f7cc2d7-df77-4ff7-8417-c1309aac68fa" /><br>
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
<img width="485" alt="image" src="https://github.com/user-attachments/assets/f01802dc-d60b-4430-8a97-c640473a24b3" />

- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부    
    -> 위에서 언급한 것 처럼, 모델의 block을 구현하는 함수를 효율적으로 잘 작성해주셨습니다.

# 회고(참고 링크 및 코드 개선)
```
오늘도 동주님 코드를 보면서 정말 많이 배워갑니다!!
특히 Task 목적에 맞게 이진분류 모델로 수정하신 점에서, 제가 가장 중요한 점을 놓쳤다는걸 알게됐습니다. 감사합니다ㅎㅎ..
고생 많으셨습니다!
```
