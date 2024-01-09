# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박준
- 리뷰어 : 윤빛나

평가문항	상세기준
1. 번역기 모델 학습에 필요한 텍스트 데이터 전처리가 한국어 포함하여 잘 이루어졌다.	구두점, 대소문자, 띄어쓰기, 한글 형태소분석 등 번역기 모델에 요구되는 전처리가 정상적으로 진행되었다.
2. Attentional Seq2seq 모델이 정상적으로 구동된다.	seq2seq 모델 훈련 과정에서 training loss가 안정적으로 떨어지면서 학습이 진행됨이 확인되었다.
3. 테스트 결과 의미가 통하는 수준의 번역문이 생성되었다.	테스트용 디코더 모델이 정상적으로 만들어져서, 정답과 어느 정도 유사한 영어 번역이 진행됨을 확인하였다.


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
1. 모델 학습에 필요한 번역기 모델에 요구되는 전처리가 정상적으로 되었습니다.
   
<img width="891" alt="스크린샷 2024-01-06 19 21 46" src="https://github.com/currybab/first-repository/assets/100587126/1775e99e-dc63-4e04-9ef0-56e04e216d60">

<img width="903" alt="스크린샷 2024-01-06 19 22 52" src="https://github.com/currybab/first-repository/assets/100587126/773c6120-c73b-4b29-9482-d66e5f73895a">

2. 모델 인코딩 디코딩 과정을 거쳐 정상적으로 구동되며 훈련 과정에서 training loss가 잘 떨어지면서 학습이 진행되는 것을 확인할 수 있습니다.

   <img width="630" alt="스크린샷 2024-01-06 19 26 22" src="https://github.com/currybab/first-repository/assets/100587126/1aff0c6a-6697-4dcd-93df-af7b2bfc343f">
   
<img width="865" alt="스크린샷 2024-01-06 19 26 42" src="https://github.com/currybab/first-repository/assets/100587126/574c42e7-dc52-4e47-b435-1b1034a03320">

3. 디코더 모델이 정상적으로 만들어져서 정답과 어느정도 유사한 영어 번역이 진행됨을 확인하였습니다.

<img width="617" alt="스크린샷 2024-01-06 19 37 13" src="https://github.com/currybab/first-repository/assets/100587126/2f3e6800-3651-4835-83f2-edd732444fa2">

<img width="783" alt="스크린샷 2024-01-06 19 37 39" src="https://github.com/currybab/first-repository/assets/100587126/5b1a0c42-19f5-4f1d-91dd-2d5f86928507">


- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

어떠한 이유로 결과치가 안좋아질 것이라 생각하고 코드를 짰는지에 대한 설명을 해놓아서 왜 이렇게 코드가 진행되는지에 대해 이해가 쉬웠습니다.

<img width="630" alt="스크린샷 2024-01-06 19 28 12" src="https://github.com/currybab/first-repository/assets/100587126/52efe11c-36d1-46ea-afdb-ec1b940f4ac3">

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**

나올 수 있는 결과들에 대해 모두 시각화하여 어떠한 시도를 해보았는지를 확인할 수 있었습니다.

<img width="779" alt="스크린샷 2024-01-06 19 30 20" src="https://github.com/currybab/first-repository/assets/100587126/eae4e4bb-6a0e-40d6-ac64-5cb6d3c19363">

<img width="865" alt="스크린샷 2024-01-06 19 30 29" src="https://github.com/currybab/first-repository/assets/100587126/ed3f0a98-27fc-4833-adcd-afcf0ac1ac70">

        
- [x]  **4. 회고를 잘 작성했나요?**

좋았던 사례들과 좋지 않았던 사례들에 대한 설명과 결과에 대한 아쉬움과 궁금한 점 그리고 알게 된점들에 대해 자세히 남겨주셨습니다.

<img width="908" alt="스크린샷 2024-01-06 19 31 40" src="https://github.com/currybab/first-repository/assets/100587126/821d1e3b-d628-4660-9fab-45001b5869fc">

- [x]  **5. 코드가 간결하고 효율적인가요?**

코드가 실용적으로 작동되도록 잘 작성해주셨고 중간 중간 길이 체크를 하며 확인하는 코드를 작성해주셔서 이해하는데에 도움이 되었습니다.

<img width="920" alt="스크린샷 2024-01-06 19 33 42" src="https://github.com/currybab/first-repository/assets/100587126/9d71dbc1-c429-466f-8e1a-8c9365bc68d4">

<img width="807" alt="스크린샷 2024-01-06 19 34 46" src="https://github.com/currybab/first-repository/assets/100587126/626fee2e-7a8d-476a-8b53-fb2a8f5a82fb">

<img width="591" alt="스크린샷 2024-01-06 19 34 53" src="https://github.com/currybab/first-repository/assets/100587126/72308afc-ba3e-429f-ba2b-24c2eb38dd18">



