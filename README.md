# Child-s-Fine-Motor-and-Haptic

소근육 발달과 햅틱의 연관성 연구<br/><br/>

![캡처1](https://user-images.githubusercontent.com/63523334/207372429-f37eb0b0-0e48-40e3-ad79-e42f0be48087.PNG)
<br/>
## 🖥️ &nbsp; 프로젝트 소개

 가. 과제 선정 배경 및 필요성
 소근육 발달이 필요한 아동, 노인, 혹은 재활치료자들을 위한 컨텐츠를 만들고자 했다. 디지털시대가 초래한 이래 디지털기기를 사용하게 되는 연령이 점차 낮아지고 있다. 실제 물건인 여러 도구와 놀이 기구 등을 통해 놀던 아이들이 이제 스마트폰과 스마트 패드를 사용하며 놀게 됐다. 그런 만큼 유아들의 소근육 사용량이 줄어들고 있다. 디지털기기를 사용하더라도 소근육 발달에 도움이 될 수 있는 방안을 고려하고자 하였다. 또한 재활치료를 진행할 때 가장 중요한 것은 ‘정확한 자세’로 ‘반복적’으로 진행해야하는 것이다. 정확한 자세를 판단해주는 전문가를 실시간 옆에 두는 것은 시간적으로 금전적으로 부담이 있는 일이다. 더불어 반복적으로 수많은 시행이 필요한 만큼 매우 고단하고 지루한 작업으로 느껴지기 쉽다. 이와 같은 해결책으로 디지털 공간을 생각했다. 디지털 세계에서는 사용자의 자세를 디지털로 센싱하여 사용자에게 자세의 정확성을 자동으로 알려주기 용이하며, 게임적인 요소를 추가하기 쉽기 때문에 지루함을 덜어낼 수 있을 것이다.
<br/>
 휴대폰을 이용한 컨텐츠, 혹은 PC, VR을 이용한 컨텐츠들도 가상 오브젝트와 직접적인 인터랙션이 아닌 간접적 인터랙션을 통해 소통하고 있다. 소근육의 발달에는 직접 오브 젝트들을 만져보며 소근육을 키워가는 것이 효과적이다. 그렇기에 햅틱 디바이스를 통해 사용자가 오브젝트들과 직접으로 인터랙션하게 하는 것이 필요하다고 생각하였다. 
<br/>
   나. 과제 주요내용
 물건을 만져보고, 옮기는 등 상호작용을 할 수 있는 컨텐츠를 만들고자한다. 햅틱 디바  이스를 선정하고, 사용자가 이 햅틱 디바이스를 사용하여 컨텐츠를 진행하도록 할 것이  다. 이 과정에서 근육의 사용 정도를 센싱하는 센서를 사용자에게 부착하여, 평면 디스   플레이를 이용할 때 생기는 근육 사용 정도와 햅틱 디바이스를 사용하여 생기는 근육   사용 정도를 비교하고자 한다. 
  <br/>
   다. 최종결과물의 목표
실제 물체와의 인터랙션, 터치 디바이스와의 인터랙션, 피드백 없이 핸드 트랙킹만 이용한 인터랙션, 햅틱 장비를 이용한 인터랙션, 위와 같은 네 가지 인터랙션을 사용하면서 측정된 근전도 데이터를 분석한다. 이 데이터를 토대로 가장 큰 근육 사용량을 제공하는 인터랙션 방법을 찾고자 한다. 또한 하나의 Task를 진행하는 동안 측정된 근전도 데이터를 Time Domain에서 DTW(Dynamic time wraping) 방법으로 유사성 분석하여 실제 인터랙션과 가장 유사한 인터랙션이 어떤 것인지 찾고자한다. 
<br/>
## 🕰️ &nbsp; 개발 기간
- 22.09.10 - 22.12.13

## 📚 &nbsp; Skills
- ### Languages <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white"/> <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=C%20Sharp&logoColor=white"/>

- ### Skills <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=Arduino&logoColor=white"/> <img src="https://img.shields.io/badge/Unity-%23000000.svg?style=flat-square&logo=unity&logoColor=white"/>  <img src="https://img.shields.io/badge/git-F05032?style=flat-square&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/Fusion360-0696D7?style=flat-square&logo=Autodesk&logoColor=white"/>

## 💁‍♂️ &nbsp; 팀원 구성
- 팀장: 김승채


## 🚩 &nbsp; 시연 영상
https://user-images.githubusercontent.com/63523334/207372906-c65d8260-aee4-4e3f-a635-3da84db38ded.mp4


<br/>

## 💻 &nbsp; 개발 내용
## 1) 컨텐츠 기획

소근육 데이터 분석을 위해 동일한 컨텐츠를 4가지 환경에서 진행해야한다. 
	1) 실제 물건을 이용한 컨텐츠
	2) 햅틱 피드백 없이 핸드트랙킹을 이용한 컨텐츠
	3) 햅틱 피드백과 핸드트랙킹을 이용한 컨텐츠
	4) 터치 스크린을 이용한 컨텐츠
