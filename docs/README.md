
## Controller

View에서 입력받은 정보를 Model에 전달

Model에서 처리한 정보를 View에 전달


## View

### 입력

구입 금액을 입력받기

당첨 번호를 입력받기

보너스 번호를 입력받기

## 출력

입력 안내 메시지 출력하기

로또 수만큼 로또 번호 리스트 출력하기

당첨 통계 출력하기

수익률 출력하기


## Model

### LottoNum

구입 금액에 따라 로또 번호 리스트를 생성하는 기능

랜덤으로 숫자를 뽑는 기능

한 로또에서 이미 뽑힌 번호를 제외하는 기능

### WinChecker

번호 몇 개가 일치하는지 확인하는 기능

### RateCalculator

총 당첨금을 계산하는 기능

수익률을 계산하는 기능

## 예외 처리

### 구입 금액
구입 금액이 1000원으로 나누어 떨어지지 않을 때

구입 금액이 정수가 아닐 때

### 당첨 번호
당첨 번호를 6개 이상 입력했을 때

로또 번호 범위 밖의 당첨 번호를 입력했을 때

당첨 번호가 정수가 아닐 때

당첨 번호로 중복되는 번호를 입력했을 때

### 보너스 번호
당첨 번호와 중복되는 보너스 번호를 입력했을 때

로또 범위 밖의 보너스 번호를 입력했을 때

보너스 번호가 정수가 아닐 때

