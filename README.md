# javascript-lotto-precourse

## ❓무슨 프로그램인가요?

로또 번호를 발행하고 당첨 여부와 비교하여 수익률을 계산하는 프로그램입니다

## 🚀 주요 기능

- **로또 구입 금액 입력 및 유효성 검사**
- **구입 수량 결정 및 로또 번호 발행** : 각 로또에 대해 중복 없는 6개의 숫자 발행
- **로또 번호 오름차순 정렬**
- **로또번호 출력** : 각 로또 당첨 번호 출력
- **당첨 번호 입력** : 중복 없는 숫자 6개 선정
- **보너스 당첨 번호 입력** : 당첨 번호와 중복되지 않은 보너스 당첨번호 1개 선정
- **당첨 통계 계산** : 로또 번호와 당첨 번호가 몇 개가 일치하는지 계산
- **당첨 통계 출력** : 당첨 번호와 일치한 개수 출력
- **총 수익률 출력** : 구매한 금액 대비 수익률 출력

## ⚠️ 에러 처리

### 로또 구입 금액

- 입력한 로또 구입 금액이 숫자가 아닌 경우
- 입력한 로또 구입 금액이 음수인 경우
- 입력한 로또 구입 금액이 1,000원으로 나누어 떨어지지 않는 경우

### 당첨 번호 / 보너스 번호

- 입력한 로또 당첨 번호 및 보너스 번호 중 숫자가 아닌 문자가 있는 경우
- 입력한 로또 당첨 번호 중 중복인 숫자가 있는 경우
- 입력한 로또 당첨 번호 및 보너스 번호가 1~45 사이 숫자가 아닌 경우
- 입력한 로또 당첨 번호가 6개가 아닌 경우
- 입력한 보너스 번호가 로또 당첨번호에 이미 있는 번호인 경우

## 📁 파일 구조

## 📥 설치 및 실행 방법

1. 프로젝트 클론

```bash
git clone https://github.com/hanheel/javascript-lotto-7.git
```

2. 의존성 설치 : 필요한 라이브러리 설치

```bash
npm install
```

3. 프로그램 실행

```bash
npm run start
```
