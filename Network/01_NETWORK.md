- [네트워크란?](#네트워크란)
	- [네트워크 종류](#네트워크-종류)
	- [IEEE 표준 802](#ieee-표준-802)
	- [활용 예](#활용-예)
	- [네트워크 구성 요소](#네트워크-구성-요소)
		- [시스템](#시스템)
		- [인터페이스](#인터페이스)
		- [전송매체](#전송매체)
		- [표준화](#표준화)
		- [프로토콜](#프로토콜)
	


# 네트워크란?

Net + Work 의 합성어

![network](../img/Pasted%20image%2020221220062249.png)

통신 설비 기술을 이용하여 두대 이상의 컴퓨터가 연결된 통신 이용 형태, 체계, 통신망


<br>
<br>

## 네트워크 종류
-   PAN ( Personal Area Network ) : 가장 작은 규모의 네트워크
-   LAN ( Local Area Network ) : 근거리 영역 네트워크
-   MAN (Metropolitan Area Network) : 대도시 영역 네트워크
-   WAN (Wide Ares Network) : 광대역 네트워크
-   VAN (Value Added Network) : 부가가치 통신망 정보의 축적과 제공, 통신속도와 형식의 변화, 통신경로의 선택 등 여러 종류의 정보서비스가 부가된 통신망.
-   ISDN (Integrated Services Digital Network) : 종합정보 통신망(=BISDN) 전화, 팩스, 데이터 통신, 비디오텍스 등 통신관련 서비스를 종합하여 다루는 통합서비스 디지털 통신망. 디지털 전송방식과 광섬유 케이블 사용.

![network2](../img/Pasted%20image%2020221220062357.png)

---
<br>

## IEEE 표준 802

(Institute of Electrical and Electronics Engineers:국제 전기 전자 공학회)
![[Pasted image 20221220062314.png]]

1980년 2월 창설 IEEE 802위원회라는 곳에서 표준안을 정해서 발표
802는 브릿지 통신규격 802 뒤에 숫자가 붙음으로써 프레임 규격으로 구분되어 집니다.

- EEE 802.1  -> 상위 계층 인터페이스 및 MAC 브릿지  
- IEEE 802.2  -> LLC(Logic Link Control)  
- ### IEEE 802.3  -> 이더넷(CSMA/CD)에 관한 규격
	-   IEEE 802.3  -> 10Base-X
	-   IEEE 802.3u  -> 100Base-X
	-   IEEE 802.3z  -> 1000Base-X
	-   IEEE 802.3ab  -> 1000Base-T
	-   IEEE 802.3ac -> 최고 867Mbps(5G)
	-   IEEE 802.3ae  -> 10Gigabit
	-   IEEE 802.3ad  -> Link Aggregation
- IEEE 802.4  -> Token Bus  
- IEEE 802.5  -> Token Ring  
- IEEE 802.6  -> 도시형네트워크(MAN)를 정의한 규격  
- IEEE 802.9  -> IS LAN  
- IEEE 802.10  -> 네트워크 본안의 규격제정에 관계되어 있음  
- ### IEEE 802.11  -> 무선 LAN(CSMA/CA)
	-   IEEE 802.11a  -> 5GHz 대역의 **OFDM 기술**을 사용해 54Mbps의 전송을 지원한다.
	-   IEEE 802.11ah -> '**와이파이 헤일로**(Wi-Fi HaLow)'
	-   IEEE 802.11b  -> **CSMA/CA 기술을** 사용하여 최대 11Mbps의 전송을 지원한다.
	-   IEEE 802.11g  -> 2.4GHz 대역에서 54Mbps의 전송을 지원한다.
	-   IEEE 802.11n  -> 여러 안테나를 사용하는 **다중입력/다중출력(MIMO)** 기술과 대역폭 손실을 최소화하여 상용화된 전송 규격으로 2.4GHz와 5GHz를 모두 사용한다.
- IEEE 802.12  -> 디멘드, 프라이빗(100VG-AnyLAN)  
- IEEE 802.14  -> Cable Modem  
- IEEE 802.15.1  -> 블루투스**  
- IEEE 802.15.4  -> ZigBee**  
- IEEE 802.16  -> Wibro(와이브로) & WiMAX

---
<br>


## 활용 예

주변장치 공유

![network3](../img/Pasted%20image%2020221220062550.png)

능률적인 통신

![network4](../img/Pasted%20image%2020221220062708.png)

손쉬운 백업

![network5](../img/Pasted%20image%2020221220062735.png)

등의 장점이 있다

---
<br>

## 네트워크 구성 요소

### 시스템
- 내부 규칙에 따라 능동적으로 동작하는 대상
- ex) 컴퓨터, 자동차, 커피 자판기, 마이크로 프로세서, 운영체제, 프로세스
	-    노드 : 인터넷에 연결된 시스템을 가장 일반화한 용어
	-   호스트 : 일반적으로 컴퓨팅 기능이 있는 시스템을 의미
	-   클라이언트 : 서비스를 이용하는 시스템
	-   서버 : 서비스를 주고 받는 호스트들의 관계에서 서비스를 제공하는 시스템
	- ![network6](../img/Pasted%20image%2020221220063302.png)


### 인터페이스
- 시스템과 시스템을 연결하기 위한 표준화된 접근 방법
- ex) RS-232C(serial), USB 등

### 전송매체
- 시스템끼리 정해진 인터페이스를 연동해 데이터를 전달하기 위한 전송 수단

### 표준화
- 노드 사이의 상호 연동성을 확보하기 위하여 제조업자, 판매업자, 정부기관, 그 밖의 서비스 제공자들이 약속된 규약으로 데이터 통신과 네트워크, 그리고 관련된 기술 및 프로세서간의 상호 운영에 있어서 호환성 유지 목적  
	표준화는 상호연동성을 보장하기 위한 제조업자나 판매업자, 정부기관 등의 활동을 말함
- ex) a4용지, 랜선등의 cable 등 

### 프로토콜
- 프로토콜은 네트워크 객체들간의 규격, 순서 등을 정의한 통신 규약
![network7](../img/Pasted%20image%2020221220063835.png)

<br>
<br>

다음 ->  [02. 프로토콜이란](02_Protocol.md)