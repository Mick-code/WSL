# 设置WSL固定IP

win+R，输入shell:startup

将bat脚本放入打开的文件夹中即可

可以实现开机自启设置ip，无弹窗

可以编辑bat脚本来设置想要的ip

默认本机设为172.25.0.1，wsl为172.25.0.2



想要自启wsl的服务也可以加在bat脚本末尾，如启动docker

```
wsl service docker start
```

