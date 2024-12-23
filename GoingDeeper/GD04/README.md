# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 황동주
- 리뷰어 : 김영민


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 루브릭에 맞는 코드가 전부 포함되어 있습니다.
        ![1](https://github.com/user-attachments/assets/803d327b-c842-422d-8353-7219155d1491)
    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 코드가 진행되는 순서가 마크다운으로 기록되어 있고 어떤 이유로 이런 코드를 작성하게 되었는지 주석으로 설명되어 있습니다.
        ![2](https://github.com/user-attachments/assets/97b8a26b-b6fa-48bc-9ac4-e7b183b1b006)
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 9가 연속적으로 출력되는 부분에 대해서 해결하는 내용이 담겨 있습니다.
        ![3](https://github.com/user-attachments/assets/9272a2e7-069e-4589-987f-e639cf0ee0f9)
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 회고가 노트북 마지막단에 작성되어 있고 결과요약과 문제점, 수정한 부분과 해보고싶은 부분을 잘 적어주셨습니다.
        ![4](https://github.com/user-attachments/assets/f5bc652e-945f-4ef9-9ec9-4af4ce252881)
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 진행이 한눈에 잘보이게 작성되어 있고 함수형으로 작성되어 반복적인 코드를 줄였습니다.
```python
def process_sample_image(image_path):
    """
    주어진 이미지 경로에서 텍스트를 감지하고 크롭된 텍스트 이미지를
    인식하여 결과를 출력하는 함수.

    Args:
        image_path (str): 처리할 이미지 파일 경로

    Returns:
        None
    """
    # 1. 이미지에서 텍스트 감지
    img_pil, cropped_imgs = detect_text(image_path)

    # 2. 감지된 텍스트 영역 표시
    print("Detected Text Regions:")
    display(img_pil)

    # 3. 크롭된 텍스트 이미지 확인 및 크기 출력
    for i, img in enumerate(cropped_imgs):
        display(img)
        print(f"Cropped Image {i+1} Size: {img.size}")

    # 4. 크롭된 이미지에서 텍스트 인식
    print("Recognized Texts:")
    for i, _img in enumerate(cropped_imgs):
        try:
            recognized_text = recognize_img(_img)
            print(f"Recognized Text {i+1}: {recognized_text}")
        except Exception as e:
            print(f"Error processing Cropped Image {i+1}: {e}")
```


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- 저는 인덱스를 확인하는 작업을 건너뛰었는데 귀찮다고 넘어가지 않고 동주님처럼 확인해보는게 디버깅 측면에서 좋은거같습니다.
- 깜박하고 모델 학습 그래프를 그려보지 않았는데 퀘스트가 끝난 후 그려볼 수 있도록 하겠습니다.