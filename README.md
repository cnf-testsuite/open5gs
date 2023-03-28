###Run Example

```helm repo add openverso https://gradiant.github.io/openverso-charts/```

Install Open5gs 
```helm install open5gs openverso/open5gs --version 2.0.8 --values https://gradiant.github.io/openverso-charts/docs/open5gs-ueransim-gnb/5gSA-values.yaml```

Install RAN & UE
```helm install ueransim-gnb openverso/ueransim-gnb --version 0.2.2 --values ./gnb-ues-values.yaml

