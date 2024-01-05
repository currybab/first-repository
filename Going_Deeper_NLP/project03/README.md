# AIFFEL Campus Online Code Peer Review Templete

- 코더 : 박준

- 리뷰어 :윤빛나

1. 주어진 영화 코퍼스를 바탕으로 워드임베딩 모델을 정상적으로 만들었다. 워드임베딩의 most_similar() 메소드 결과가 의미상 바르게 나왔다.
2. 영화 구분, 장르별로 target, attribute에 대한 대표성있는 단어 셋을 생성하였다. 타당한 방법론을 통해 중복이 잘 제거되고 개념축을 의미적으로 잘 대표하는 단어 셋이 만들어졌다.
3. WEAT score 계산 및 시각화를 정상적으로 진행하였다. 전체 영화 장르별로 예술/일반 영화에 대한 편향성 WEAT score가 상식에 부합하는 수치로 얻어졌으며 이를 잘 시각화하였다.



# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**

1. 워드 임베딩 모델을 정상적으로 만들었으며 워드임베딩의 most_similar() 메소드 결과가 의미상 바르게 출력됩니다!

<img width="619" alt="스크린샷 2024-01-03 17 26 55" src="https://github.com/currybab/first-repository/assets/100587126/d03ae2e2-d964-423f-aaf9-6797bb203ec0">

<img width="402" alt="스크린샷 2024-01-03 17 28 16" src="https://github.com/currybab/first-repository/assets/100587126/1b677b96-3c5c-419a-9373-2c4c7d234315">

2. 영화 구분, 장르별로 target, attribute에 대한 대표성있는 단어 셋을 생성하였으며 중복이 잘 제거되고 단어 셋이 잘 만들어졌습니다.

<img width="825" alt="스크린샷 2024-01-03 17 30 01" src="https://github.com/currybab/first-repository/assets/100587126/f66a60ac-474b-44c9-9feb-2422e3ff79e1">

<img width="728" alt="스크린샷 2024-01-03 17 35 51" src="https://github.com/currybab/first-repository/assets/100587126/692f058f-6b98-403a-b75b-64bfad37fed7">

3. 전체 영화 장르별로 예술과 일반 영화에 대한 편향성 WEAT score가 알맞게 측정되었고 이를 잘 시각화하였습니다.

<img width="812" alt="스크린샷 2024-01-03 17 38 13" src="https://github.com/currybab/first-repository/assets/100587126/c403e679-0a7e-457b-8856-8bc10b8f03e9">

<img width="384" alt="스크린샷 2024-01-03 17 38 00" src="https://github.com/currybab/first-repository/assets/100587126/78e49d5c-349c-411b-98ce-f2f8687e9074">


    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

코드에 대한 적절한 주석들로 설명을 잘 해주셨고 중간중간 진행 과정에 대해 설명도 남겨주셔서 이해하기가 쉬웠습니다.

<img width="743" alt="스크린샷 2024-01-03 17 39 19" src="https://github.com/currybab/first-repository/assets/100587126/8342098e-389b-4b1d-bf41-8da79255e0f2">

<img width="774" alt="스크린샷 2024-01-03 17 41 00" src="https://github.com/currybab/first-repository/assets/100587126/b48a06c1-d05d-4e2b-a7ed-8331b9bd68a6">


        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**

n을 크게 잡아주거나 장르들에 대한 단어축을 고를때에도 스텝과는 다르게 상위의 단어들을 고르지 않는 선택을 하는 방식을 선택하여 세세하게 프로젝트를 진행하였고 그 과정을 잘 남겨주셨습니다.

<img width="462" alt="스크린샷 2024-01-03 17 40 48" src="https://github.com/currybab/first-repository/assets/100587126/63dfd398-8712-4b8c-9146-c209499377a7">


<img width="797" alt="스크린샷 2024-01-03 17 39 39" src="https://github.com/currybab/first-repository/assets/100587126/697ba4c6-dfd9-43c5-aa3c-ffaf9b041919">


        
- [x]  **4. 회고를 잘 작성했나요?**

이번 프로젝트를 통해 느낀 점과 결과에 대한 자신의 생각을 잘 적어주셨습니다.

<img width="741" alt="스크린샷 2024-01-03 17 45 17" src="https://github.com/currybab/first-repository/assets/100587126/8e12099e-0f3c-42a5-8598-9b264480edae">


        
- [x]  **5. 코드가 간결하고 효율적인가요?**

자칫 복잡해질 수 있는 코드를 for 반복문을 사용하여 attribute를 골라낼때 i행을 제외한 나머지 행에 해당 단어의 다른 문서 존재여부를 측정하고 없을 시에만 attribute에 추가하는 방식을 택하여 코드가 간결하고 효율적이게 작동되도록 작성해주셨습니다.

<img width="752" alt="스크린샷 2024-01-03 17 48 11" src="https://github.com/currybab/first-repository/assets/100587126/6b8297a7-8dd5-40db-97ac-44afc56d75b6">


