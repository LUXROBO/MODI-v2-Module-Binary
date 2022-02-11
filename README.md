# MODI+ Module Binary

## Module Firmware Version
Module OS e103: **v1.1.0**

Module OS e230: **v1.0.2**

Bootloader e103: v1.0.0

Bootloader e230: v1.0.0

Battery: v1.0.0

Button: v1.0.0

Dial: **v1.0.2**

Display: **v1.1.2**

Environment: **v1.0.2**

Imu: v1.0.0

Joystick: v1.1.0

Led: v1.0.0

Motor: v1.0.1

Speaker: **v1.1.2**

Tof: **v1.1.1**

Network: **v1.1.1**

Network app: **v4.1.1**

Network ota: v1.0.0

## Feature

### OS e103
1. 긴급 모듈 정지 시, 상태 LED를 노란색으로 표시
2. Display 모듈의 상태 LED 표시 삭제

### Environment
1. 녹음 완료 시, 완료 메세지 전달 기능 추가

### Speaker
1. 음악 실행 시, 실시간으로 음량이 수정 가능하도록 변경

## Hotfix

### OS e103
1. PnP 동작 시, 첫 동작이 이상하게 동작되는 오류 수정

### OS e230
1. PnP 동작 시, 첫 동작이 이상하게 동작되는 오류 수정

### Dial
1. 원점에서 값이 0, 100이 반복되며 나타나는 오류 수정

### Display
1. 글자 출력 후, 변수가 출력되지 않는 오류 수정
2. 긴 글자 출력 시, 일부분이 출력되지 않는 오류 수정
3. -1 ~ 0 사이의 값을 변수로 출력 시, 값이 잘못 출력되는 오류 수정
4. 변수 출력 시, 출력한 변수 값이 지워지지 않는 오류 수정

### Environment
1. 녹음 시, 지정한 시간보다 오래 녹음하는 오류 수정
2. 조도 값의 최대가 100으로 나타나지 않는 오류 수정

### Speaker
1. 정지 명령어를 준 후, 소리가 출력되는 오류 수정
2. 음악 실행 시, 모듈이 정지하는 오류 수정

### Tof
1. 50cm 거리에서 가끔 100cm로 표시되는 오류 수정

### Network
1. 다른 모듈과 연결 시, 가끔 부트로더로 이동하는 오류 수정
2. 리소스 파일 전송 시, 모듈이 정지하는 오류 수정

### Network App
1. not 연산자가 조건문에서 쓰일 경우, 실행이 종료되는 오류 수정
2. Math 상수 추가
* M_PI (3.141592....)
* M_E (2.71828...)
* M_R2D (180.0/M_PI)
* M_D2R(M_PI/180.0) 