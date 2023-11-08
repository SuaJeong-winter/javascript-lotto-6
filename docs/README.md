# 로또


## 기능 목록

1. **입력값-로또 구입 금액:**
   첫 번째 입력 값인 로또 구입 금액입니다
   구입 금액은 1000원 단위로 입력받습니다
   예외 처리 - 1000원으로 나누어 떨어지지 않는 경우 "[ERROR]구입 금액은 1000원 단위만 가능합니다" 출력

2. **입력값-당첨 번호 :**
   두번째 입력 값인 당첨 번호 입니다
   쉼표를 기준으로 중복되지 않는 자연수 6개를 입력받습니다
   @woowacourse/missoion-utils의 Random API를 사용하여 1~45 사이의 랜덤한 값을 받습니다
   예외처리 - 당첨번호의 길이가 6개가 아닐 경우 "[ERROR]발행되는 로또의 당첨 번호는 6개가 되어야 합니다 " 출력
   예외처리 - 당첨번호에 자연수가 아닌 다른 값이 들어온다면 "[ERROR]올바른 로또의 당첨 번호의 형태가 아닙니다" 출력

3. **입력값-보너스 번호:**
   세번째 입력 값인 보너스 번호입니다
   당첨 번호에 해당하지 않는 자연수 1개를 입력받습니다
   숫자의 범위는 두번째 입력값과 동일합니다 

4. **출력값-발행한 로또 수량 및 번호:**
    발행한 로또 수량 및 번호를 출력한다 
    로또 번호는 오름차순으로 정력하여 보여준다 

5. **출력값-당첨 내역을 출력한다 :**
    당첨이 되더라도 안되더라도 모든 경우를 다 출력은 해야 한다 

6. **출력값-수익률:**
    수익률은 소수점 둘째 자리에서 반올림한다 