# k8sDOJO
Kubernetes道場をひたすらこなす記録リポジトリ
- https://cstoku.dev/posts/2018/k8sdojo-01/

## 環境
Minikubeを採用する
- MinikubeはKubernetesをローカルマシンで構築するためのツールである。

Minikubeは複数のDriverが利用でき、以下の仮想化機構を使って構築できる。
- virtualbox
- vmwarefusion
- kvm2
- kvm
- hyperkit
これらの仮想化機構を使いVMを作成し、そのVM上にKubernetesを構築する。

今回はVirtualBoxとMinikubeを導入し、Kubernetesを使用できるようにする。