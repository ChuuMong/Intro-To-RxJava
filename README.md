> *이 문서는 [Intro-to-Rxjava](https://github.com/Froussios/Intro-To-RxJava)를 Fork하여 번역한 문서입니다.*

# RxJava 소개

이 가이드는 리액티브 프로그래머가 [RxJava](https://github.com/ReactiveX/RxJava)를 통해 JVM용 리액티브 프로그래밍을 구현하는 것을 목표로 합니다. Rx.NET의 [IntroToRx](http://www.introtorx.com) 가이드를 기반으로 합니다.

이 가이드를 읽으려면 리액티브, 함수형 프로그래밍에 대한 경험이 필요 없습니다. 다만 자바에 익숙해야합니다.

[학습 시작](/Part 1 - Getting Started/1. Why Rx.md)

### 구조

이 가이드의 내용을 처음부터 끝까지 읽어야하며 평균적인 튜토리얼보다 양이 많지만 실제 책보다는 작습니다. Rx에 대한 기본부터 시작하고 후속으로 갈 수록 점점 더 진보된 기능과 개념을 소개합니다. 이 가이드의 섹션은 초보자가 아닌 사람이 다시 참조 할 수 있도록 자체 포함되고 점으로 구성됩니다.

이 가이드에서 사용된 예제는 2가지 형식의 [컴파일 가능한 자바 파일](/tests/java/itrx)로 제공됩니다:
* 표준 out으로 출력하는 예제(처음 읽는 사람에게 권장)
* [JUnit](http://junit.org/)으로 체크하는 예제.

독자들은 자신에게 적합한 스타일로 예제를 볼 수 있습니다.

