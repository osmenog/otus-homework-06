# otus-homework-06
Для запуска можно вызвать команду:
```
skaffold run --tail
```
или развернуть при помощи helm (предварительно создав namespace командой `kubectl create namespace otus`):
```
helm install otus ./k8s/user_service -n otus
```
