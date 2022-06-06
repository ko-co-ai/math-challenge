# Tutorials For KMWP(Korean Math Words Problem)  
안녕하세요 저희는 [Aiffel](https://aiffel.io/)에서 [KMWP](https://github.com/tunib-ai/KMWP) 학습에 도전했던 팀입니다.  
이 저장소는 다음 KMWP 문제에 도전할 팀을 위한 가이드를 목적으로 만들었습니다  
데이터에 대한 전처리부터, 학습에 사용할 레퍼런스 조사, 대형 모델을 사용하기 위해 Google Cloud Platform  설정 등, 자연어 처리 내용 외에도 우리가 알고 사용해야할 기본적인 내용들이 너무 많기에 다음 팀의 시간은 아끼고, 여기서 한발짝 더 나아갈 수 있도록 기록을 남기려고 합니다.  
여기에 있는 내용들을 모르더라도 다양한 방법으로 시도할 수 있습니다.  
그러나 이 도구들을 활용하게 된다면 더 다양한 방법을 시도해볼 수 있을겁니다.  
저희가 안내할 내용은 다음과 같습니다.  

## 목차  

(본인의 폴더에 맞게 링크 달아주시면 됩니다)

데이터 EDA -> 깃헙링크  
데이터 정제내용 -> 깃헙링크  

### Model Base Code

1. [Base-transformer model](https://github.com/koco-tunlp/math-challenge/tree/main/transformer-basecode)

2. [tensorflow, SKT-kogpt-trinity model](https://github.com/koco-tunlp/math-challenge/tree/main/skt-kogpt-trinity-basecode)  

3. [tensorflow, Roberta-Large For Class labeling](https://github.com/koco-tunlp/math-challenge/tree/main/roberta-large-for-classlabeling)

4. [pytorch, SKT-kogpt2-base-v2 model](https://github.com/koco-tunlp/math-challenge/tree/main/skt-kogpt2-base-v2-basecode)  

모델 예측 결과 및 후처리 -> 깃헙링크  

6. [모델 서빙](./model-serving/)

## Performance
...


## Reference  
[CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models for Code Understanding and Generation](https://arxiv.org/pdf/2109.00859.pdf)  
  
[CodeBERT: A Pre-Trained Model for Programming and Natural Languages](https://arxiv.org/pdf/2002.08155.pdf)  

[KoEPT: Transformer 기반 생성 모델을 사용한 한국어 수학 문장제 문제 자동 풀이](http://koreascience.or.kr/article/CFKO202125036187306.pdf)  
  
[Training Verifiers to Solve Math Word Problems](https://arxiv.org/pdf/2110.14168.pdf)  
  
[Semantically-Aligned Equation Generation for Solving and Reasoning Math Word Problems](https://aclanthology.org/N19-1272.pdf)  
  
[Measuring Mathematical Problem Solving With the MATH Dataset](https://arxiv.org/pdf/2103.03874.pdf)


## Authors  
<img src=https://user-images.githubusercontent.com/53106649/171995972-81c4962e-08b2-4290-95ea-62fbf9c15c36.png  width="100" height="100" />

