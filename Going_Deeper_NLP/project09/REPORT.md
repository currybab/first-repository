총 9개의 파일로 이루어진 거대한 일감이였던것 같다.(그렇다고해서 다 했다는 것은 아니다)

1. base-foundation-model-check.ipynb  
2. base-SFT.ipynb  
3. base-RM.ipynb  
4. base-PPO.ipynb
5. dataset-aug-SFT.ipynb
6. dataset-aug-PPO.ipynb
7. model-change-SFT.ipynb
8. model-change-PPO.ipynb  
9. bleu-try.ipynb  

먼저 1~6은 base 모델이였던 skt/kogpt2-base-v2를 활용하여 진행하였다.

2~4번 과정에서는 이전 노드의 내용을 그대로 진행하였다.

5~6번 과정에서는 base 상태에서 sft 데이터셋에 대하여 eda를 진행한다음에 koeda라이브러리를 활용하여 rs,rd 두개만을 활용하여 augmentation을 진행하였다.
그리고 해당모델을 actor모델로 사용하여 ppo를 진행하였다.

7~8번 과정에서는 기본 모델을 skt/ko-gpt-trinity-1.2B-v0.5로 교체하여 진행하였다. 모델이 매우 크기 때문에 rm모델의 경우 기존의 모델을 그대로 활용하였다.
또한 optimizer가 adam인 경우 훈련 자체가 불가했기때문에 optimizer를 adafactor로 교체하였으며 ppo과정에서 또 oom문제로 인해 fp16으로 모델을 로드하여서 훈련시킬 수 있었다.

마지막으로 9번에서는 세가지 과정을 통해 만든 모델을 육안 및 지표로 확인하려고 하였다. 육안상으로 큰 차이는 없었지만 기존에 없었던 질문인 경우에 그래도 skt/ko-gpt-trinity-1.2B-v0.5를 베이스로 활용한 모델이 비교적 잘 답변하는 모습을 볼 수 있었고 augmentation한 모델도 기본 모델보다는 나은 결과가 있었다.

bleu스코어를 측정하려하였으나 generation 결과가 엉망진창인 탓에 0점이 나와 1-gram결과만을 활용하여 대강 그래프를 그려보았고. 결과는 뭐 그다지 의미 없는것 같다.

기본 모델을 교쳬하는 과정에서 꽤 많은 시간을 쓰게 되었는데 결과적으로 훈련을 성공할 수 있어서 그때 기분이 좋았다.

