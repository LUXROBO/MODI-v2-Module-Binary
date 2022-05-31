# MODI+ Module Binary

## Module Firmware Version

### OS
| | |
|:---|:---|
| e103 | **v1.2.0** |
| e230 | **v1.2.0** |

### Bootloader
| | |
|:---|:---|
| e103 | v1.0.0 |
| e230 | v1.0.0 |

### Module
| | |
|:---|:---|
| Battery | **v1.0.4** |
| Button | v1.0.0 |
| Dial | v1.0.3 |
| Display | **v1.2.1** |
| Environment | v1.0.2 |
| Imu | **v1.1.2** |
| Joystick | v1.1.1 |
| Led | v1.0.0 |
| Motor | **v1.2.0** |
| Speaker | **v1.2.0** |
| Tof | v1.1.2 |
| Network | v1.1.2 |
| Network app | **v4.3.0** |
| Network ota | v1.0.0 |

## Feature

### Motor
1. 일시정지 기능 추가

### Speaker
1. Pause/Resume 기능 추가

### Network app
1. 일시정지 기능 추가

## Hotfix

### OS e230
1. 특정 모듈 만으로 연결 시 PNP 기능이 정상 동작 하지 않는 오류 수정

### Battery
1. 완충 후, usb 전원이 계속 연결되어 있으면 방전되는 오류 수정

### Display
1. 업데이트 시, 마지막으로 출력된 그림이 남아있는 오류 수정

### Speaker
1. 주파수를 0Hz로 설정 시, 소리가 출력되는 오류 수정

## Patch

### Imu
1. 가속도 범위를 ±4g에서 ±2g로 수정

### Motor
1. 위치 제어 성능 개선

### Speaker
1. 음악 실행 성능 개선