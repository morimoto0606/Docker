# Dockder file for Cpp Library
## Content
- Ubuntu 
- vim 
- build-essential (c++: g++, gcc, make etc.)
- cmake 
- libgtest-dev(gtest) 
- libboost-all-dev(boost) 
- libeigen3-dev(Eigen)

## 環境設定
### 各自の端末でコンテナをビルドする場合
    - docker-compose build
    - docker-compose run dev bash
### DockerHubからイメージを取ってくる場合
    - docker create -it -v {mount host direcotry path (absolute)}:{path in container} {image name}
        e.g. docker create -it -v /home/morimoto/Public/GitHub/QuantsCpp/GeometricSde:/dev/GeometricSde morimoto0606/geometricsde_dev
    - start {process id}