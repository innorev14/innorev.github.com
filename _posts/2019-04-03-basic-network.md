>ifconfig
mac 주소 확인

Network -> mac address를 다룸
mac address는 근거리인 lan안에서 식별하기 위해 존재
port : 소켓에 부여된 일련번호
process안에 soket이 있음
-> soket

ETHernet protocal : LAN 영역을 책임진다
destination MAC Adderess :  내 라우터(ex iptime)의 MAC주소

MTU : 한번에 최대로 보낼 수 있는 데이터 양 1500 byte
어플리케이션단에서 최대는 1350정도

>traceroute URL 
: 몇 개의 라우터를 거치는지 (*는 비공개)

ARP : mac 주소를 ip 주소로 바꾸는 역할
RARP : ip 주소를 mac 주소호 바꾸는 역할

arp -a
ifconfig
ping <ip주소>
MAC Address가 갱신된다

ip
TTL 중요 -> 라우터를 지나면서 패킷을 버림 5 -> 4-> 3-> 2-> 1-> 0
icmp_seg 따로 공부

__.__.__.__
하나당 1Byte * 4 = 4Byte
Network 주소는 라우터 주소 (lan을 찾는 주소라고 생각 하면 됨)
host주소는 lan에 속해있는 주소(컴퓨터 주소라 생각하면됨)

일반적으로
255 broadcast
0은 자신


192.168.100.18/26
255.255.255.0
: 서브넷 없이 표현할때 요즘에는 이렇게 표현(/ + 1의 갯수)

DHCP
Dynamic Host Configuration Protocol

>whois ip주소

linux에서는 소켓을 파일 취급한다
윈도우는 파일과 소켓이 다르게 취급
윈도우에에서는 handle이고 함
