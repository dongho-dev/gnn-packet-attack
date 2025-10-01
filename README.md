# gnn-packet-attack

## Problem Description

파일 packets.csv는 어느 wifi 네트워크에서 수집된 패킷들의 정보이다.
 - src : 패킷 송신 주소
 - dst : 패킷 수신 주소
 - packet_size, protocol, encryption, packet_delay : 패킷 정보
 - attack label : 공격 종류

test dataset size를 20%로 두고, src의 공격 종류를 예측하는 프로그램을 작성하고, 최대한 정확도를 높이시오.

### 요구사항1.
test dataset size를 20%로 두고, src 의 공격 종류를 예측하는 프로그램을 작성하고, 최대한 정확도를 높이시오.

### 요구사항2.
test 파일을 입력으로 받아서 학습한대로 src의 공격종류를 출력하시오.

### 요구사항 3.
5분내외 프로젝트 발표준비


### 제출물
10/13 수업전에 출력해서 제출

다음 순서로 깔끔하고 보기 쉽게 출력하여서 제출하시오.

1. 정확도 출력 화면
2. loss function 그래프 화면
3. test 파일 출력 화면
4. 소스코드 전체
5. 본인 프로젝트 특징/배운점/의견/느낀점/불만/제안 등
