# Cloude Study Jam

- 사전 지식: AWS IAM, EC2, DynamoDB 지식 사용 경험, docker 개념

구글 스터디 잼 쿠버네티스 입문반을 진행하면서 정리한 repository입니다.

Qwiklabs 를 이용해서 학습을 진행할 예정입니다. 영문으로 이뤄져있는 만큼 모두 번역해서 정리해둘 예정입니다.

> https://www.cloudskillsboost.google/quests/29?catalog_rank=%7B%22rank%22%3A1%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&search_id=17324522

## Quest: Kubernetes in Google Cloud

Kubernetes는 가장 인기있는 container orchestration system입니다. 그리고 Google Kubernetes Engine은 구글 클라우드에서 쿠버네티스 배포를 관리하기위해 만들어졌습니다. 이번 고급 수준의 Quest(Qkiklabs에서 하나의 수업 개념)을 통해서 Docker images, containers를 설정하는 것과 쿠버네티스 엔지 어플리케이션을 배포하는데 익숙해질 것입니다. 이번 quest은 우리의 작업에서 컨테이너 orchestration을 통합하는데 필요한 실용적인 기술들을 알려줄 것입니다. 당신의 지식을 검증하고 너의 기술을 증명할 hands-on challenge lab을 찾고 있나요? 이번 quest를 끝내고 Google Cloud digital badge를 얻기 위해 [Deploy to Kubernetes in google cloud](https://google.qwiklabs.com/quests/116)을 끝내고 추가로 [Challenge Lab](https://google.qwiklabs.com/catalog_lab/2524)를 끝내자.

당신이 이번 활동을 잘 마무리한다면, 당신은 쿠버네티스 모양의 배치를 얻을 수 있습니다. 프로필 페이지에서 얻어온 모든 뱃지를 볼 수 있습니다. 그리고 cloud career를 더 높여보세요.

1. [Introduction to Docker](https://www.cloudskillsboost.google/focuses/1029?parent=catalog)

해당 랩에서 우리는 도커 컨테이너 환경 커맨드들에 익숙해질 것 입니다. 컨테이너들을 만들고 실행하고 디버깅하고 구글 컨테이너 registry 에 이미지를 pull, push 하는 것을 배우게 됩니다.

2. [Kubernetes Engine: Qwik Start](https://www.cloudskillsboost.google/focuses/878?parent=catalog)

구글 쿠버네티스 엔진은 구글 인프라를 사용하는 컨테이너 어플리케이션을 scaling, managing, deploying 하기 위해 관리되는 환경을 제공합니다. this hands-on lab은 쿠버네티스 엔진을 가지고 컨테이너 어플리케이션을 배포하는 방법을 보여줍니다. => AWS로 하는 것도 같이 공부해서 정리하기

3. [Orchestrating the Cloud with Kuberntes](https://www.cloudskillsboost.google/focuses/557?parent=catalog)

이번 lab에서는 구글 컨테이너 엔진을 사용해서 쿠버네티스 클러스터를 provision하는 방법을 배웁니다. kubectl을 사용해서 도커 컨테이너를 관리하고 배포하고 어플리케이션을 마이크로서비스로 나누게 됩니다.

4. [Managing Deployments Using Kubernetes Engine](https://www.cloudskillsboost.google/focuses/639?parent=catalog)

Dev Ops best practices는 어플리케이션 배포 시나리오를 관리하기위해서 여러 배포방식을 가능하도록 해줍니다.(의역 심함..) 이번 lab은 흔히 발생하는 시나리오들(이기종 - 서로다른 종류의 배포를 할 때) 컨테이너들의 스케일링과 관리하는 연습을 하게됩니다.

=> 여러 복잡한 배포방식들을 통합하는 시나리오들을 학습할 듯

5. [Continuous Delivery with Jenkins in Kubernetes Engine](https://www.cloudskillsboost.google/focuses/1104?parent=catalog)

이번 랩에서는 우리는 쿠버네티스 엔진속에서 실행되는 젠킨스를 사용해서 CD pipeline을 설정하고 배포를 진행하게 됩니다.
