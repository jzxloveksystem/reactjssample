# reactjs sample code 

> dev
- npm install -g create-react-app
- create-react-app react-sample

> user
- yarn install
- yarn start

# +redux 
> 정의 : 가장 사용률이 높은 상태관리 라이브러리 
- (추가적으로 미들웨어 기능 포함?)
- https://velog.io/@velopert/Redux-1-%EC%86%8C%EA%B0%9C-%EB%B0%8F-%EA%B0%9C%EB%85%90%EC%A0%95%EB%A6%AC-zxjlta8ywt

> react의 단점 
- 할머니 component -> 엄마 component -> 딸 component, 아들 component 
  - (일은 결국 전달,전달해서 할머니가 다 한다. 가독성 떨어짐, 관리 어려움)
- 불필요한 rerendering 

> react + redux
- component 밖에서 store라는 객체 내부에 status를 담고 관리한다.
- status에 어떤 변화를 일으켜야 하면, action을 store에 전달한다. 

> 개념 : 
- Action 액션 
- Action Creator 액션 생성함수 
- Reducer 리듀서 => store에 전달된 action으로 status를 어떻게 변경할지 결정, 변경된 status는 store에 저장 
- Store 스토어 => status 담는다. 
- dispatch 디스패치 => store에 action을 전달하는 과정 
- subscribe 구독 => status가 바뀌면, store를 구독하고 있는 component에 바로 전달한다. 
- (추가) status 상태 

> ※ redux는 react에서 사용하려고 만든 상태 관리 라이브러리지만, react에 의존하지는 않는다.