이러한 컨텐츠를 위해 우선 실제 환경에서 쓰일 실제 물건을 구매하였다.

![image](https://user-images.githubusercontent.com/63523334/207374362-6337e8fb-042b-4bb3-98eb-f8dcef598177.png)

그림  칼라 도형 맞추기 학습완구

<br/>
## 2) 햅틱 디바이스 선정
두 전문가와의 인터뷰 이전에 펜 형태의 [그림2. 햅틱디바이스(3D Systems TouchX / Touch)]만을 사용할 계획이었다. 

![image](https://user-images.githubusercontent.com/63523334/207374400-f3f73407-eab0-45fb-9b19-47eb3828f0fb.png)

그림  햅틱디바이스(3D Systems TouchX / Touch)


하지만 전문가와의 인터뷰를 통해 장갑 형태의 햅틱 디바이스가 실제 소근육 사용과 더욱 유사한 소근육 사용을 보여줄 것으로 예상하게 되었다. 따라서 장갑 형태의 햅틱 디바이스를 사용한 근전도 분석도 추가하였다.

![image](https://user-images.githubusercontent.com/63523334/207374429-bc5150bd-3b4d-4bde-b669-73bfc9884b90.png)

그림  센스글러브 / 덱스모글러브


이번 학기 진행 중인 전자공학과 졸업 논문에서 햅틱 글러브를 제작하였다. 

![image](https://user-images.githubusercontent.com/63523334/207374480-57d809c2-e64a-465c-9870-4e57743d1ac4.png)

그림  전자공학과 New Meta팀 햅틱글러브

유아의 소근육 발달에 사용되는 놀이기구를 구매하였다. 이를 실측하여 직접 3D모델링 하였다. 3D모델을 유니티로 Import하여 각 인터랙션에 따라 사용 가능하도록 컨텐츠를 제작하였다. 립모션을 통해 핸드트랙킹을 구현하였고, 가상 손이 가상 물체를 집고 옮길 수 있도록 만들었다. 햅틱 장갑의 경우도 립모션을 사용하여 가상 물체를 옮기는 것은 동일하며, 그와 동시에 햅틱 피드백이 느껴지도록 했다. 햅틱 디바이스는 가상의 포인터가 물체를 집고 옮길 수 있으며, 이에 대한 햅틱 피드백이 디바이스의 핸들에서 표현된다.
위와 같은 방법들로 가상 물체와 인터랙션을 할 때 근전도 데이터를 측정한다. 
<br/>
## 3) 근전도 분석
이번 연구에 사용될 근전도 센서(EMG센서)는 DFRobot사의 SEN0240제품이다.  

 ![image](https://user-images.githubusercontent.com/63523334/207374495-20e53666-281a-4705-a729-b594d4d39e87.png)

그림  EMG센서_SEN0240-DFRobot


근전도 센서는 손등(물건 집기)과 팔뚝(물건 쥐기) 두 곳에 부착하고자 하였었다. 하지만 근전도 센서가 조금이라도 피부에서 떨어지면 노이즈가 심하게 끼는 문제가 있었다. 손등 부위는 손을 움직일 때마다 센서와 피부 사이에 틈이 생겼다. 이를 해결하기 위해 탄력이 있는 스트랩을 사용하여 센서가 피부에 완전히 접촉하도록 고정시켰다.



그림  실험을 통해 선정된 EMG센서 부착 부위 [왼-손등 / 오른-팔뚝]

근전도 분석은 지속적으로 근전도값을 출력하도록 하였으며, 동시에 10초의 주기로 Count를 세며 각 Count마다 근전도데이터의 평균과 최대값을 계산하여 출력되도록 하였다. 위의 출력값들을 실시간으로 엑셀에 저장되도록 하였다. 


그림  근전도 데이터 측정 및 저장


각각의 Count의 최대값을 기준으로 +-3초로 그래프의 범위를 지정하였다. 이 범위의 그래프들을 각 Task별로(초록-빨강-파랑-노랑 블럭 옮기기) 한 곳에 그래프를 그려 비교해보았다.

![image](https://user-images.githubusercontent.com/63523334/207374758-c0c893e3-de6d-4394-a844-caeae09378ab.png)

그림  Grab-EMG 데이터 그래프

![image](https://user-images.githubusercontent.com/63523334/207374772-534e8213-b204-48ce-8078-74c7b7a39c08.png)

그림  Grab-EMG 데이터 그래프
 
##4) Unity 컨텐츠 제작
립모션 컨텐츠와 햅틱 글러브 컨텐츠는 하나의 컨텐츠에서 동시 진행할 수 있도록 제작
하였다. 동일한 컨텐츠를 햅틱 디바이스를 이용하여 진행할 수 있도록 햅틱 디바이스용 컨텐츠를 제작하였다. 컨텐츠를 진행하는 동안 실시간으로 근전도 사용을 볼 수 있는 UI를 제작하였다. 다만 근전도 데이터를 측정할 때는 유니티와 연결하지 않고 유니티와 통신하는데 발생하는 딜레이를 고려해 아두이노에서 곧바로 데이터를 저장하였다. 

![image](https://user-images.githubusercontent.com/63523334/207376215-5527fa58-0900-441d-8e38-40574222d256.png)

그림  립모션&햅틱글러브 컨텐츠

![image](https://user-images.githubusercontent.com/63523334/207376288-8f9c1700-611d-4841-a063-5bad57f1da4e.png)

그림  햅틱디바이스 컨텐츠

<br/>
##5) Python을 이용한 DTW(Dynamic time wraping)분석
우선 Openpyxl을 사용하여 엑셀의 근전도 값들을 읽어 왔다. 읽어온 값들을 각각의 컨텐츠별 리스트에 Parsing해주는 작업을 완료하였다.

![image](https://user-images.githubusercontent.com/63523334/207376345-24131917-0e1f-4306-bf55-78db9083e688.png)

그림  엑셀 데이터 파이썬 변수로 불러오기


그 후 DTW(Dynamic time wraping)알고리즘을 사용하여 실제 컨텐츠와 립모션, 터치스크린, 햅틱장갑, 햅틱Touch 컨텐츠들의 그래프를 분석하였다.

![image](https://user-images.githubusercontent.com/63523334/207376423-50e4ee65-ee52-4c5a-ab55-dc3556296c5c.png)

그림  EMG-Pick-DTW 분석

![image](https://user-images.githubusercontent.com/63523334/207376451-79e50f28-9eee-4101-9c20-8e07e3625bae.png)

그림  EMG-Grab-DTW 분석


<br/>
##4. 수행결과
   가. 과제수행 결과
 각 컨텐츠 별로 동일한 Task를 진행하여 근전도 값을 비교하였다. 데이터를 비교하기 전 예상했던 결과와 실제 결과는 차이가 있었다. 데이터 분석 전 실제 데이터와 햅틱 장갑의 데이터가 가장 유사하고, 그 다음 립모션이 가장 유사할 것이라 예상하였다. 하지만 데이터 분석 후 나온 결과는 다음과 같다.

 
   나. 최종결과물 주요특징 및 설명
 우선 팔뚝에 부착한 근전도 센서로부터 분석한 Grab의 결과는 립모션이 1등을 하였고 햅틱 장갑이 2등을 하였다. 립모션과 햅틱 장갑은 매우 근소한 차이로 1등과 2등을 하였으며, 그 뒤로 터치스크린과 햅틱Touch가 각 3등과 4등을 하였다. 예상과 유사하게 립모션과 햅틱 장갑의 점수가 가장 높았다. 하지만 립모션이 햅틱 장갑보다 더욱 유사도가 높은 결과가 나왔기에 후속 연구에서 이에 대한 추가 분석이 필요할 것이다.

다음으로 손등에 부착한 근전도 센서로부터 분석한 Pick의 결과이다. 이번에도 립모션이 1등을 하였고 그 다음 터치스크린과 햅틱 장갑이 뒤를 이었다. 1등, 2등, 3등의 차이는 비교적 근소한 차이를 보인다. 손등의 근전도 분석에서 터치 스크린 컨텐츠가 실제 컨텐츠와 매우 비슷한 경향을 보이는 것이 확인됐다. 이에 대해 물건을 집고 옮기는 모션과 터치 스크린을 누르는 모션이 매우 비슷하기 때문으로 분석하였다. 또한, 손등에서도 립모션이 햅틱 장갑보다 유사도가 높게 나왔다. 이에 대한 분석 역시 후속 연구에서 다뤄져야 할 것이다. 

햅틱 디바이스가 손등, 팔뚝 분석 모두에서 제일 낮은 유사도를 보인다. 그에 대한 이유로 햅틱 디바이스의 경우 그라운드 디바이스이기 때문에 가상 물체의 무게를 느낄 수 있기 때문으로 분석된다. 이러한 이유로 다른 컨텐츠보다 근육 사용량이 월등히 높게 나온 것이다. 소근육을 많이 사용하기 때문에 소근육 발달 및 재활에 더욱 도움이 될 가능성이 높지만, 실제 물건을 집고 옮기는 인터랙션과는 차이가 가장 많이 나는 방법이다. 더욱 정확한 분석을 위해서는 후속 연구에서 실제 물체의 무게를 측정한 후 가상 물체에 이를 적용시켜야할 것으로 보인다.

다음의 결과로 알 수 있는 사실은 실제 물체와 인터랙션할 때와 가장 유사한 형태로 손을 움직이는 방법이 실제 인터랙션의 근전도 데이터 추이와 유사하다는 것이다. 그렇기에 립모션과 햅틱 장갑이 각 각 1등과 2등을 한 것을 볼 수 있다. 하지만 햅틱 피드백이 있는 햅틱 장갑보다 허공을 집는 립모션이 더 높은 유사도를 보인다는 점에서 예상과 다른 결과를 보였다. 더 많은 사용자의 인터뷰를 실시하여 많은 데이터를 확보하고 분석해서 립모션이 명확히 더 높은 유사도를 가지는지 확인해볼 필요성이 있다.

<br/>
##5. 기대효과 및 활용방안
   가. 기대효과
립모션과 햅틱 장갑의 총 점수가 확실한 차이를 보이지는 않는다. 하지만 실제 모션과 비슷한 모션의 인터랙션이 가장 높은 유사도를 지닌다는 것을 알 수 있었다. 이를 토대로 NUI(Natural User Interface)방식 즉 실제 모션과 같은 모션을 취할 때 실제 물건들과 인터랙션할 때 만큼의 소근육 발달 및 재활 효과가 있다는 것을 유추할 수 있다. 이를 바탕으로 더욱 다양한 인터랙션을 디자인하여 더 많은 사용자의 EMG데이터를 분석한다면 어떤 방식의 인터랙션이 소근육 발달 및 재활에 가장 큰 도움이 될지 결정지을 수 있을 것이다.

   나. 활용방안
현대의 아동들을 스마트폰, 스마트 패드를 비교적 더욱 많이 사용하고 있다. 이로 인해 실제 물체와 인터랙션하는 방법보다 소근육 발달이 뎌딜 것으로 예측할 수 있다. 현재까지의 결과를 토대로 터치 스크린보다 립모션 혹은 햅틱 장갑의 사용이 더욱 실제 인터랙션과 유사한 것을 알 수 있었다. 이를 참고하여 아동들이 단순히 터치하는 컨텐츠가 아닌 직접 손을 움직여 물체와 직접적인 인터랙션을 할 수 있도록 한다면, 아동들의 소근육 발달에 도움이 될 것이다. 

소근육 재활 치료에 있어서도 립모션 혹은 햅틱 장갑을 활용할 수 있을 것이다. 재활 치료에 가장 중요한 점은 정확한 자세와 꾸준함이다. 대면으로 이루어지는 재활 치료는 정확한 자세를 피드백 받기 위해 재활치료사와 만나서 진행해야한다. 이때 시간과 비용이 발생한다. 하지만 이를 가상공간에서 진행하고, 재활 치료 자세 피드백을 위한 AI가 만들어진다면 시간과 비용을 절약할 수 있을 것이다. 또한 기존의 아날로그 재활 치료 방식에서는 꾸준함을 가져가는데 지루함을 느낄 수 있다. 하지만 가상 환경에서 소근육 재활 컨텐츠를 진행한다면 다양한 컨텐츠와 컨텐츠마다 흥미를 유발 할 수 있는 기믹들로 사용자들의 흥미를 유지하면서 꾸준함을 지속시켜나갈 수 있을 것으로 기대한다.

<br/>
##6. 결론 및 제안
이번 연구는 물건을 집고 옮기는 블록 옮기기 소근육 발달 놀이에 초점이 맞춰져 있다. 이 컨텐츠에 있어 Grab의 결과 립모션, 햅틱 장갑, 터치스크린, 햅틱 디바이스 순서로 등수가 매겨졌다. Pick의 결과는 립모션, 터치스크린, 햅틱 장갑, 햅틱 디바이스 순서로 등수가 매겨졌다. 이 둘을 모두 합한 총 등수는 립모션, 햅틱 장갑, 터치스크린, 햅틱 디바이스 순서이다. 이 등수는 각 인터랙션이 얼마나 실제 인터랙션과 유사한 근전도 데이터 추이를 보이냐로 결정이 난다. 따라서 실제 물건을 집는 모션과 가장 유사한 립모션과 햅틱 장갑이 가장 높은 유사도를 보이는 것을 확인할 수 있었다. 하지만 이는 소근육 데이터의 경향성을 분석한 것이지 얼마나 근육을 많이 사용하였냐를 분석한 것이 아니다. 가장 많은 근육량이 사용된 인터랙션은 햅틱 디바이스로 다른 인터랙션보다 압도적으로 큰 근육량을 보였다. 이번 연구에서 햅틱 디바이스가 가장 낮은 점수를 받았지만 이는 소근육 발달에 가장 덜 도움이 된다는 의미로 해석해서는 안된다. 이를 명확히 하기 위해서는 소근육 사용량이 많을수록 소근육 발달에 도움이 되는지의 인과관계에 대한 후속 연구가 필요할 것이로 보인다. 또한 립모션과 햅틱 장갑의 점수에 큰 차이는 없었지만 Grab과 Pick에서 립모션이 모두 1등을 한 만큼 확실히 립모션이 햅틱 장갑보다 더 실제 모션과 같은지 확인이 필요하다. 이를 위해 더 정교한 햅틱 장갑을 사용해야 할 것이며, 더 많은 사용자 인터뷰를 통해 많은 데이터를 분석해야 할 것이다.





<br/>



#### 근전도 데이터 시각화
![visual](https://user-images.githubusercontent.com/100567791/203309770-d55a6a19-3637-4220-97a1-049e64e44045.png)

근전도 데이터를 나타내는 그래프와, 주파수 domain으로 변환하여 Spectrum의 변화를 나타내는 Spectrogram을 기능 구현하였다.

Spectrogram은 샘플링주파수를 10Hz, 데이터 크기를 16개로 설정하여 FFT로 얻은 값을 표시하였다.

<br/>

## 📖 &nbsp; 참고문헌
 Chun, H.-Y., Kim, J.-O., & Park, K.-H. (2010, October 1). Correlation of Human Carpal Motion and Electromyogram. Transactions of the Korean Society of Mechanical Engineers A. The Korean Society of Mechanical Engineers. https://doi.org/10.3795/ksme-a.2010.34.10.1393 

Geršak, Gregor, Huimin Lu, and Jože Guna. (2018). Effect of VR Technology Matureness on VR Sickness. Multimedia Tools and Applications 79.21-22 (2018): 14491-4507. Web.  

Guruswamy, V. L., Jochen Lang, and Won-Sook Lee. (2011). IIR Filter Models of Haptic Vibration Textures., IEEE Transactions on Instrumentation and Measurement 60.1 (2011): 93- 103. Web.  

Hae-Chan Na, Yu-Jin Lee, Su Young Kim, Yoon Sang Kim. (2022). A Study on Metaverse Education Platform: cases analysis and suggestion. Journal of Digital Contents Society, 23(5), 827-836.  

Ultraleap Co. Ltd. (2019). What is Haptic Feedback?, https:// www.ultraleap.com/company/news/blog/what-is-haptic-feedback/,  

Grigore C. Burdea. (1999). Haptic Feedback for Virtual Reality, Proceedings of International Workshop on Virtual prototyping, Laval, France, pp. 87-96, May.  

Cho Young Don. (2002). Types and Characteristics of Piezoelectric Sensors. Instrumentation Technology, April 2002.  

Son Jung Woo (2012). Haptic actuators in mobile devices. Journal of KSNVE, 22(6), pp. 25-30..  

HappyFaceFriend. (2021). TetrisWithHand, github, https:// github.com/HappyFaceFriend/TetrisWithHand.  

Park, S.-H., Hong, B.-K., Kim, J.-K., Hong, E.-P., & Mun, M.-S. (2011, August 1). Development of the Myoelectric Hand with a 2 DOF Auto Wrist Module. Journal of Institute of Control, Robotics and Systems. Institute of Control, Robotics and Systems. https://doi.org/10.5302/j.icros.2011.17.8.824 

Ma, Z., & Ben-Tzvi, P. (2015). Design and Optimization of a Five-Finger Haptic Glove Mechanism. Journal of Mechanisms and Robotics, 7, 041008. 

 M. Hosseini, A. Sengül, Y. Pane, J. De Schutter and H. Bruyninck(2018). ExoTen-Glove: A Force-Feedback Haptic Glove Based on Twisted String Actuation System. 27th IEEE International Symposium on Robot and Human Interactive Communication (RO-MAN), 2018, pp. 320-327, doi: 10.1109/ROMAN.2018.8525637. 

Pinhas Ben-Tzvi, Senior Member, IEEE, and Zhou Ma, Student Member, IEEE. (2015). Sensing and Force-Feedback Exoskeleton (SAFE) Robotic Glove. IEEE Transactions on Neural Systems and Rehabilitation Engineering, Vol. 23, No. 6.  

Zhe Cao, Student Member, IEEE, Gines Hidalgo, Student Member, IEEE, Tomas Simon, Shih-En Wei, and Yaser Sheikh. (2018). OpenPose: Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields, arXiv:1812.08008, Web  

Chen, Tianlang, Chen Fang, Xiaohui Shen, Yiheng Zhu, Zhili Chen, and Jiebo Luo. (2022). Anatomy-Aware 3D Human Pose Estimation With Bone-Based Pose Decomposition. IEEE Transactions on Circuits and Systems for Video Technology 32.1 (2022): 198-209. Web.  

Google LLC. (2020). Mediapipe, https://google.github.io/mediapipe/. Google LLC. (2019). Tensorflow Lite, https://www.tensorflow.org/lite.  

S. Juhn, C. Jamais, and P. Jerry. (2007). A Cross-Industry Public Foresight Project, Acceleration Studies Foundation.  

Kim, Koun (2019). Effect of Virtual Reality Rehabilitation Program with RAPAEL Smart Glove on Stroke Patient's Upper Extremity Functions and Activities of Daily Living, Journal of The Korean Society of Integrative Medicine, Volume 7, Issue 2, Pages. 69-76.  

Leeanne Carey, Richard Macdonell, Thomas A Matyas. (2011). SENSe: Study of the Effectiveness of Neurorehabilitation on Sensation: a randomized controlled trial, Neurorehabil Neural Repair. 2011 May; 25(4), 304-313.  

Kim Ji Hoon (2018). Influence of Upper extremity function, Activities of Daily Living, Therapeutic Flow and Quality of Life in Stroke patients. Journal of Digital Convergence. Vol. 16. No. 12, pp. 417-425. 

신재영, 김성욱, 이윤성, 이형탁 and 황한정. (2019). LSTM을 이용한 표면 근전도 분석을 통한 서로 다른 손가락 움직임 분류 정확도 향상. 의공학회지, 40(6), 242-249. 

 공주(2019). 손가락 굴곡과 신전 힘 생성에서 뇌성마비 환자의 다중 손가락 시너지. 국내석사학위논문 서울대학교 대학원, 2019. 서울 
