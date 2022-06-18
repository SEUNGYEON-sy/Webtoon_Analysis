# Webtoon_analysis

개요 : 네이버 웹툰의 댓글을 분석하여 자주 사용되는 키워드 추출을 통한 독자들의 반응 분석

순서 :
 1. 데이터 수집
 2. 긍정, 부정 댓글 감성 분석(이진 분류)
 3. 긍정 댓글 라벨링
 4. 다중 분류 모델 구축
 5. 모델을 통한 웹툰 댓글 분류
 6. 시각화(GUI 기반 추천 시스템)


파일 설명 :
- 데이터 수집
- - webtoon_image_crawl
- - all_webtoon_comment_crawl
- - webtoon_number_crawl
- - Omniscient_Reader_comment_crawl
- - labeled_data_classification

- 모델
- - pos_neg_modeling
- - create_and_apply_model_allComment

- 시각화
- - webtoon_analysis_result_window
