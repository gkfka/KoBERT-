# KoBERT를 이용한 개체명인식

### data

- 모두의 말뭉치 - 개체명 말뭉치(2020)

- json파일을 읽어 KoBERT 토크나이저를 이용하여 가공함
- 토크나이저 이용 후 문자가 유니코드로 바뀌어 생기는 오류를 제거함


- data_utils안에 ner_dataset.py에서 train과 test 말뭉치의 경로를 변경해야함




### train

```
python train_bert_bilgru.py
```
### test
```
python inference.py
```



---
https://github.com/SKTBrain/KoBERT

https://github.com/eagle705/pytorch-bert-crf-ner
