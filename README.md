# define

> Definitions for dev ref

# authentication 
- JWT (Json Web Tokens)
  - https://jwt.io/
  - https://velopert.com/2389 
- express-session + connect-redis
  - https://stackoverflow.com/questions/25532692/how-to-share-sessions-with-socket-io-1-x-and-express-4-x

> KeyWord
- react nodejs express socket.io session 
  - how to share session between express and socket.io ?
- passport, cookie-parser, cookieSession 

# protocol / domain / path / query string 
- Ex. http://a.com/topic?id=1
  - https://pro-self-studier.tistory.com/76?category=664874

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
  - ALB, NLB, CLB
  - EC2 2개 
  - sticky session 

> S3 (Simple Storage Service)
  - bucket (버킷) === 폴드 
  - lifecycle : S3 => Glacier 파일 이전, 오래 된 파일은 저가 storage로 이동해서 보관(archive,아카이브)
  - https://bluese05.tistory.com/39
  - https://medium.com/@autumn.bom/archiving-s3-to-glacier-b01e31940037
  
> CloudFront 
  - AWS CDN(Content Delivery Network)
  - 전세계 AWS 각 리전의 로케이션에 리소스 복사본을 미리 로드해놓고, 사용자들이 짧은 지연 시간에 파일을 받을 수 있도록 해준다. 
  - Edge Location, Origin Server 
  - https://musma.github.io/2019/06/29/publish-static-assets-over-https-using-cloudfront.html
  - https://walkinpcm.blogspot.com/2017/06/aws-aws-s3-static-website-hosting.html
  - 요금 
  - https://www.youtube.com/watch?v=L4xH1j7266A&feature=emb_title

> IAM (Identity and Access Management)
  - 인증 및 권한 
  - 사용자, 접근 유형, 그룹, 권한 
  - 보안 키 (API Key)
  - +MFA (Multi-Factor Authentication) : 2중 보안 (SMS,Email, Google Authenticator)

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
  
# FPS (Frames Per Second, 초당 프레임) 
- != 모니터 주사율

# Parallax Scrolling 
- 마우스를 스크롤할 때, 
- 원거리에 있는 배경 이미지는 느리게 움직이게 하고, 
- 근거리에 있는 사물 이미지는 빠르게 움직이도록 함으로써 입체감을 느낄 수 있게 만든 디자인 기법
- https://ko.wikipedia.org/wiki/%ED%8C%A8%EB%9F%B4%EB%9F%AD%EC%8A%A4_%EC%8A%A4%ED%81%AC%EB%A1%A4%EB%A7%81

# Scroll Performance ? 
- infinite scroll
- virtualized list

# UI/UX
- https://materializecss.com/
- https://material-ui.com/

# Animation 
- 1) react-motion 
  - https://github.com/chenglou/react-motion
  - https://github.com/chenglou/react-motion/wiki/Gallery-of-third-party-React-Motion-demos
- 2) react-spring 
  - https://www.react-spring.io/docs/hooks/examples
- 3) react-animations
  - https://github.com/FormidableLabs/react-animations
- 4) react-reveal
  - https://www.react-reveal.com/
- 5) ?
  - https://lottiefiles.com/
  - https://github.com/chenqingspring/react-lottie
  - https://levelup.gitconnected.com/master-ux-with-react-in-2020-four-ways-to-upgrade-your-react-app-user-experience-a053b3ffbf59
  - https://github.com/google-fabric/velocity-react

# react example 
  - https://reactjsexample.com/
