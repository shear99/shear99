# 안녕하세요, 권병수입니다.

C++와 Python을 주로 사용하며, 임베디드 시스템과 컴퓨터 비전에 관심이 있습니다.
Raspberry Pi 기반 안내 화면과 차량 출입 시스템을 개발·운영하고 있습니다.

## Projects

### [PoseNavigator](https://github.com/shear99/PoseNavigator)
관절 추정과 그래프 신경망을 활용한 인물 촬영 포즈 가이드 프로젝트입니다.
관절 좌표를 그래프 특징으로 구성하고, 모델 출력과 현재 포즈의 차이를 화면에 표시했습니다.

`Python` `Pose Estimation` `GAT`

### [VEDA — VisionCraft 스마트 팩토리](https://github.com/VisionCraft2025)
임베디드 소프트웨어 교육 과정에서 진행한 팀 프로젝트입니다.
카메라 기반 분류, MQTT 장치 통신, Qt 모니터링 화면을 연결한 스마트 팩토리 시스템을 다뤘습니다.

`C++` `Qt` `MQTT` `OpenCV`

### [스마트 디지털 사이니지](https://github.com/shear99/smart-signage)
Python 서버에서 배포한 영상·자막·일정을 Raspberry Pi와 동기화하고, C++/Qt 화면에 표시하는 시스템입니다.
콘텐츠 다운로드와 화면 표시를 분리하고, 새 콘텐츠의 검증이 끝난 뒤 화면을 전환하도록 구성했습니다.

`C++` `Qt/QML` `Python` `WebSocket` `Raspberry Pi`

### [주차 차단기·번호판 인식 시스템](https://github.com/shear99/parking-gate-system)
카메라 영상에서 번호판을 인식하고, Pi의 허용 판단을 MQTT와 A6 보드를 통해 기존 차단기 제어기에 전달하는 시스템입니다.
장치 제어와 번호판 인식 모델의 학습·평가 과정을 함께 정리합니다.

`C++` `Python` `MQTT` `RS232` `Computer Vision`

## Tech Stack

| 분야 | 주로 사용한 기술 |
| --- | --- |
| Languages | C++, Python |
| GUI | Qt, QML |
| Embedded & Communication | Raspberry Pi, ESP32/KC868-A6, MQTT, RS232 |
| Vision | OpenCV, 번호판 인식, 관절 추정 |
| Environment | Linux, CMake |
