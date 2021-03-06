+++
	author = "Sung Ho Youn"
	date = "2021-08-10"
	title = "두번째언어로 파이썬 배우기 1"
	tags = ["Python", "Java", "Programming" ]
	categories = [ "Studying", ]
+++

파이썬은 보다 편하고 쉽게 코딩을 할 수 있게 발명된 프로그래밍 언어입니다. 하지만 만약 다른언어, 예를 들면, 자바나 C언어를 먼저 배웠다면 다소 생소하거나 이해가 잘 가지 않는 부분들이 있을겁니다. 이 포스팅은 그런부분들을 하나씩 정리하고 파이썬을 늦게 공부하게 된 개발자분들이 빠르게 파이썬에 적응하기 위해 만들어 졌습니다.

아무래도 파이썬에 가장 편하지만 다른 언어에서는 상상할 수 없는 것이 바로 타입선언이라고 생각됩니다. 자바를 공부하신 분들이라면, 타입을 선언하는게 얼마나 중요한지 알고 계실겁니다. 변수를 저장할 때 타입을 지정해주지 않으면 바로 에러가 뜨기 때문이죠. 하지만 파이썬에서는 변수에 타입을 정해주지 않습니다. 그 이유는 객체지향 언어로서, 모든 변수를 레퍼런스로 바인딩하기 때문입니다. 예를 들면 int a = 10; 이라는 문장을 a = 10 이라고 해주면, 10을 저장하고 있는 메모리 주소를 저장하고 있습니다.

이것때문에 많이 헷갈리셔할분들이 많습니다. 리스트에 저장을 할때도, 한가지 타입만을 저장하지 않고 모든 타입을 한 리스트에 저장가능합니다. 처음에는 생소하겠지만 사용하다보면 오히려 편하다고 느껴집니다. 편한만큼 코딩을 할 때 조심해야합니다. 리스트를 이터레이팅할 때, 타입을 착각해 잘 못 처리할 수 있으니, type() 클래스를 이용하여 확인하는거나 try except 코드( 자바의 try catch )를 사용하여 에러를 잡아내는 게 중요합니다. 하지만 자바나 C언어를 하신분들에게는 이렇게 확인코드를 넣는건 어찌보면 매우 당연하다고 할 수 있기에 크게 불편하지는 않을것 같습니다.

다음 포스팅은 함수에 대해 얘기해보겠습니다.
