+++
	author = "Sung Ho Youn"
	date = "2021-08-24"
	title = "두번째언어로 파이썬 배우기 3"
	tags = ["Python", "Java", "Programming" ]
	categories = [ "Studying", ]
+++

다른 언어와 마찬가지로 파이썬 역시 반복문이 존재합니다. 흔히들 알고 있는, for문과 while문이 있습니다. while문은 크게 다르지 않지만, for 반복문은 여러방식으로 사용되기에 한번 글을 작성해보았습니다. 

기본적인 for문의 문법은 for [val] in [list]: 입니다. 자바의 for each 문과 상당히 비슷합니다. 용도도 비슷하지만, 내장 함수 몇개와 같이 사용하면 여러방식으로 사용이 가능합니다. 첫번째로는, for [val] in `range(n)`처럼 리스트대신 range라는 클래스를 사용함으로 쉽게 수를 읽을 수 있습니다. range(10) 이면 0~9까지를 읽을 수 있고, range에 추가 인자를 넣어 다르게 사용할 수 있습니다. 두번째로는 `enumerate()`라는 함수를 사용하는겁니다. 이 함수를 사용할때는 보통, for [idx],[val] in enumerate(): 식으로 사용합니다. 한번에 리스트의 값과 index 값을 동시에 얻을 수 있어, 매우 편리합니다. 마지막으로는, for [idx] in range(len([list])): 사용법입니다. len()은 리스트의 길이를 리턴하는 함수입니다. 리스트의 값과 index를 가져오기위해 사용하는 방법인데, enumerate()를 잘 사용하시지 않은 분들이 많이 사용하는 방식입니다.

for문은 이런식으로 iterate할때도 사용하기도 하지만, 리스트를 다시 정의 할때도 사용합니다. 
```
# 1. 첫번째 방법
l = []
for x in list:
	l.append( x ** 2 )

# 2. 리스트안 for문 사용법 (list-comprehension)
l = [ value ** 2 for value in list ]
```
이 방법은 굉장히 중요한데, 그 이유는 1번 방법보다 2번 방법이 더 빠르기 때문입니다. 그러기에 2번 방식으로 구사할 수 있는 방법이라면 사용하는게 좋습니다. list-comprehension이 더 빠른 이유는 파이썬를 개발한 개발자들이 알겠지만, list comprehension방식에서는 리스트를 확인할 필요없으며, 일일이 append 함수를 사용해주지 않아서 인걸로 알고있습니다. 

다음은 람다 표현식에대해 알아보겠습니다.