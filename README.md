# 일기 감정 분석 후 노래 추천

- project notion : https://uncovered-ceramic-be3.notion.site/73b9ca06c8b2441797fcbd797c21998c

- 23.09.19 ~ 24.01.25

# about dataset

\*\* 모든 데이터는 kobert 모델학습에 맞춰 전처리를 마침

label = ['기쁨', '사랑', '분노', '불안', '상처', '슬픔', '외로움']

## 대화 데이터

- AI HUB 감성 대화 말뭉치

  - https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=86

  - filtered_corpus_data.xlsx

- chatbot data

  - https://github.com/songys/Chatbot_data?tab=readme-ov-file

  - filtered_love.xlsx

- chatGPT로 직접 생성

  - filtered_lonely.xlsx

## 노래 가사 데이터

- 멜론 플레이리스트 크롤링

  - lyrics.xlsx

- 토큰 크기에 맞춰 가사 길이 조절
