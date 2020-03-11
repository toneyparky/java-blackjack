# java-blackjack
블랙잭 게임 미션 저장소

## 우아한테크코스 코드리뷰
* [온라인 코드 리뷰 과정](https://github.com/woowacourse/woowacourse-docs/blob/master/maincourse/README.md)


- [ ]  플레이어의 이름을 입력 받는다.
    - [ ]  문자열 처리
    - [ ]  참여인원 제한
    - [ ]  플레이어 생성
- [ ]  게임 시작시 카드 2장을 딜러와 플레이어에게 나누어 주어야 한다.
    - [ ]  Deck에서 2장을 pop해서 준다. (2장 pop하는 메서드도 가능)
    - [ ]  Deck을 만들어야 한다.
- [ ]  딜러는 1장, 플레이어는 2장의 카드를 공개한다.
    - [ ]  처음에 블랙잭일시 플레이어와 딜러의 패에 따라 경기 처리
- [ ]  플레이어가 카드를 더 받을수 있는지 검사 해야한다.
    - [ ]  ACE는 1 또는 11로 계산할 수 있다.
    - [ ]  K,Q,J는 10으로 계산한다.
- [ ]  플레이어가 카드를 더 받고 싶어하는지 검사 해야한다.
- [ ]  받을수 있고, 받고자 한다면 카드를 나누어준다.
- [ ]  플레이어가 카드를 받으면 카드의 상태를 출력한다.
- [ ]  플레이어 페이즈가 끝나면 딜러가 카드를 받는다.
    - [ ]  딜러가 16이하의 점수를 갖고 있으면 넘을때 까지 카드를 받는다.
- [ ]  카드 결과를 출력한다.
- [ ]  승패 결과를 출력한다.
    - [ ]  딜러가 블랙잭이면 블랙잭을 가진 사람 이외의 플레이어는 전부 패배한다. (둘다 블랙잭이면 무승부)
    - [ ]  둘다 버스트면 딜러가 이긴다.
    - [ ]  처음 2장으로 21이 만들어지면 블랙잭이다.
    - [ ]  버스트면 0점으로 간주한다.