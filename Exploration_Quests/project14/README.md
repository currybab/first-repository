# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박준
- 리뷰어 : 김찬중


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?** 네
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 코드를 캡쳐해 근거로 첨부
     
        1. Augmentation을 활용하여 이미지 데이터를 증강하여 활용하였습니다.
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/32fc7336-18bd-49ef-bdaf-279f29a04e32)
     
        2. U-net과 discriminator 모델 구현을 아주 잘 하였습니다.
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/d139ae7c-3852-461b-90a1-546c8a7a90ea)
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/d44f610f-0ad4-48f8-b7e8-9194e9ee1d18)
     
        3. 40 epoch 학습을 진행한 후 5epoch 마다 train과 validation set 데이터를 이용해 출력물을 확인해 보았습니다.     
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/8383e7fa-402e-4589-a65d-eb56ebed5b3d)
        
    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?** 네
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
     
        - 주석을 통해 모델 구현의 진행상황을 알수 있었습니다.
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/14d15b08-e4f4-4fae-8a22-dbbd985eddd4)
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/ac76f2dd-aa75-4d25-9c8a-87627dc6d6f3)
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/aa74fd2f-6219-40f6-b42d-eaa6d90b28fc)





        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?** 네
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
     
        - 모델의 성능 체크를 위하여 모델을 짧은 에폭으로 한번, 많은 에폭으로 한번 두번 돌려보면서 성능체크를 시도하였습니다.
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/095bec70-079a-4cbd-b915-8103950724cc)
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/e9659007-0d6f-49b7-9a9c-9384a8eb9c86)


        
- [x]  **4. 회고를 잘 작성했나요?** 네
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
     
        - 회고를 통해 아쉬운 점과 배운점 그리고 느낀점이 잘 드러나있습니다.
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/ccb993fe-7751-452e-aa0e-0763f427eaea)

        
- [x]  **5. 코드가 간결하고 효율적인가요?** 네
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
     
        - 함수화를 통해 코드의 간결화를 추구하였고, 이로인해 가독성이 좋았습니다.    
        - ![image](https://github.com/kcj4800/first-repository_BJ/assets/128466813/5a26fbec-6cf1-4453-8ea5-e622458a726f)


주어진 시간동안 수행하기 어려운 조건의 프로젝트였음에도, 전날 몸이 아파 노드 학습을 온전히 시행하지 못한 그루원의 학습을 끝까지 도와서 함께 결과물을 내었다는 부분에서 큰 점수드리고 싶습니다.
사실 이 부분이 이곳 아이펠에서 추구하는 가장 이상적인 모습이지 않았나하는 생각이 듭니다. 앞으로도 항상 주변 그루분들과 상생하며 아름답게 성장하시길 바랍니다. 식사 맛있게 하세요.

# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

