### 글로벌 fetch 전략 설정
+ 모든 연관관계를 지연 로딩(fetch = Lazy)
+ @ManyToOne, @OneToOne은 기본이 즉시 로딩이므로 지연로딩으로 변경
***
### 영송성 전이 설정
+ Order -> Delivery를 영속성 전이 All 설정
+ Order -> OrderItem을 영속성 전이 All 설정
+ 
