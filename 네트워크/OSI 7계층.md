![image](https://user-images.githubusercontent.com/50320556/172038349-b9225d71-f665-4bed-a6e3-723c40a10cc0.png)  

### OSI 7계층
1) 응용계층(Application)  
- 사용자와 가장 밀접한 계층으로 응용 프로세스 간의 정보 교환을 담당한다.  
- 가상터미널, chrome, 전자우편  
-  HTTP, SMTP, FTP, Telent, DNS  
  
2) 표현계증(Presentation)  
- 데이터를 압축하거나 암.복호화작업을 담당한다.  
- UTF-8을 ASCII로 변환  
- MPEG, JPEG, MIDI  
  
3) 세션계층(Session)  
- 통신을 하기 위한 세션을 확립, 유지, 중단하는 작업을 담당한다.  
- TCP/IP 세션을 생성,삭제하고 사용자 동기화 및 오류복구 명령을 다룬다.  
- SSH, TLS, NetBIOS  
  
4) 전송계층(Transport) 
- 종단 간 효율적 데이터 전송을 위해 오류검출 및 복구, 흐름제어 등을 수행한다.  
- 방화벽 및 프록시 서버  
- 데이터 단위는 세그먼트(Segment)이다.  
- TCP, UDP, OSPF  
  
5) 네크워크계층(Network)  
- 라우팅, 흐름제어, 세그멘테이션, 오류제어, 인터네트워킹 기능을 수행한다.    
- 데이터 단위는 패킷(Packet)이다.  
- 장비는 라우터, L3가 있다.  
- IP, ICMP, ARP  
  
6) 데이터링크계층(Data-Link)  
- 물리적인 연결을 통해 데이터를 전송하는 수단을 제공한다.  
- MAC 주소를 식별하는데 사용할 수 있는 주소지정체계를 제공하는 것이 주목적이다.  
- 데이터 단위는 프레임(Frame)이다.  
- 장비는 브리지, 스위치가 있다.  
- Ethernet, MAC  
  
7) 물리계층(Physical)  
- 실제 데이터를 전송하는 계층이다.  
- 장비는 케이블, 리피터, 허브가 있다.  

<br>

### TCP/IP 프로토콜
1) 응용계층(Application)  
- OSI 7계층의 응용, 표현, 세션계층이다.  
- TCP/UDP 기반의 응용 프로그램을 구현할 때 사용한다.  
- FTP, HTTP, SSH  

2) 전송계층(Transport)  
- OSI 7계층의 전송 계층이다.  
- 통신 노드 간의 연결을 제어하고, 신뢰성 있는 데이터 전송을 담당한다.  
- TCP, UDP  
  
3) 인터넷계층(Internet)  
- OSI 7계층의 네트워크 계층이다.  
- 통신 노드 간의 IP패킷을 전송하는 기능과 라우팅 기능을 담당한다.  
- IP, ARP, RARP  

4) 네트워크 엑세스 계층  
- OSI 7계층의 데이터링크, 물리계층이다.  
- 물리적인 주소로 MAC을 사용한다.  
- LAN, 패킷망 등에 사용된다.  

<br>
