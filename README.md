# Roberta(base)_Sentiment_Anaylsis-Friends-
Transformers Roberta(base) 모델을 활용한 감성분석(시트콤 Friends data)

# 실행방법

0. src 폴더의 'friends모델_v3_roberta_submit.py' 복사
혹은 
https://colab.research.google.com/drive/1UO9wTMHJaZZcYeVLi0GU11ndiOfD7QqN?usp=sharing 실행
1. 구글 colab에서 실행하는 것을 권고(로컬 사용시 version.txt에 있는 환경을 모두 설치해야함)
2. 구글 드라이브의 디렉토리와 Colab을 연동(코드 1~2번째 셀 실행)
3. raw data에 있는 'Friends' 폴더를 다운받아 구글 드라이브 'drive/MyDrive'경로에 설치
4. 구글 colab 런타임 유형 변경 > GPU환경
5. 모두 실행

# 참고 소스코드 및 문헌
## Hugging Face BERT Chris McCormick의 오픈소스 
https://colab.research.google.com/drive/1PHv-IRLPCtv7oTcIGbsgZHqrB5LPvB7S#scrollTo=PGnlRWvkY-2c

## 네이버 영화리뷰 감정분석 with Hugging Face BERT
https://colab.research.google.com/drive/1Xs99-e4g6KS5Alu7z9CnrWX0J_f5HBsQ#scrollTo=muU2kS2GCh4y

## Hugging Face Transformers 공식 library
https://huggingface.co/transformers/_modules/transformers/models/electra/modeling_electra.html#ElectraModel 참고
