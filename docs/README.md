## 기능 구현 사항

**1. 서로 다른 3자리 수 랜덤하게 생성**

- [x] 1-9 사이의 값을 가지는 3자리의 수를 생성한다.
- [x] 3자리 수는 서로 다른 수로 구성되어야 한다.

**2. 사용자(player)는 3자리의 수를 입력한다.**

- [x] 사용자는 3자리의 수를 입력한다.
- [x] 공백이 포함되어 있다면 공백을 제거한다.
- [x] 자리의 수가 3보다 크거나 작은 경우 예외가 발생한다.
- [x] 자리의 수 중 중복되는 수가 있다면 예외가 발생한다.
- [x] 각 자리의 수는 1부터 9까지의 범위를 가진다. 그렇지 않다면 예외가 발생한다.

**3. 컴퓨터(NumbersComparator)는 사용자가 입력한 수를 확인하여 결과를 반환한다**

- [x] 컴퓨터는 사용자가 입력한 3자리 수와 랜덤하게 생성한 3자리 수를 비교하여 결과값(볼 개수, 스트라이크 개수)을 반환한다.

**4. 받은 결과값을 출력한다.**

- [x] 콘솔에서 컴퓨터가 연산하여 반환한 결과값을 출력한다.

**5. 결과값이 3스트라이크라면 3자리 수 입력을 종료한다.**

- [x] 게임 종료메시지와 게임을 계속 해서 진행할 것인지 입력 받는 안내 메시지를 출력한다.

**6. 게임을 계속 진행하거나 종료한다.**

- [x] 사용자가 1을 입력한다면 게임을 새로 시작한다. 이때 randomNumber도 새로 생성한다.
- [x] 사용자가 2를 입력한다면 게임을 종료한다. 
