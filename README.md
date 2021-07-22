・pod 一覧取得
kubectl get pod

・pod 内のコンテナシェルに入る
kubectl exec -it [pod_name] bash

・pod 内に複数コンテナが存在する場合にコンテナを指定してシェルに入る
kubectl exec -it [pod_name] bash [--container or -c] [container_name] bash
