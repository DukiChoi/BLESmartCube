[![License: Personal Use Only](https://img.shields.io/badge/License-Personal--Use--Only-red.svg)](https://github.com/DukiChoi/BLESmartCube/blob/main/LICENSE)
[![Contact: Email Author](https://img.shields.io/badge/Contact-Email%20Author-blue.svg)](mailto:cbcc12345@hanyang.ac.kr)


# BLESmartCube
<p align="left">
  <img src="https://github.com/user-attachments/assets/d34f545b-8ebe-4e57-8919-aebf579c034e" width="400" height="400" alt="icon"/>
</p>

- 한양대 BPNE 연구실
- IMU센서 + 압력센서 BLE 스마트 큐브 제작  



## 큐브 연동 앱
<img width="300" height="480" alt="1000001843" src="https://github.com/user-attachments/assets/e729cfbc-b3f0-43c0-b56c-1cf287fe6442" />
<img width="300" height="480" alt="1000001844" src="https://github.com/user-attachments/assets/457600e4-65f3-44fa-9fc4-82ad01d4147b" />
<img width="300" height="480" alt="1000001845" src="https://github.com/user-attachments/assets/4649597d-ec9a-42d9-b8cb-ae1d005569d7" />

- 가속도 기반 상태 분류 및 시각 피드백: 3축 가속도 벡터의 크기($|Acc|$)를 실시간 연산하여 기기 상태를 식별하고, 결과에 따른 상태 인지용 시각 피드백(LED) 시스템
- 사용자 정의 캘리브레이션 인터페이스: 하드웨어 인터럽트(Button)를 활용한 Calibration Mode 진입/탈출 기능 및 사용자 편의성을 고려한 UI 구현
- 파라미터 지속성 확보: 캘리브레이션 결과값을 비휘발성 메모리(Flash)에 자동 저장 및 로드 기능
- 클라우드 기반 데이터 수집: Google Drive API를 연동하여 실험 중 발생하는 센싱 데이터를 실시간으로 클라우드에 전송(Wifi) 및 자동 저장하는 데이터 파이프라인 구축

## 큐브 사진
![shiny cube](https://github.com/user-attachments/assets/75951c20-c7cc-4451-b9e2-83fd1ddf7854)
<img width="450" height="600" alt="KakaoTalk_20260330_212451191_03" src="https://github.com/user-attachments/assets/20d38853-cece-4732-96f7-873980cc9828" />

- 터치 센서(Custom FSR sensor) + LED 센서를 장착하여 터치 시에 불빛이 나는 상호작용 기능
- IMU 센서(BNO055)와 BLE(MCU:NRF52832)를 통한 데이터(가속도,자세,압력) 수집 기능

## 실험 사진
<img width="600" height="450" alt="image" src="https://github.com/user-attachments/assets/22f70058-534f-4f6a-8bae-66d91b25da83" />

## 📥 다운로드

최신 스마트 큐브 앱은 아래 릴리스 페이지에서 다운로드할 수 있습니다.  

- [**Download page**](https://github.com/DukiChoi/BLESmartCube/releases)

