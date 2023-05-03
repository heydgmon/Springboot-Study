# 프록시 패턴
![proxy uml](https://user-images.githubusercontent.com/40292371/235812878-6c849bbc-f8ad-4506-b224-8337d7c4f203.png)

프록시 패턴이란?
->프록시 패턴은 어떤 객체에 대한 접근을 제어하는 용도로 대리인에 해당하는 객체를 제공하는 패턴

1.Client : 고객


2.Subject : 결제


3.Proxy : 체크카드


4.RealSubject : 체크카드에 연관된 은행 계좌


고객이 매장에 방문해서 상품을 체크카드로 결제를 하게 되면, 체크카드에 연관된 계좌에 돈이 빠져나감

체크카드는 결제를 대행해주는 Proxy 역할을 하고, 은행계좌는 외부로부터 숨겨 민감정보를 보호할 수 있음

 
