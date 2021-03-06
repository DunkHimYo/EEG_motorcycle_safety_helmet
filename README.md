
| 영상 시청을 원할시 클릭 |
| ------ |
|[![waiting](https://github.com/DunkHimYo/motorcycle-safety-helmet/blob/main/img/main_img.png)](https://youtu.be/VJhJqzU6J08)|

# BCI 기술을 적용한 이륜차 안전 헬멧

- 매년 이륜차의 사고 발생률 점진적 증가
- 최근 배달 서비스 증가로 오토바이 운전자 사망사고가 늘어남
- 더 빨리 배달해야 하는 서비스 문화가 자리를 잡으면서 이들의 안전이 위협
- 피로감을 느껴 졸음 운전의 가능성 높음

| 사고 현황 |
| ------ |
|![waiting](https://github.com/DunkHimYo/motorcycle-safety-helmet/blob/main/img/accident_status.png)|


| 오토바이 CC 빈도 |
| ------ |
|![waiting](https://github.com/DunkHimYo/motorcycle-safety-helmet/blob/main/img/motorcycle_total.png)|

## 해결 방안

- BCI를 이용해 착용자의 뇌파를 입력 받음
- 흥분 상태를 판단하여 시동을 제어
- 운행 중 흥분, 집중력 상태와 속도를 통해서 상황에 맞는 음성 메시지 출력
- LED를 이용하여 주변 차량들에게 위험성을 알림

## 데이터 수집
| 수집 방법 |
| ------ |
|![waiting](https://github.com/DunkHimYo/motorcycle-safety-helmet/blob/main/img/explain.jpg)|

## 데이터 분석
- 집중력이 떨어질때 Theta와 Alpha 부분에 튀는 것을 확인 할 수 있음

| 분석 |
| ------ |
|![waiting](https://github.com/DunkHimYo/motorcycle-safety-helmet/blob/main/img/state.jpg)|


## 모델 제작

| 분석 |
| ------ |
|![waiting](https://github.com/DunkHimYo/motorcycle-safety-helmet/blob/main/img/model.png)|

## 감정 인식
- Emotiv API를 이용하여 감정에 대한 값을 상대적으로 받아와 데이터 처리

| 감정 |
| ------ |
|![waiting](https://github.com/DunkHimYo/motorcycle-safety-helmet/blob/main/img/matrix.jpg)|


## 기대 효과

- 기본적으로 헬멧을 착용해야 하기 때문에 헬멧 착용율 증진
- 사용자의 부주의(과속, 음주, 졸음 등)로 인한 위험 상황 저하
- 사용자의 상황을 주변 차량들이 LED를 통해 시각적으로 확인하여 미연에 방지

