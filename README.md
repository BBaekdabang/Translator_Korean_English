# Translator_Korean_English
# seq2seq 모델을 활용한 번역기 구축 프로젝트
<img width="800" img height="400" src="https://user-images.githubusercontent.com/113493692/212307322-fa2a234f-2d7d-4822-a00c-7cd95c1b8b71.png">


프로젝트 기간 : 2022.09.03. ~ 2022.09.12.

---

# 1. Subject
- RNN 모델의 이해
- seq2seq 모델을 활용한 번역기 구축

# 2. Dataset

<img width="800" img height="400" src="https://user-images.githubusercontent.com/113493692/212307928-2ee6bd5d-fbc6-4b08-98ed-5158b4181ab9.png">


# 3. Model

- LSTM (Following Paper)

<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212309558-b8aa0de4-af72-4fb7-b683-32bb05641828.png'>

- LSTM (hidden units / input direction / embedding dim / Tokenizer)

<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212310526-3a83aff0-b44b-4d94-9dc3-0eeffac35e9c.png'>
<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212310584-6cdd0a75-8af4-4f26-b432-83114c285c67.png'>
<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212310636-093d9051-b5b6-48e2-adb0-d9842556ce2a.png'>
<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212310683-d6a8ddf4-66b8-49f0-872e-37e979009f74.png'>

- LSTM with attention

<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212312564-830432db-56c3-4253-a3f8-28351ef41cdd.png'>

- LSTM vs GRU (with attention)

<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212312641-2ac6dedf-511e-4dc7-8dac-5e305e67d5b0.png'>


# 4. Result

- 모델 선정
<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212313017-25dc5015-3095-4f2f-b9ce-ea5cef7e98b8.png'>

- 번역기 성능
<img width = '1000' img height = '520' src = 'https://user-images.githubusercontent.com/113493692/212313037-df406446-96aa-4f37-bd9b-31575502ea14.png'>


# 5. Conclusion

-신조어 학습, out-of-vocabulary 처리 어려움

-학습데이터 양 부족 
