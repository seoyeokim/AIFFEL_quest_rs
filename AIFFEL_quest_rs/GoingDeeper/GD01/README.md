# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김서영
- 리뷰어 : 황동주


# PRT(Peer Review Template)
- [▲]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/144c0e76-dd48-49e9-9232-e10442952585)
        ![image](https://github.com/user-attachments/assets/e021d45b-f31b-4a83-a896-086e96dba5e2)
        - ResNet 모델 구현 부분은 잘 완성 하셨습니다.
        - 데이터셋 load 부분 수정 하셔서 학습이후 모델들 비교까지 마치면 좋을 거 같습니다.


        
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/c09fa33b-883c-4ce6-9e10-af3a5be40b6a)
        ![image](https://github.com/user-attachments/assets/550547a9-7a79-4838-a282-166b6c4e1574)
        ![image](https://github.com/user-attachments/assets/78842c9a-c6ea-4c9d-bdcc-ee485c4e54a1)
        ![image](https://github.com/user-attachments/assets/51d4e80f-97f0-48b3-a003-0751a9e29f50)
        ![image](https://github.com/user-attachments/assets/77b1f684-66e3-435f-90a4-9b0e6d930d74)
        - ResNet block 에서 34, 50 구분하는 부분
        - Skip Connection 차원 맞추는 부분
        - ResNet-34 모델 생성 하는 부분들이 주석으로 잘 표현 되어 있었습니다.
        - 디버깅 하셔서 ResNet-50 부분도 구현 하시면 좋을 거 같습니다.
        - build_resnet 함수 부분에 "# VGG 모델" 주석은 수정 부탁드립니다.
        

        
- [▲]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
        - 데이터 load 부분에서 발생 된 에러 부분의 수정 사항을 업데이트 해서 기록으로 남겨 두시면 좋을 거 같습니다.
        - 프로젝트 완료 후 추가 실험이나 결과에 대한 부분을 업데이트 해두시면 도움이 될 거 같습니다.
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/31182623-e2a4-43cd-9634-6780066c4dd5)
        - 오늘의 회고를 잘 남겨 주셨습니다.

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/4abdb743-0e2a-4ba7-9882-89ff148a4a8a)
        ![image](https://github.com/user-attachments/assets/5d5304f1-a088-4e5d-980f-985620acba2d)
        ![image](https://github.com/user-attachments/assets/48be0eef-28b7-4872-827d-1962726b5042)
        ![image](https://github.com/user-attachments/assets/2b6a56de-c817-4258-8cf4-612011c3b9cf)
        - ResNet 모델를 함수별로 구분해서 잘 작성하셨습니다.
        - 모델별 compile 부분 구분해서 잘 작성되어 있습니다.


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- 이번주 학습을 같이 했는데 시간이 많이 부족한 상황에서도 최대한 진행 잘 하셨습니다.
- 디버깅할 시간이 부족해서 끝까지 완료 못한 부분은 추후 진행 하셔서 마무리 잘 하시면 좋을 거 같습니다.
- 다음번에는 프로젝트에 시간을 좀 더 투입해서 진행 하면 좋을 거 같습니다.
- DLTON 부터 오늘까지 계속 정신 없이 달려 왔는데 정말 고생 많이 하셨습니다.
- 저도 다른분 코드 리뷰 하면서 배운 부분이 많이 있었고 다시 한번 생각할 수 있는 계기가 되었습니다.
