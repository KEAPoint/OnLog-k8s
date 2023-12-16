# OnLog-k8s

이 저장소는 Kubernetes 매니페스트(manifests)를 관리하고, 이미지 버전을 추적하기 위한 곳입니다. 

## 🔍 소개

이 레포지토리는 Jenkins와 Argo CD를 활용한 CI/CD 파이프라인의 핵심 요소입니다. Jenkins는 각 서비스의 소스 코드 변경을 감지하고, Docker 이미지를 빌드한 후, 이 이미지의 새로운 버전 정보를 이 레포지토리에 푸시합니다. 이렇게 업데이트된 매니페스트는 Argo CD에 의해 감지되어, 자동으로 쿠버네티스 클러스터에 배포됩니다.

이 과정을 통해, 이 레포지토리는 소스 코드의 변경부터 서비스의 배포까지 이어지는 CI/CD 파이프라인에서 중요한 역할을 합니다.

![cicd](https://github.com/KEAPoint/OnLog-k8s/assets/74820505/58d778a5-02c8-4db9-be9d-da766307749d)
