# TCP/IP 4 계층 구조
## 4계층 애플리케이션 계층(프로토콜: FTP, HTTP, SSH, SMTP, DNS)
    - 응용 프로그램이 사용되는 프로토콜 계층으로 실질적인 사용자들에게 제공하는 층이다.
## 3계층 전송계층(프로토콜: TCP, UDP 등)
    TCP(Transmission Control Protocol)?
    - 연결지향 커뮤니케이션 프로토콜로 IP(Internet Protocol)과 함께 사용한다.
    - 애플리케이션이나 서버에서 받은 데이터를 패킷(packet)으로 나눠 네트워크를 통해 목적지로 전송한다.
    - 각 패킷에 번호를 붙이기 때문에 이것을 재조립해 목적지에 전달한다. 
    - 패킷의 수신여부를 확인한다.
## 2계층 인터넷 계층(프로토콜: IP, ARP, ICMP 등)
    IP(Internet Protocol)?
    - 컴퓨터끼리 어떻게 패킷을 주고 받을 것인지에 관한 프로토콜이다.
    - TCP에서 나눠진 패킷들을 목적지로 전송한다.
## 1계층 네트워크 액세스 계층
    - 실질적으로 데이터를 전달하는 계층

## 참고
- [Transmission Control Protocol (TCP)](https://www.sdxcentral.com/resources/glossary/transmission-control-protocol-tcp/)
- [Internet Protocol (IP)](https://www.sdxcentral.com/resources/glossary/internet-protocol-ip/)
- [Transmission Control Protocol (TCP)](https://www.techtarget.com/searchnetworking/definition/TCP)
- [[Network] TCP/IP 와 TCP/IP 4계층이란?](https://wooono.tistory.com/507)
