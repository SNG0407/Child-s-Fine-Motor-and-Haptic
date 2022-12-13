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

## 3) 근전도 분석
이번 연구에 사용될 근전도 센서(EMG센서)는 DFRobot사의 SEN0240제품이다.  

 ![image](https://user-images.githubusercontent.com/63523334/207374495-20e53666-281a-4705-a729-b594d4d39e87.png)

그림  EMG센서_SEN0240-DFRobot


근전도 센서는 손등(물건 집기)과 팔뚝(물건 쥐기) 두 곳에 부착하고자 하였었다. 하지만 근전도 센서가 조금이라도 피부에서 떨어지면 노이즈가 심하게 끼는 문제가 있었다. 손등 부위는 손을 움직일 때마다 센서와 피부 사이에 틈이 생겼다. 이를 해결하기 위해 탄력이 있는 스트랩을 사용하여 센서가 피부에 완전히 접촉하도록 고정시켰다.

![image](https://user-images.githubusercontent.com/63523334/207374571-e685db57-a193-4a77-8220-4bcf3fa3cbd7.png)

그림  실험을 통해 선정된 EMG센서 부착 부위 [왼-손등 / 오른-팔뚝]

근전도 분석은 지속적으로 근전도값을 출력하도록 하였으며, 동시에 10초의 주기로 Count를 세며 각 Count마다 근전도데이터의 평균과 최대값을 계산하여 출력되도록 하였다. 위의 출력값들을 실시간으로 엑셀에 저장되도록 하였다. 

![image](https://user-images.githubusercontent.com/63523334/207374741-33d345ab-4c7d-4696-98fa-8258b22bdf92.png)

그림  근전도 데이터 측정 및 저장


각각의 Count의 최대값을 기준으로 +-3초로 그래프의 범위를 지정하였다. 이 범위의 그래프들을 각 Task별로(초록-빨강-파랑-노랑 블럭 옮기기) 한 곳에 그래프를 그려 비교해보았다.

![image](https://user-images.githubusercontent.com/63523334/207374758-c0c893e3-de6d-4394-a844-caeae09378ab.png)

그림  Grab-EMG 데이터 그래프

![image](https://user-images.githubusercontent.com/63523334/207374772-534e8213-b204-48ce-8078-74c7b7a39c08.png)

그림  Grab-EMG 데이터 그래프
  

<br/>


- 햅틱 장갑은 가상의 물체를 잡을 경우 모터가 손가락에 연결된 실을 잡아당기며 손가락에 힘을 주게 된다.
- 물체를 세게 쥘수록 물체의 탄성력 계산을 통해 실을 더욱 잡아당긴다. 이를 통해 물체의 탄성력, 반발력을 느끼게 해준다.

<br/>

- 유니티에서는 립모션을 통해 핸드트랙킹을 구현하였다. 
- 컨텐츠에서 가상의 손이 물체를 만지면 각 손가락과 물체에 주는 압력을 계산하게 된다.
- 이 계산된 값과 어떤 손가락인지를 아두이노로 블루투스를 통해 전달한다. 
- 이 정보들을 토대로 아두이노에서 해당 손가락에 특정 길이의 실을 당긴다.

<br/>

- 근전도 컨텐츠를 위해 근전도 센서를 착용하면 아두이노에서 근전도 데이터를 블루투스 통신으로 유니티에 전송한다.
- 유니티에서는 이 근전도 데이터를 토대로 그래프를 보여주며 현재 근전도 값, 평균값, 공을 몇 번 쥐었는지, 물건을 몇 번 옮겼는지, 각 Task당 평균과 최대값을 알려주는 UI가 있다.

<br/>

## 시스템 설계도
![그림1](https://user-images.githubusercontent.com/100567791/203299160-8a1f30f4-2928-4c80-96c1-8dc98018c2a1.png)

## Object Modeling – PC Application
![그림2](https://user-images.githubusercontent.com/100567791/203299509-f07af04f-d569-47f4-ac6b-60f1d1825ba6.png)

## Object Modeling – Haptic Glove

![그림3](https://user-images.githubusercontent.com/100567791/203299698-4d8b20e4-2784-477f-ab57-3eafb64e332c.png)

## Event Modeling – Unity&Arudino
![그림4](https://user-images.githubusercontent.com/100567791/203299820-65e19ece-4040-461f-9db8-2479849feebd.png)


## 각도에 따른 실의 길이 추적 방법(유니티)
<img width="636" alt="image" src="https://user-images.githubusercontent.com/100567791/203300820-d73d8f07-8704-48af-8ae4-355723b319c8.png">

## 가변저항에 따른 실의 길이 추적 방법(아두이노)
<img width="604" alt="image" src="https://user-images.githubusercontent.com/100567791/203300834-863f87b2-ef91-41ea-bb5f-ec97e0b759bc.png">


## Bluetooth 통신
- 목적: 아두이노 보드에 HC-06 블루투스 칩을 추가하고 외부 전원을 사용하여 사용자의 활동 범위를 넓히고자 한다.
- 원리: 아두이노와 컴퓨터를 블루투스를 통해 연결시킨 후 유니티에서 컴퓨터로 보낸 데이터를 그대로 아두이노 보드로 전달하고자 한다. 
- 데이터의 통신 방향: 유니티 -> 컴퓨터 -> 아두이노 보드
 
> 방법1) 3개의 데이터(변수)를 순차적으로 보내는 방법
> 1. Index – 3개의 손가락 중 어느 손가락에 해당하는 데이터인지
> 2.	IsTouched -  힘이 전달되었는지 유무(True or False)
> 3.	Fs – Force를 만들기 위해 필요한 실의 길이 변화량

> 방법2) 배열을 이용하여 한꺼번에 데이터를 보내는 방법
> [float1, float2, float3] 과 같이 배열을 만들어 각각 손가락에 전달되어야 하는 Fs(Force를 만들기 위해 필요한 실의 길이 변화량)를 한꺼번에 전달하는 방법(전달될 힘이 없다면 0값 입력) - Char의 형태로 데이터를 Unity에서 보낸 후 아두이노IDE에서 parsing을 통해 float1, float2, float3를 각각 서보 모터로 전송. 
> 방법 2를 통해 유니티에서 아두이노로 데이터를 보내기로 결정하여 유니티에서 특정 char을 보냈을 때 컴퓨터의 Bluetooth Serial Monitor에서 해당 char을 받을 수 있는지 테스트할 수 있는 UI를 유니티 내에서 만들었다. 
> 또한, 반대 방향으로도 통신이 가능하도록 Bluetooth Serial Monitor에서 보낸 char 데이터가 Unity 내 UI에 출력되도록 코드를 작성하였다.
  
보내고자 하는 데이터는 위와 같으며 방법2의 통신을 사용했다.

![bluetooth1](https://user-images.githubusercontent.com/100567791/203304083-ac5dc925-d6ff-411a-a3c7-74bea2bc04a5.png)


![bluetooth2](https://user-images.githubusercontent.com/100567791/203304146-a092fa6b-3387-4720-8772-629bfa0a60d3.png)
<Char 형태로 Unity와 Arduino 간 양방향 블루투스 통신이 성공한 모습>

<br/>

- 아두이노의 시리얼 통신은 Asynchronous 시리얼 통신 이므로 블루투스 칩 HC-06의 synchronous 전송 속도는 최대 2.1Mbps이다.
- 본 프로젝트에서는 Baud rate을 9600으로 설정하므로 ASCII Code를 기준으로 1초에 9600개의 symbol을 보낼 수 있다.
- 통신에서 ASCII Code는 1 symbol이 8bit이므로 9600 Baud rate은 초당 9600*8=76800bit를 송, 수신하는 것이므로 2.1Mbps 속도를 가진 HC-06이 안정적으로 데이터를 전달할 수 있다.
- 또한, 이전 데이터와 다음에 송, 수신할 데이터가 관계가 없다는 점에서 데이터를 float 형태로 3번 보내는 것보다 char 형태로 한꺼번에 보내는 것이 더 효율적이라고 판단하였다.

<br/>

![Bluetooth3](https://user-images.githubusercontent.com/100567791/203304910-9a4caca5-9b7d-49cd-8025-45ca13969d5b.png)


![Bluetooth4](https://user-images.githubusercontent.com/100567791/203304920-0e3f94bf-6f0a-4323-8315-2ceb081c74a2.png)

Parsing에 성공하여 string 형태로 받은 데이터를 int형 데이터로 아두이노에서 분리시켰다.

3개의 int형으로 분리한 데이터들을 각각 해당하는 모터로 값을 전송.

<img width="440" alt="bluetooth6" src="https://user-images.githubusercontent.com/100567791/203305178-73123746-d16f-4e1b-864a-d21d4692e236.png">


## Object Deform
![image](https://user-images.githubusercontent.com/100567791/203305338-fa74d847-464b-4d7c-bc02-c51918a5e25a.png)


- 컴퓨터 그래픽스에서 3차원 공간의 객체는 Polygon들로 구성된 Mesh로 정의된다.
- Polygon은 3개의 정점(Vertex)들이 모여 형성하는 하나의 삼각형을 가리킨다.
- 핸드트래킹된 손이 물체를 쥐면 물체의 형태를 변경시키기 위해서, 손가락이 주는 압력을 입력 받아 물체의 정점 정보들을 실시간으로 업데이트한다.
- 물체의 변형 과정은 손가락의 압력 -> 탄성력 -> 감쇠로 총 3단계로 이루어진다. 
- 정점들이 이동하는 방향벡터는 압력 지점에서 정점을 향한다. 
- 역제곱 법칙(inverse square law)에 의해서, 정점들이 손가락으로부터 받는 압력은 손가락이 힘을 가한 지점과의 거리의 제곱에 반비례한다.
- Mesh의 해상도와 크기에 따라서 정점 간의 거리가 1보다 작을 수 있기 때문에 정점이 받는 힘을 $1\over(1+ax)^2$ (a=감쇠(attenuation) 계수, x=거리) 형태로 설정한다.
- 탄성력은 F = kx(k= 탄성계수, x=변한 길이)이므로 정점의 복원력은 정점의 현재 위치가 정점의 초기 위치와 떨어진 만큼 증가시킨다.
- 정점의 탄성력은 시간이 흐를수록 감쇠(damping)한다.


## 근전도 센서 EMG
### 1. 아두이노 소스코드 <br/>

<img width="480" alt="code1" src="https://user-images.githubusercontent.com/100567791/203306876-41170a25-ecea-4556-bd8d-c30b18dbd59a.png">


<img width="487" alt="code2" src="https://user-images.githubusercontent.com/100567791/203306884-394ae26c-0843-4ef6-ae93-3aa352171e92.png">

### 2. 테스트 사진 <br/>
두 가지 상황으로 테스트를 실시하였다.
첫 번째는 공을 쥐는 상황이며, 두 번째는 물건을 집고 옮기는 상황이다.

첫 번째 상황에서 EMG센서는 팔뚝에 위치시켰고, 두 번째 상황에서는 손등에 위치시켰다.

#### 상황1)

<img width="492" alt="image" src="https://user-images.githubusercontent.com/100567791/203307187-d89bd544-b0d0-4e9d-8673-4f02a973ad3d.png">

허공을 쥘 때와 실제 공을 쥘 때의 EMG 데이터 값을 시리얼 모니터로 출력해보았다. 


<img width="626" alt="image" src="https://user-images.githubusercontent.com/100567791/203307205-31f0b50a-eebc-4a35-8587-6a022ec8bc71.png">

실제 공을 쥘 때 더 높은 데이터 값들이 다량 출력되는 것을 확인하였다.

#### 상황2)

<img width="727" alt="image" src="https://user-images.githubusercontent.com/100567791/203307290-95b4a620-8815-4b94-b019-3d237e2c9d6a.png">
이는 블럭을 집고 옮길 때도 마찬가지였다.

EMG 데이터 값을 시리얼 플로터로 확인한 사진이며 실제 물건을 집을 때 높은 데이터가 출력되었다.

### 3. 근전도 센서 데이터 분석 방법 <br/>

<img width="452" alt="data1" src="https://user-images.githubusercontent.com/100567791/203308313-78bce8bc-69f3-458f-adf0-290c51e60b98.png">

- 유니티 UI로 Task버튼과 Contents버튼이 있고 그랩과 픽업의 카운팅 표시가 있다. 
- Task 버튼을 누르면 stop을 누르기 전까지의 시간동안 근전도 센서의 평균값을 계산하여 표시해준다. 
- Contents버튼은 컨텐츠 하나를 전부 끝내는 동안 평균적인 근전도 센서 값을 계산한다. 
- Grab은 공을 세게 쥐는 모션을 카운팅하고, Pick up은 물건을 집어 옮기는 모션을 카운팅한다.


<img width="453" alt="data2" src="https://user-images.githubusercontent.com/100567791/203308325-4ac14d26-b1fa-4f3a-9673-6c645f6a5795.png">

위와 같은 방법으로 M명의 사람과 테스트를 진행할 것이며, 각각의 참가자와 N번 시행하여 진행할 계획이다. (M, N은 미확정)


## 장갑 부속 부품 3D 프린팅
- 2022.10.28

<img width="465" alt="3D_1" src="https://user-images.githubusercontent.com/100567791/203309344-8b92c0e9-1f5b-4272-b035-eb6442effb6f.png">

<img width="451" alt="3D_2" src="https://user-images.githubusercontent.com/100567791/203309357-5b081165-be76-4828-a807-2007cfc70a68.png">

<br/>

- 2022.11.04 - 3D 프린팅 완료

<img width="438" alt="3D_3" src="https://user-images.githubusercontent.com/100567791/203309432-ba85610e-1d23-480d-a87c-963936d6a024.png">


각 부속품, 가변저항과 글러브 조립 완료

<img width="424" alt="3D_4" src="https://user-images.githubusercontent.com/100567791/203309443-51a6f603-401f-45cb-8faa-3468443f53a4.png">


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
