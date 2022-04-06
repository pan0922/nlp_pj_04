# 새싹 자연어처리 프로젝트 - 네이버 영화추천 시스템 구현
MLP project, movie recommentation system

### 설명 
자연어 처리 기법을 활용한 영화추천 서비스 구현
- 사용한 전처리 모듈:
- 사용 모델: word2vector, wmf, tfidf

## 과정 
과정
과정 및 사용한 라이브러리
- 크롤링 --> (1) BeautifulSoup을 활용한 네이버 영화 리뷰 ID, Nid값 크롤링, (2) scrapy를 활용한 영네이버 영화 title, review 크롤링 
- 전처리 --> (1)Tokenizer, (2) preprocessing, (3) stopword, (4) wordcloud
- 모델링 --> (1) word2vector, TFIDF, NMF, LDA
- 시연 --> (1) django, pyQT
django 파일 공유--> https://drive.google.com/file/d/1sWx13Z1LCWygS1gHQfOof5aHgOQZeAV4/view?usp=sharing
