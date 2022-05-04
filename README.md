# MODI+ Module Binary

## Module Firmware Version

### OS
| | |
|:---|:---|
| e103 | **v1.1.2** |
| e230 | **v1.1.2** |

### Bootloader
| | |
|:---|:---|
| e103 | v1.0.0 |
| e230 | v1.0.0 |

### Module
| | |
|:---|:---|
| Battery | **v1.0.3** |
| Button | v1.0.0 |
| Dial | v1.0.3 |
| Display | **v1.2.0** |
| Environment | v1.0.2 |
| Imu | **v1.1.1** |
| Joystick | v1.1.1 |
| Led | v1.0.0 |
| Motor | **v1.1.0** |
| Speaker | v1.1.2 |
| Tof | v1.1.2 |
| Network | v1.1.2 |
| Network app | **v4.2.1** |
| Network ota | v1.0.0 |

## Feature

### Battery
1. 배터리 잔량을 5 단위로 출력

### Display
1. PnP 모드 시, 모듈 데이터 범위 변경

### Imu
1. Vibration 범위 수정
* -100 ~ 100 -> 0 ~ 100

## Hotfix

### OS e103
1. Pause 동작 시, 모듈이 동작하는 오류 수정

### OS e230
1. Pause 동작 시, 모듈이 동작하는 오류 수정

### Motor
1. Pause 동작 시, 모듈이 동작하는 오류 수정

### Display
1. 37자 이상 한글 출력 시, h!가 출력 되는 오류 변경
2. IMU 모듈과 PnP 시, 특정 값에서 ']' 문자가 출력 되는 오류 수정
3. 이미지 출력 - 문자 출력 - 변수 출력을 순차적으로 실행하면, 이전 이미지가 남아있는 오류 수정
4. 99,999.99의 값을 가지는 변수 출력 시, ']' 문자가 출력 되는 오류 수정
5. PnP 처음 값이 이상하게 출력되는 오류 수정

## Patch

### Network app
1. 사용자 코드 업로드 속도 개선