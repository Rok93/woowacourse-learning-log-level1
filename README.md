# 로또미션 학습로그 

## [OOP] 원시값 포장 - 3
### 내용
- int lottoNumber를 LottoNumber 래퍼 클래스로 포장
- int money를 Money 래퍼 클래스로 포장 

## [OOP] 일급 컬렉션 사용 - 4
### 내용
- List<Lotto> 를 Lottos 으로 대체 
- List<LottoNumber> 를 LottoNumbers으로 대체 
- Map<Rank, Long> lottoResults 를 LottoResults으로 대체   
## 링크
- [일급 컬렉션(First Class Collection](https://rok93.tistory.com/entry/%EC%9D%BC%EA%B8%89-%EC%BB%AC%EB%A0%89%EC%85%98First-Class-Collection%EC%9D%98-%EC%86%8C%EA%B0%9C-%EC%8D%A8%EC%95%BC%ED%95%A0-%EC%9D%B4%EC%9C%A0) <br> 

## [JDK] Enum - 2
### 내용
- Enum의 내부 구현에는 ``int ordinary`` 라는 순서를 저장하는 변수가 있다.
- 따라서 Collections.sort()와 같이 정렬을 하는 메서드의 적용이 가능하다. (Stream의 sort 또한 마찬가지로 사용 가능하다)
- ...
### 링크
- [Java Enum 활용기 - 우아한 형제들 기술블로그](https://woowabros.github.io/tools/2017/07/10/java-enum-uses.html)

## [TDD] TDD 3단계에 따라 개발 - 1
### 내용 
- 일부 코드를 제외하고 거의 대부분의 코드를 TDD Cycle로 구현함 

# 블랙잭미션 학습로그 
# 로키 학습로그 - 블랙잭
## [객체 지향] - 추상 클래스 vs 인터페이스 4
### 내용
* 공통적인 요소들을 묶어서 interface 로 구현을 할 것인지, 추상 클래스로 상속을 받을 것인지 고민
* ``Participant`` interface를 활용하여 ``Player``와 ``Dealer``를 구현 

## [디자인 패턴] - 전략패턴 2 
### 내용 
* ACE 카드를 상황에 따라 1점 or 11점 중 유리한 방향으로 점수를 세는 전략 생성 
* 추후 전략을 코드의 변경 없이 새로운 전략을 구현하여 주입함으로써, 손쉽게 수정할 수 있음 

## [디자인 패턴] - MVC 패턴 4 
### 내용 
\- AS IS
* view에서 입력을 받아 바로 model로 맵핑까지 진행하여 반환함.

\- TO BE
* view에서는 model과의 의존성을 가지면 안된다. 따라서 InputView에서 입력을 받아 원시값을 반환하도록 하였음 
* controller에서 view에서 받아온 원시값을 model로 매핑하는 작업을 추가로 구현함

# 체스미션 학습로그

## [디자인패턴] 상태패턴 - 3
### 내용
- 체스게임의 현재 상태를 상태패턴으로 구현하여  
### 참고 내용 
- 개발자가 반드시 정복해야 할 객체 지향과 디자인 패턴 (상태 패턴 부분) 

##  [디자인패턴] 커맨드패턴 - 2
### 내용 
- 체스게임을 조작하기 위한 커맨드를 커맨드 패턴으로 변경하여 조작 

### 참고 링크 
* [커맨드 패턴 (Command Pattern) - 기계인간(Jonn Grip)](https://johngrib.github.io/wiki/command-pattern/) 

## [객체지향] DTO - 2 
- Controller와 View의 정보 전달시 model을 직접 전달하거나 받는 형태가 아닌, DTO 객체로 전달 

