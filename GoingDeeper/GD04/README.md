# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김재성
- 리뷰어 : 임정민


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          <img width="1946" height="1348" alt="image" src="https://github.com/user-attachments/assets/d2863d35-fd34-4d55-bb4f-b7355fcaef31" />
          <img width="1810" height="1017" alt="image" src="https://github.com/user-attachments/assets/47b76940-9c05-489d-8976-b1be97077609" />
          <img width="1964" height="306" alt="image" src="https://github.com/user-attachments/assets/8af39ec5-d122-44a6-89f1-e39c3df853bc" />
          <img width="1209" height="900" alt="image" src="https://github.com/user-attachments/assets/337a64b1-16b6-4793-8773-dce178b066c4" />
          <img width="1267" height="888" alt="image" src="https://github.com/user-attachments/assets/72514e23-01d0-4a29-9bf1-eb7937e0c9f0" />
        - 모델 학습부터 평가까지 진행하셨고 시각화도 적절하게 수행해 주셨습니다.

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="1494" height="1243" alt="image" src="https://github.com/user-attachments/assets/a9aa2bdf-a01f-48f5-b427-bb7a486989da" />
        - 모델 설계 관련 코드인데, 이전 단계에서 진행한 내용과 모델 설계 단계를 순차적으로 주석을 통해 설명해주셔서 코드 리뷰하는데 도움이 많이 되었습니다.

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="1935" height="542" alt="image" src="https://github.com/user-attachments/assets/6fccc53a-0d84-4e63-9fc0-2cd0aa51ab77" />
          <img width="1942" height="405" alt="image" src="https://github.com/user-attachments/assets/6b6e02a1-61d0-49ec-95c8-7ec48e592720" />
        - LMS 상에서 GPU 연결이 어려웠다고 말씀해 주셨는데, 코드 중간 마다 GPU 연결을 확인하는 셀이 있어 계속해서 문제 해결을 시도하려는 모습을 확인할 수 있었습니다.
        - 또한 Mecab 설치 오류는 커널 재시작을 통해 해결할 수 있음을 인사이트로 남겨주셔서 문제 원인 및 해결 과정을 살펴볼 수 있었습니다.

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="1760" height="365" alt="image" src="https://github.com/user-attachments/assets/5f4967d2-8815-4fcc-9e4a-f2823573330c" />
        - 프로젝트를 진행하면서 느꼈던 아쉬운 점과 느낀 점을 회고에 잘 작성해 주셨습니다.
        - 작성해주신 회고를 보고 같은 오류를 겪고 계셨다는 것을 알게 되어, 조금 빠르게 트러블 슈팅을 공유 드리면 좋았을 텐데 아쉽습니다.

        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="1019" height="564" alt="image" src="https://github.com/user-attachments/assets/7a0dcc4b-2101-4a14-a610-3c9f9df31d0d" />
          <img width="1270" height="1188" alt="image" src="https://github.com/user-attachments/assets/ffad57d6-b334-49a4-904d-9f655612cb36" />
        - 대부분의 코드들이 함수 형태로 작성하여 코드가 중복 없이 깔끔하게 정리되어 있었습니다.


# 회고(참고 링크 및 코드 개선)
```
깔끔하게 코드를 작성하셔서 리뷰할 때 불편함 없이 읽어나갈 수 있었습니다. 저는 코드가 항상 긴 편이라 깔끔하게 작성하신 분들의 코드를 참고해서 보완해야겠습니다.
모델 설계 부분에서 모델에 대한 요약 부분(summary)도 제시되어 있어서, 실제 모델이 어떻게 구성되어 있는지 확인할 수 있었습니다.
로스도 적절한 수준에서 떨어져서 조금 더 보완하면 더 좋은 성능을 내는 번역기를 만들 수 있지 않을까 싶습니다. 고생 많으셨습니다!
```

