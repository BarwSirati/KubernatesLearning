#### CLI
- ดูทรัพยากรทั้งหมด
```bash
kubectl get all
```

- ดู pods
```bash
kubectl get pods
```

- ใช้งานไฟล์
```bash
kubectl apply -f myfile.yml
```

- ดูเซอร์วิสทั้งหมด
```bash
kubectl get services
```

- ดู log pod
```bash
kubectl logs mypods
```

- ลบ pod
```bash
kubectl delete pod mypod
```

- ลบ service
```bash
kubectl delete servicce myyservice
```

- ลบ pod หรือ service ทั้งหมด
```bash
kubectl delete pod/service --all
kubectl delete all --all
```

- ดู Service ทั้ง
```bash
kubectl get services
```
