# jquery 오목 만들기!

## 목표
주어진 오목판에 검은돌과 흰돌을 번갈아서 놓는 오목게임을 만들자!

## 주어진 것
* app/views/main/index.html.erb 파일만 사용하여 만들자!

* 바둑판 한칸은`.go-cell`로 선택할 수 있다. 이 class를 가진 `<div>`태그 안에 바둑돌을
  놓도록 하자.

* 바둑돌을 직접 만드는 것을 추천하지만 귀찮다면 하단의 4개의 코드를 써도
무방하다.
```{.html}
<button class="black stone"></button> <!-- 검은돌 -->
<button class="white stone"></button> <!-- 흰돌 -->
<button class="semi_black stone"></button> <!-- 투명한 검은돌 -->
<button class="semi_white stone"></button> <!-- 투명한 흰돌 -->
```

* 'jquery data attribute'를 구글링 해보길 추천!
