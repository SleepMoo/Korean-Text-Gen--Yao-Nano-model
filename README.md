# Korean-Text-Gen--Yao-Nano-model

Lang: Korean

극초소형 모델인 야오 모델입니다.

파일크기가 400MB 정도 되기 때문에, 구글드라이브로 가중치를 공유한다는점 양해 바랍니다.

+허깅페이스(huggingface) 에 안올리는 이유;

-초보들은 이용하기 어렵고,

-로그인이 조금 까다롭기 때문.

그래서 그나마 대중적인 깃허브(Github) 에 업로드 합니다.

가중치 링크(구글드라이브) 는 아래와 같습니다.

*가중치 파일과 실행 파이썬 파일이 같이 들어있습니다!*


https://drive.google.com/file/d/1NHvGn4Ydr_nZKkAWPOp_aobzHjUo7aD0/view?usp=sharing


모델 실행 방법

```
!pip uninstall -y transformers tokenizers huggingface_hub accelerate safetensors
   !pip install --no-cache-dir \
   transformers==4.57.3 \
   tokenizers==0.22.2 \
   huggingface_hub==0.36.0 \
   accelerate \
   safetensors
```

으로 먼저 라이브러리를 다운받아 줍니다.

버전은 위와 같습니다.(조금이라도 달라지면 오류 발생 위험있음 주의바람.)

**모델 구동시 만약 응답이 알아볼수 없을정도로 깨져보인다면, 토크나이저 라이브러리 문제.**

!python YaoNano_NORMAL/examples/use_yaonano_model.py
