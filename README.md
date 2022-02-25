# MODI+ Module Binary

## Module Firmware Version

### OS
| | |
|:---|:---|
| e103 | v1.1.0 |
| e230 | **v1.1.0** |

### Bootloader
| | |
|:---|:---|
| e103 | v1.0.0 |
| e230 | v1.0.0 |

### Module
| | |
|:---|:---|
| Battery | **v1.0.1** |
| Button | v1.0.0 |
| Dial | **v1.0.3** |
| Display | **v1.1.3** |
| Environment | v1.0.2 |
| Imu | v1.0.0 |
| Joystick | **v1.1.1** |
| Led | v1.0.0 |
| Motor | **v1.0.2** |
| Speaker | v1.1.2 |
| Tof | **v1.1.2** |
| Network | v1.1.1 |
| Network app | **v4.1.2** |
| Network ota | v1.0.0 |

## Hotfix

### Battery
1. 풀 충전 시, 100%로 표기 되지 않는 오류 수정

### Dial
1. 최대값을 넘어가는 오류 수정
2. 초기 속도 값이 잘못 출력되는 오류 수정
3. 속도 단위 변경

### Display
1. 무한한 값을 가지는 변수 출력 시, "INF" (Infinity) 출력
2. 숫자가 아닌 값을 가지는 변수 출력 시, "NaN" (Not a Number) 출력
3. 글자 출력 시, 줄 바꿈이 정상 작동하지 않는 오류 수정

### Joystick
1. 값 범위를 원으로 변경

### Motor
1. 초기 위치 값이 음수(-)로 측정 되어, 한 바퀴 회전하는 오류 수정
2. 위치 값을 빠르게 전송하면 정상 작동하지 않는 오류 수정

### Tof
1. 거리 값을 소수점까지 표현

### Network App
1. 모듈 Set 함수가 즉각적으로 반응하지 않는 오류 수정