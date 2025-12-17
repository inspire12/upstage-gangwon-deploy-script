# secret 

app-secret
- upstage API KEY 등록
```bash
kubectl create secret generic app-secret \
  --from-literal={UPSTAGE_API} \
    -n gangwon
```