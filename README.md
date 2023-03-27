# Python_Handwritten_Hangul_Classification  
한글 손글씨를 분류하는 지도학습 기반 딥러닝 모델입니다.  
Deep learning AI model that classifies handwritten Hangul.  
  </br>

1. 'ttf_to_png.ipynb'로 한글 손글씨 폰트 52종을 '가'부터 '힣'까지 유니코드를 사용해 이미지로 추출합니다.  
2. 'proj.ipynb'로 추출된 이미지를 numpy array로 변환한 다음, 학습합니다.  
3. 28*28 사이즈의 흰 배경(FFFFFF)에 검은 글씨로 한글 손글씨 이미지를 만들면 AI가 이게 무슨 글자인지 분류합니다.  
  </br>
  
1. 'ttf_to_png.ipynb' : 52 types of handwritten style Korean fonts are extracted into images using Unicode from '가' to '힣'.  
2. 'proj.ipynb' : Convert the extracted image to numpy array, and then learn.
3. If you create a Hangul handwriting image with black letters on a white background(FFFFFF) of 28*28 size, AI classifies what letter this is.  
