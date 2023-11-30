
AIFFEL Campus Online 7th Code Peer Review Templete

코더 : 박준

리뷰어 : 이승제

🔑 **PRT(Peer Review Template)**

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    1. 공백과 특수문자 처리, 토크나이징, 병렬데이터 구축의 과정이 적절히 진행되었다.  
 
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/a60b4ea2-1872-4bd0-a415-42973d720a65) <br/> *특수문자 전처리*


        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/354927a1-3f70-4841-91ad-3b22557755fc) <br/> *토크나이징*



        **-> 전처리, 토크나이징등 데이터 처리 과정이 잘 진행되었다.**

       
    2. 구현한 트랜스포머 모델이 한국어 병렬 데이터 학습 시 안정적으로 수렴하였다.  

        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/987d9d65-615d-4e07-9481-87496d65d4fb)
        
        **-> loss와 accuracy가 안정적으로 수렴하는 것을 볼 수 있다.**

       
    3. 한국어 입력문장에 맥락에 맞는 한국어로 답변을 리턴하였다.  
     
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/4db9bf2c-e863-4608-bb20-7b53de71286c)

        **-> 정확도 높은 답변을 해준 것을 볼 수 있다.**

<br/>

---

<br/>

- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

    ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/cb0c4403-3d93-4869-a7e4-2dcfe1e12dba)  

  
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인  
        
        **-> transformer 모델을 구성하는 함수를 작성하고 주석이 잘 달려있다.**  


    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.  
        **-> 패딩을 위한 마스크 처리를 해주고 인코더 -> 디코더 -> 완전연결층으로 생성된다.**
    
    
    - 주석을 보고 코드 이해가 잘 되었는지 확인  

        **-> 동작하는 이유를 주석을 보고 잘 이해할 수 있었다.**

<br/>

---

<br/>
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나”, ”새로운 시도 또는 추가 실험을 수행”해봤나요?**

    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/bca12aba-bd5a-40a0-9b09-70846a44dc45)  
        
        **-> 하이퍼 파라미터를 조정하여 실험했다.**

<br/>

---

<br/>
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해 배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/1da187aa-2b08-4bc1-805c-12cc6947243b)

        **-> 프로젝트를 진행하면서 아쉬운 점과 느낀점이 기록이 되어있다.**


    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/efa7edfc-1d81-4106-8773-462df01ecfeb)
        
        **-> 진행되면서 변화하는 loss 과정을 출력하여 이해를 돕고 있다.**

<br/>

---

<br/>
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인  
        
        **-> class명은 CamelCase, 함수명은 소문자로 구성되어 준수하였다.**


    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/628ae2ca-6ccd-4fe3-882f-c546b992cca2)

        **-> sentence_generation 함수로 입출력을 효율적으로 할 수 있게 하였다..**
