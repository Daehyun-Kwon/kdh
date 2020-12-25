# 이 파일은 신한금융그룹 디지털금융공학과정 : 디지털금융공학을 위한 자연언어 처리기술 기말 과제에 대한 주석 파일입니다

# 이 파일은 
# 한국어 감정분석 2019516011(korean).ipynb와
# 영어 감정분석 2019516011(english).ipynb에 대한 주석 파일입니다.


# 한국어 감정분석 2019516011(korean).ipynb에 대한 설명입니다.

# 실행 방법은 구글 드라이브에 트레인 데이터 및 테스트 데이터를 업데이트 한후,
# 구글 콜랩 GPU를 사용하여 실행하였습니다.
# 구글 드라이브 주소는 아래와 같습니다.
# gdrive/My Drive/Colab Notebooks/2020_NLP/nsmc/ 이며,
# 공유 주소는 아래와 같습니다.
# https://drive.google.com/drive/folders/1LDxLVjghY1_JErCLgaMx_LFKiaHNezf4?usp=sharing

# 학습 데이터 출처입니다.
# 학습 데이터는 '네이버 영화 리뷰 데이터'를 사용하였으며 세부 주소는 다음과 같습니다.
# https://github.com/e9t/nsmc.git

# 모델 출처입니다.
# 블랙보드 - 공지사항 - 12월 13일자 '기말고사 공지' 게시물의 최하단 참고자료 링크中 첫번째 링크
# http://aidev.co.kr/chatbotdeeplearning/8709를 우선 참고하였습니다
# 해당 링크에서 제시된 첫번째 깃허브 주소 https://github.com/deepseasw/bert-naver-movie-review을 참고하였습니다.
# (세부 코드 주소는 https://github.com/deepseasw/bert-naver-movie-review/blob/master/bert_naver_movie.ipynb 입니다.)
# 상기 링크의 모델은 Hugging Face의 PyTorch BERT를 사용하였으며 세부 주소는 https://huggingface.co/bert-base-multilingual-cased 입니다.
# 상기 링크의 모델은 Chris McCormick의 블로그를 참조하여 한글에 맞게 수정된 모델입니다. 세부 주소는 https://mccormickml.com/2019/07/22/BERT-fine-tuning 입니다.

# 테스트 데이터 출처 입니다.
# 테스트 데이터 ko_data.csv는 https://www.kaggle.com/c/korean-sa-competition-dfe610/data 참조하였습니다.


# 영어 감정분석 2019516011(english).ipynb에 대한 주석 파일입니다.

# 실행 방법은 구글 드라이브에 트레인 데이터 및 테스트 데이터를 업데이트 한후,
# 구글 콜랩 GPU를 사용하여 실행하였습니다.
# 구글 드라이브 주소는 아래와 같습니다.
# gdrive/My Drive/Colab Notebooks/2020_NLP/friends/ 이며,
# 공유 주소는 아래와 같습니다.
# https://drive.google.com/drive/folders/1LDxLVjghY1_JErCLgaMx_LFKiaHNezf4?usp=sharing

# 학습 데이터 출처입니다.
# 학습 데이터는 미국 시트콤 '프렌즈' 대사를 사용하였으며 세부 주소는 다음과 같습니다.
# http://doraemon.iis.sinica.edu.tw/emotionlines/index.html

# 모델 출처입니다.
# 블랙보드 - 강의자료 - 실습7(BERT) - 두번째 링크
# https://colab.research.google.com/drive/1EMzEfTYjYLgEHjCCP1vEr9oOZLXMocGh?usp=sharing 를 참고하였습니다.
# 제시된 링크에서는 bert-base-uncased를 사용하였으나 이번 과제에서는 bert-large-uncased를 사용하였으며,
# 진행 경과를 시각화하여 보여주는 tqdm 업데이트가 있어 이를 반영하였습니다.
