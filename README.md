# wanted_cleancode


### Q1. 내가 생각하는 클린 코드란?
- 변수명: 어떤 목적을 나타내는 것인지 쉽게 파악 가능해야 함.
- 함수: 1개의 함수에는 1개의 목적만
- 전체 코드: 다른 사람이 보더라도 이해할 수 있도록
- 패턴: 동일한 패턴으로 이해하기 쉽게


### Q2. 내가 생각하는 (프론트엔드에서의) 클린 코드란?
팀원들과 합의한 규칙과 내용을 우선으로 작성한 코드
다른 팀원들이 리뷰할 때 쉽게 이해할 수 있는 코드

### Q3. 내가 클린코드보다 중요하게 생각하는 것은?
구현 완성도

### Q4. 다음 중 선호하는 방식과 그 이유는?

**1.Tab vs Space**
Tab: 같은 결과를 위해 4배의 클릭을 하는 것을 매우 비효율적이다

**2. 세미콜론 O vs 세미콜론 X**
세미콜론O: 여기가 끝인 줄 알려주는게 좋다.

**3. count++; vs count += 1; vs count = count + 1;**
count +=1;: +2 등 다른 경우도 있을테니, 동일한 표기 규칙을 위해.

**4. if (isLogin) {} vs if (isLogin === true) **
if (isLogin): 변수명을 잘 정했다면 굳이 true를 적지 않아도 직관적으로 이해할 수 있다.

**5. isLogin && <HelloWanted /> vs isLogin ? <HelloWanted /> : <></> vs isLogin ? <HelloWanted /> : null vs isLogin ? <HelloWanted /> : undfined**
isLogin && <HelloWanted />: 같은 결과라면 짧고 명확하게.
