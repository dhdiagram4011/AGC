# AGC
AGC 경진대회 플렛폼 개발

[ System Requirement ]
- OS : Ubuntu 18.04 ~
- GPU : Nvidia GeForce 470 GTX or AMD Radeon 6870 HD Series and or higher
- CPU : Quad-core Intel or AMD Processor, 2.5 GHz or faster
- RAM : 8GB 이상 (16GB 이상 추천)
- Disk : 500GB 이상
- S/W :  Carla 0.9.13(Scenario Runner, LeaderBoard), Autoware.AI, Python2, Python3, docker, anaconda)


[ System Architecture ]

![제목_없는_클리핑_050223_012930_PM](https://user-images.githubusercontent.com/50344658/235579475-62b6adb2-a349-44e0-8ad0-2d74590ff1df.jpg)



[ Installation ]
- 환경 : Ubuntu 18.04 에서 환경구성(window 환경은 지원하지 않음)


1. NVIDIA-Driver 설치
#ubuntu-drivers install


2. Carla 시뮬레이터 설치
- 다운로드 페이지 : https://github.com/carla-simulator/carla/releases/tag/0.9.14/
- wget https://carla-releases.s3.eu-west-3.amazonaws.com/Linux/CARLA_0.9.14.tar.gz


3. Scenario Runner 다운로드 및 설치
- git clone https://github.com/carla-simulator/scenario_runner.git


4. LeaderBoard 다운로드 및 설치
- git clone -b leaderboard-2.0 --single-branch https://github.com/carla-simulator/leaderboard.git


5. Docker 설치
- sudo apt-get install docker*
- sudo systemctl enable docker
- sudo systemctl start docker
- sudo systemctl status docker


6. Carla-autoware Bridge Container Image 다운로드


7. 환경 구성 스크립트 실행
- OperaSIM-AGC-VER.sh
