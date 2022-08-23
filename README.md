# 🔢 ⚾️ 숫자야구 프로젝트 저장소

> 프로젝트 기간: 2022.02.08 ~ 2022.02.11<br>
> 팀원: [Cathy](https://github.com/cathy171), [Taeangle](https://github.com/Taeangel) 리뷰어: [Yeha](https://github.com/ye-ha)

## 🔍 프로젝트 소개
### "🏏야구... 좋아하세요? 근데 이제 숫자를 곁들인...🔢"
- 사용자의 `Input`을 받을 수 있도록 `Command Line Tools`를 이용하여 프로젝트를 진행하였습니다.
- 컴퓨터는 1~9까지 중복되지 않은 임의의 수 3개를 생성합니다.
- 사용자는 9번의 기회안에 컴퓨터의 임의의 수를 맞추어야 합니다.
- 사용자는 중복없이 3개의 정수를 입력합니다.
- 사용자가 입력한 수와 컴퓨터가 생성한 수가 일치하고 위치까지 일치한다면 스트라이크입니다.
- 사용자가 입력한 수와 컴퓨터가 생성한 수가 일치하지만 위치가 다르다면 볼입니다. 
- 9번의 기회안에 사용자가 컴퓨터의 수를 맞추지 못하면 패배합니다.
- 사용자가 3스트라이크를 만들면 승리합니다.

## 📺 프로젝트 실행화면
- `ex) 컴퓨터 임의의 수: [4, 1, 5]`

<img src="https://user-images.githubusercontent.com/74251593/185851277-bb63a31d-1a8d-43c7-bbf1-b2f52c2b219b.png" width="90%">

## 📈 Flow Chart
<img src="https://user-images.githubusercontent.com/74251593/153222342-1f543a07-6e46-459f-b37b-7f7fa0a6f5bc.png">

## 🗝 키워드
- readLine()
- Set
- Optional Binding
    - if let
    - guard let
- Multi-line Strings
- split()

## [[STEP 1]](https://github.com/yagom-academy/ios-number-baseball/pull/82)
### 고민했던 점!
- `while loop`에서 빠져나오는 경우 `break`를 사용할지 `return`를 사용할지 고민하였습니다.
- `random`이 필요한 부분이 많아서 네이밍때문에 고민하였습니다.
- `startGame`함수에서 `while`문을 좀더 나누고 싶었는데 좋은 방도가 떠오르지 않았습니다.
- 어쩌다 보니 커밋순서를 잘 지키지 못했는데 죄송합니다. 다음부턴 이런일 없도록 하겠습니다.

## [[STEP 2]](https://github.com/yagom-academy/ios-number-baseball/pull/92)
### 고민했던 점!!
- 네이밍이 많이 이상합니다.
- `return`에 빈 문자열("")과 `return`에 빈 array([])를 생성하는 것 말고 다른 방법이 있는지 궁금합니다.
