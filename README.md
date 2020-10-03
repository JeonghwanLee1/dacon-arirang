# :bulb: 아리랑 위성영상 AI 객체 검출
 아리랑 위성영상에 내재된 다수의 객체를 신속, 정확하게 탐지 가능한 인공지능 알고리즘 개발 (컴퓨터 비전,객체 검출,mAP)

## :airplane: 데이터셋
1) train(1.34GB)

- images(1.27GB), 800장) : 학습용 이미지 데이터   
<img src="https://user-images.githubusercontent.com/43736669/94993183-20fe4700-05ca-11eb-9d7b-e9b2bfdfee0a.png" height="30%" width="30%">    <img src="https://user-images.githubusercontent.com/43736669/94993192-370c0780-05ca-11eb-917d-7394de253ad2.png" height="30%" width="30%">    <img src="https://user-images.githubusercontent.com/43736669/94993373-90c10180-05cb-11eb-8775-e4fd5701f211.png" height="30%" width="30%">

- json(66.6MB, 800개) : 학습용 라벨링 데이터

* 바운딩 박스의 좌표 표기법은 DOTA dataset 표기법을 따릅니다.


2) test(161MB)

- images(161MB, 100장) : 평가용 이미지 데이터



3) sample submission.csv

- 제출용 csv 파일

## :thought_balloon:파생 데이터

## :computer: 사용 모델    

## :chart_with_downwards_trend: 결과  
  
## :book: 기술 스택  
python,jupyter notebook, numpy, pandas, sklearn, pydotplus  
