## immer를 설치하고 실습한 저장소

#### install

```
yarn add immer
```

<br>

#### immer를 사용하는 이유
불변성을 위해서 immer를 사용한다. 패키지를 쓰면 편해지는 경우가 있고,
안 써도 되는 경우가 있다.

<br>

#### 사용법

```js
import produce from 'immer';

produce(수정하고 싶은 상태, 업데이트 함수)
```