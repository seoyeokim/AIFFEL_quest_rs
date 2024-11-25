# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김서영
- 리뷰어 : 황동주


# PRT(Peer Review Template)
- [▲]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/ea232720-dd37-4ef4-a72f-d87df72fd5ab)
        - 3가지 Text Classification 태스크를 성공적으로 수행 하였고 시각화도 잘 하셨습니다.
        ![image](https://github.com/user-attachments/assets/9d316f76-6102-4f62-a6e4-d7dc5720141b)
        -  자체학습된 임베딩 레이어 잘 분석 하셨습니다.
        ![image](https://github.com/user-attachments/assets/5b3488a7-2b72-44cd-b59a-a82f2996730c)
        - 위에서 한국어 Word2Vec 을 가져 와야 하는데 GoogleNews-vectors 를 로드해서 학습이 잘 안 된 거 같습니다.
        - 따라서 아래 임베딩 결과도 잘 안나온거 같습니다. 이부분 수정하면 학습이 잘 될 거 같습니다.
        ![image](https://github.com/user-attachments/assets/133fd5fe-6c16-4964-9f04-ad485af58c01)

    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/0cb36640-25df-4ddd-a40f-5e2b3eded72f)
        - 핵심 부분에 주석을 보고 이해 할 수 있었습니다.
        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/45674e60-7aa9-4d52-86a2-ded5d0a60499)
        - 데이터 라벨 의문점을 잘 남겨 주셨습니다.
        ![image](https://github.com/user-attachments/assets/592c6e6c-2ebb-447e-af2b-166716a23576)
        - 정규 표현식을 통한 한글 외 문자 제거한 부분이 인상 깊었습니다.

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 회고가 없었던 점이 아쉬웠습니다.
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/be9b2ec2-e7b4-411d-9b7e-a4310ea7efc0)
        ![image](https://github.com/user-attachments/assets/27d8d55d-0a7a-4364-b9b9-539eae335076)
        - 모델 구성에서 학습 까지 잘 구성 되었습니다.




# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- load_data 함수에서 정규 표현식을 통한 한글 외 문자 제거 하는 부분이 좋았습니다.
- 데이터 라벨링을 보고 의문점을 가지고 생각해 봤던 점이 좋았습니다.
- 전체적으로 코드 잘 작성했고 3가지 모델에 대해 학습이 잘 이루어졌습니다.
- 마지막에 한국어 Word2Vec 을 가져 오는 부분만 수정 하면 좋을 거 같습니다.
- 고생하셨습니다!
