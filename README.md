# twitch-1080p
한국에서 VPN 없이 트위치 1080p 방송을 볼 수 있는 프로젝트

## 유의
본 프로젝트는 초기 버전 출시를 위해 개발 중인 단계입니다. 컨셉과 계획은 언제든 변경될 수 있습니다.

## 핵심 컨셉
- 원본 1080p 방송은 한국 이외의 지역에 구축된 서버를 통해 불러온다
- 원본 영상을 받아서 중계하는 핵심 노드도 마찬가지로 한국 이외의 지역에 구축되어있다
- 핵심 노드는 임의로 선택된 소수의 유저(시드 유저)와 WebRTC로 통신하며 원본 영상을 서빙한다
- 시드 유저는 피어 유저들과 WebRTC로 P2P 통신을 하여 1080p 원본 영상을 서빙한다
- 각 시드와 피어는 연결될 수 있는 최대 P2P 커넥션 수가 설정되어 있다
- 시드와 피어 간 커넥션 수가 최대에 도달한 이후부터는 피어끼리 원본 영상을 서빙한다

## 세부 구현 계획
TBD

## 개발 일정
TBD
