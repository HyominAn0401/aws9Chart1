# MY HELM CHART

## 설명
이 chart는 테스트용 차트입니다. 
사전에 metallb를 설치해 두셔야 합니다!
<!--의존성은 chart에 작성-->

## 설치 방법
```bash
helm repo add myrepo1 https://HyominAn0401.github.io/aws9Chart1
helm install myrelease1 myrepo1/nginx-chart

of
helm install myrelease1 myrepo1/nginx-chart --set replicaCount=8
```