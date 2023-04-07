#Wafer Defeat 분류 모델링
##산업공학종합설계 프로젝트

![image](https://user-images.githubusercontent.com/88662101/230546089-14fb8793-fd27-4062-946f-8daa17417dc7.png)
프로젝트 선정 이유 : 2022 차량용 반도체 수급 문제와 반도체 수율 문제가 대두됨
수율을 올린다면 CAPA증가에 따라 반도체 수급이 원할하게 될 것임

<br>
<br>

![image](https://user-images.githubusercontent.com/88662101/230546209-e4bd8ec1-372e-4b14-8022-aedd208b0054.png)
데이터 전처리 - 데이터 형태 파악
웨이퍼 맵 : 2차원 array 형태로 0,1,2로 구성
다이사이즈, lotname – 웨이퍼 25장당 1로트
aferindex – 웨이퍼 별 ID
trainTestLabel – 훈련/테스트 용인지 구분
failureType – 불량유형(주 타겟)
