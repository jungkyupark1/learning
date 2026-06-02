# Troubleshooting


## 노드 생성 시 할당되었으나 오류가 발생한 경우

CycleCloud UI 서버를 우회해서 문제가 된 노드에 SSH로 접속하여 문제를 파악할 수 있다.

```bash
sudo ssh -i /opt/cycle_server/.ssh/cyclecloud.pem cyclecloud@<문제 노드 IP>
```
