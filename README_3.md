# TIL
##  동기/비동기
####  동기(Synchronous)
- 코드가 **위에서 아래로, 순차적으로** 실행된다.
- 한 작업이 끝나야만 다음 작업으로 넘어간다.
- 흐름이 단순하고 예측하기 쉽지만, 시간이 오래 걸리는 작업이 있으면 그동안 전체가 멈춘다.
- 예: `for` 반복문, 일반 함수 호출
####  비동기(Asynchronous)
- 오래 걸리는 작업을 **백그라운드(Web APIs, Node APIs 등)**로 넘기고,  
  그 사이에 나머지 코드를 먼저 실행한다.
- 작업이 끝났을 때 **콜백(callback)**, **Promise**, **async/await** 등을 통해 결과를 전달한다.
- 코드의 실행 순서가 실제 작성된 순서와 다를 수 있다.
- 예: `setTimeout`, `fetch`, `addEventListener` 등
