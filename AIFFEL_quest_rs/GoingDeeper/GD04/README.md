# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김서영
- 리뷰어 : 이창민


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 루브릭을 기준으로 프로젝트의 요구사항과 실험 등이 명시적으로 남아있다.
        - 1. 텍스트 이미지 리사이징, ctc loss 측정을 위한 라벨 인코딩, 배치처리 등이 적절히 수행되었다.
        - <img width="629" alt="1 1 1" src="https://github.com/user-attachments/assets/5c26c92e-792e-4fd6-af67-70532ed44186" />
        - <img width="577" alt="1 1 2" src="https://github.com/user-attachments/assets/1e5e1c3a-47f0-488a-817a-a649fa4fe501" />
        - <img width="860" alt="1 1 3" src="https://github.com/user-attachments/assets/bd4bad30-ff6f-4194-96c1-96b719b8dcc5" />
        - 2. 학습결과 loss가 안정적으로 감소하고 대부분의 문자인식 추론 결과가 정확하다.
        - <img width="757" alt="스크린샷 2024-12-23 오전 10 44 24" src="https://github.com/user-attachments/assets/b6a21d60-9c71-44cd-b92b-d9c46b259fad" />

        - 모델 학습 로그는 남아있지 않지만, 예측 결과를 통해 학습이 순방향으로 이루어졌다는 것을 확인 가능하다.
        - <img width="472" alt="1 2 1" src="https://github.com/user-attachments/assets/539b3171-4f26-4afb-8367-3a504a2772ab" />
        - <img width="644" alt="1 2 2" src="https://github.com/user-attachments/assets/f02153a2-e6da-4911-bab1-03b3bbe63c28" />
        - <img width="633" alt="1 2 3" src="https://github.com/user-attachments/assets/9fd2218e-39d6-4236-bad5-4dd06a4d68f1" />
        - 3. 샘플 이미지를 원본으로 받아 OCR 수행 결과를 리턴하는 1개의 함수가 만들어졌다.
        - <img width="707" alt="1 3" src="https://github.com/user-attachments/assets/b7db2634-ee2d-4047-ba94-a5574e440ddd" />







        
        
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - detect_text 함수에서 주석을 통해 이해하기 편하게 코드를 작성했다.
        - <img width="655" alt="스크린샷 2024-12-23 오전 10 54 42" src="https://github.com/user-attachments/assets/ac334589-4062-4555-8ec2-9fd54d5c12d4" />

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 제대로 예측되지 않은 사례에서 문제점을 도출하고 그에 관한 해결책으로 새로운 실험을 진행했다.
        - 여기서는 시퀀스의 길이를 조정하여 성능 차이를 확인하고자 했다. max_len = (default, 12, 6, 32)
        - <img width="898" alt="3 1" src="https://github.com/user-attachments/assets/60691ad6-af7d-4f5c-9fcb-2732365f0916" />
        - <img width="405" alt="3 2" src="https://github.com/user-attachments/assets/1c5d3c2f-7689-4854-b255-7880f094c77f" />
        - <img width="409" alt="3 3" src="https://github.com/user-attachments/assets/02c101eb-f0a5-4bb5-aab3-fb5bbd8c6aae" />




        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 진행한 프로젝트에 대한 자기 고찰, 그리고 발생한 문제 해결 방안에 대한 실험 분석 등이 자세히 나타나있다.
        -  <img width="738" alt="4" src="https://github.com/user-attachments/assets/31f194fb-ab54-4cd8-9d0a-83d6e38a9aa6" />


        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 목표로 했던 recognize_img 함수 뿐만 아니라 새롭게 작성된 코드들 대부분 간결하고 효율적으로 나타나있다.
        - <img width="707" alt="5" src="https://github.com/user-attachments/assets/65087393-42da-4a68-acd3-f7d0066a0f65" />



# 회고(참고 링크 및 코드 개선)
```
교안에 충실하게 프로젝트를 진행했고, 거기서 발생한 오류들을 종합해서 시각파일로 저장해서 좋았다.
오류와 해결방안을 팀원들이 공유해서 각자 실험하는 과정이 필요할 것 같다고 코드 리뷰를 진행하며 느꼈다.
살짝 아쉬웠던 부분은 시퀀스를 조정할 때마다 학습 코드가 반복해서 작성되어 있는 부분이었는데, 모듈화를 통해서 재사용성을 늘렸다면 더욱 간결한 코드가 됐을 것 같다.
```
