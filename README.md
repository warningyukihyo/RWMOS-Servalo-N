# RWMOS Servalo-N (2017)

## 구성도

### 제어 컴퓨터

- Arduino Nano (ATmega328P 8MHz)

### 탑재 센서

- Bosch Sensortec BME280: 기온/기압/습도
- Sharp GP2Y1010AU0F: PM10
- AMS TLS2561: 일사량
- Vishay VEML6070: UV
- Honeywell HMC5883L: 지자기

## 설치 장소

강원도 홍천군 홍천읍

## 현재 상태

미션 종료, 필드에서 잘 뜯어서 회수해왔고 집에서 쉬고있음

## 일지

- 2017년 12월 19일 09시 48분: 작동 시작, 첫 번째 측정 데이터 수신 성공
  - 원격진단 상태 정상, 기온/기압/습도/PM10/자외선 센서 정상
  - 지자기 센서: 태양전지 충전 회로간의 간섭이 확인되어 흐르는 동안에는 잘못된 값을 측정함, 따라서 일몰~일출 사이 데이터만 활용하기로 함
  - 일사량 센서: 가 강한 일사량을 제대로 측정하지 못하는 것으로 생각됨, 지켜보기로 함
- 2018년 06월 25일 00시 00분: 명확한 배터리 출력 저하가 관찰됨
  - 1단계 저전압 모드로 전환되면서 블로워 팬 사용 중지, 미세먼지 관측 중단
- 2018년 06월 29일 13시 16분: 기온 측정을 위한 온도 센서 고장남
  - 온도 보상이 필요한 습도와 기압도 측정 불가
- 2018년 08월 15일 12시 41분: 무선 통신 두절
- 2018년 08월 25일 11시 57분: 다시 살아남, 심각한 배터리 출력 저하가 관찰됨
  - 2단계 저전압 모드로 전환
- 2018년 09월 02일 18시 04분: 무선 통신 두절
- 2018년 09월 04일 11시 57분: 다시 살아남, 무선 통신 상태가 좋지 않음
- 2018년 09월 10일 17시 42분: 더 이상 유의미한 과학적 데이터를 제공하지 못한다고 판단되어 미션 종료


## 링크

- 종합 상태 확인: http://yukihyo.me/lab/project/rwmos/servalo-n/monitoring/
- 기상 관측 기록: http://yukihyo.me/lab/project/rwmos/servalo-n/monitoring/weather-conditions/
- 지자기 강도 관측 기록: http://yukihyo.me/lab/project/rwmos/servalo-n/monitoring/geomagnetic-field-strength/
- 원격진단 정보: http://yukihyo.me/lab/project/rwmos/servalo-n/monitoring/telemetry/
