# デプロイ方法

```
// deploymentを適用
$ kubectl apply -f deployment.yaml

// serviceを適用
$ kubectl apply -f service.yaml
```

# IP を払い出す

```
$ minikube service <サービス名> --url
```
