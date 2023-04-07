# Wafer Defeat 분류 2D CNN 모델링
## 산업공학종합설계 프로젝트

![image](https://user-images.githubusercontent.com/88662101/230546089-14fb8793-fd27-4062-946f-8daa17417dc7.png)

<br>
프로젝트 선정 이유 : 2022 차량용 반도체 수급 문제와 반도체 수율 문제가 대두됨
수율을 올린다면 CAPA증가에 따라 반도체 수급이 원할하게 될 것임

<br>
<br>
<br>
<br>

![image](https://user-images.githubusercontent.com/88662101/230546209-e4bd8ec1-372e-4b14-8022-aedd208b0054.png)

<br>
데이터 전처리 - 데이터 형태 파악
웨이퍼 맵 : 2차원 array 형태로 0,1,2로 구성
다이사이즈, lotname – 웨이퍼 25장당 1로트
aferindex – 웨이퍼 별 ID
trainTestLabel – 훈련/테스트 용인지 구분
failureType – 불량유형(주 타겟)

<br>
<br>
<br>
<br>

![image](https://user-images.githubusercontent.com/88662101/230546607-54f0e346-3c60-4ee0-9c86-849d0f2ac407.png)

<br>
불량 유형의 시각화

<br>
<br>
<br>
<br>

![image](https://user-images.githubusercontent.com/88662101/230546662-2b095698-bd47-47bc-afe3-f5549ce4744d.png)

<br>
오토 인코더 – 이미지를 더욱 선명하게 하기 위해서 만든 전처리 층/ 데이터의 품질 향상

<br>
<br>
<br>
<br>

![image](https://user-images.githubusercontent.com/88662101/230546810-d1ca473c-0b95-45ae-9d58-e6d6e8bfc8d7.png)

<br>
Edge case들의 넷다이가 가장 높았고, 데이터 불균형으로 인해 데이터 증강으로 이를 해소

<br>
<br>
<br>
<br>

![image](https://user-images.githubusercontent.com/88662101/230546952-5b856980-e163-48dd-9d24-4e2ff84f3fa0.png)

<br>
2D CNN을 통해 이진분류 모델 개발

<br>
<br>
<br>
<br>

![image](https://user-images.githubusercontent.com/88662101/230547003-5f732b84-daf1-4c3b-b7d5-967729ca8a61.png)

<br>
BAD Class는 edge case 2가지를 의미하고, 증강 갯수에 따른 예측 정확도 93% 달성


-----

# 백엔드 개발 과정


