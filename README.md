# define

> Definitions for dev ref

# GCM, FCM 
- GCM : Google Cloud Messaging 
- FCM : Firebase Cloud Messaging 
  - +ServiceWorker
- https://cionman.tistory.com/66
- https://www.youtube.com/watch?v=BsCBCudx58g

# Service Worker
- https://developers.google.com/web/fundamentals/primers/service-workers?hl=ko

# Manifest.json
- https://web.dev/add-manifest/

# AWS 

> EC2 (Elastic Compute Cloud)

> Route53 
- 새 도메인을 등록하고, 기존 도메인을 이전하며, 도메인의 트래픽을 AWS 및 외부 리소스로 라우팅하고, 
- 리소스의 상태를 모니터링할 수 있습니다.
- Hosted-Zone (호스팅 영역 생성)
  - Domain -> DNS  
- Record Set
  - ELB 연결 

> ACM (AWS Certificate Manager)
- SSL/TLS

> ELB (Elastic Load Balancer)
  - 
  - EC2 2개 
  - sticky session 

> Ref
- https://velog.io/@minholee_93/AWS-ELB-SSL-%EC%9D%B8%EC%A6%9D%EC%84%9C-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0-mfk4dpjrd6

# Nginx ( Engine X )

> Dev

# GIF 

- https://tenor.com/
- https://giphy.com/

# Domain

- https://www.viaweb.co.kr/
- https://sg.godaddy.com/
- https://www.gabia.com/

# Load Balancer

- Scale Up : Server가 더 빠르게 동작하기 위해 하드웨어 성능을 올리는 방법 
- Scale Out : 하나의 Server보다는 여러대의 Server를 나눠서 일을 하는 방법 
  - 장점 
  - 1) 하드웨어 향상하는 비용보다 서버 한대 추가 비용이 더 적습니다. 
  - 2) 여러 대의 Server 덕분에 무중단 서비스를 제공할 수 있습니다. 
  - 여러대의 Server에게 균등하게 Traffic을 분산시켜주는 역할을 하는 것이 Load Balancer 입니다. 
  
- 종류  
- 1) Round Robin 
  - 단순히 Round Robin으로 분산하는 방식, 즉 2개 서버 번갈아 가면서 분산 
- 2) Least Connections 
  - 연결 개수가 가장 적은 서버를 선택하는 방식 
  - 트래픽으로 인해 세션이 길어지는 경우 권장하는 방식 
- 3) Source 
  - 사용자의 IP를 Hashing 하여 분배하는 방식 
  - 사용자는 항상 같은 서버로 연결되는 것을 보장
  

