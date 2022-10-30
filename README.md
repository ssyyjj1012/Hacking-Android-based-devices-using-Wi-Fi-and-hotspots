# 부릉부릉
차량 공격(DoS, Fuzzy, Free, Malfunction) IVN 데이터셋을 분석하여 취약점 분석 및 시나리오 연구

## 팀 - 진재경
|이름|전공|학번|소속 팀|
|:--:|:--:|:--:|:--:|
|서영재|콘텐츠IT|20195178|Tensor|
|유수경|빅데이터|20205209|Tensor|
|양유진|빅데이터|20207149|Latte|

## 프로젝트 개발 툴
- Python
- Google Colab
- kali Linux
- wireshark


--------------------
2022년 10월 30일 업데이트
--------------------
## DATASET
###  FEATURE
- TIMESTAMP
- CAN ID
- DLC
- DATAFIELD
- TEMP(NORMAL/ABNORMAL)


## CAN ID별 데이터 분석
#### ex) CAN ID : 329
##### 1. FREE

![image](https://user-images.githubusercontent.com/52689953/198869586-b5807b30-46a7-4d57-b62d-860af868038c.png)

##### 2. FUZZY

![image](https://user-images.githubusercontent.com/52689953/198869514-5b8dd54f-fdd9-4517-96de-73bea7ed1bca.png)


##### 3. DOS

![image](https://user-images.githubusercontent.com/52689953/198869523-d52b00c0-b0b4-4a8d-8cde-12f7394a9ce6.png)


##### 4. MALFUNCTION

![image](https://user-images.githubusercontent.com/52689953/198869526-38f59959-f2e3-4852-8620-6777ba34cfc6.png)


## CAN ID와 TimeInterval에 대한 Sequence data 추출
- sequence length : 50 으로 설정
![image](https://user-images.githubusercontent.com/52689953/198869783-664acb13-58fe-4de8-b119-da1cb2be9ba6.png)



