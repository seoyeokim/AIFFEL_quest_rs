# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김서영
- 리뷰어 : 황동주


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/0946994b-3e9e-4a8d-837f-a6c295f9cf92)
        ![image](https://github.com/user-attachments/assets/4178c294-b69b-4f9c-9706-01bd2da4e1b5)
        ![image](https://github.com/user-attachments/assets/d5bfc84b-4762-43cd-a7d6-ec006dd8e914)
        ![image](https://github.com/user-attachments/assets/8b70f938-2d0f-46d6-b18b-770f7e067d48)
        ![image](https://github.com/user-attachments/assets/99dfb9fc-4032-49db-bc03-5f3013d433aa)  
        - 모델 학습 그래프
        - CAM, Gred-CAM 시각화 및 바운딩 박스
        - 두 모델의 비교까지 잘 완료 해주셨습니다.

        
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/0c6378c8-4125-4be8-916b-273a7f972e88)
        ![image](https://github.com/user-attachments/assets/97294fa2-f306-4225-a180-6b624af9da57)
        ![image](https://github.com/user-attachments/assets/146b156d-4b21-4aef-a286-414133ddf987)
        ![image](https://github.com/user-attachments/assets/1fde9af8-c3b5-4bc8-8f26-ca9bebe7c626)  
        - CAM 과 Grad-CAM 구현 방식등이 잘 기술 되어 있습니다.
        - CAM 과 Grad-CAM 구현 함수에 주석으로 잘 작성 되어 있습니다.
        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/b4b23294-0e4f-48ac-8b6a-626a3b276deb)
        - 변경 사항을 기록으로 잘 남겨 주셨습니다.
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/a93f0518-a575-47f7-b71d-afc67925f6df)
        - 회고에 대해 잘 남겨 주셨습니다.

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/db6681ce-83f0-4b56-a42e-2f9dc4696805)
        ![image](https://github.com/user-attachments/assets/789fa997-408d-4d30-8ab6-9235b62da354)
        ![image](https://github.com/user-attachments/assets/e124f9c0-fb4d-4228-afaf-34873d8245ab)
        - 단계별 코드 작성을 보기 좋게 잘 작성했습니다.



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- 전체적으로 코드가 목적에 맞게 단계별로 잘 작성 되어 있었습니다.
- tfds 옵션에 대해 기록을 남겨주셔서 확인을 할 수 있었습니다.
- 구현 과정에서 생겼던 문제점들과 개선점에 대해서도 회고에 잘 기록 되어 있었습니다.
- 이번 과제도 열심히 하신 내용들이 담겨 있어 잘 보았습니다.
- 이번 과제 역시 잘 마무리 하셨고 수고하셨습니다!
