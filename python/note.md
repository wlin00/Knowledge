# virtualenv
- 安装  
  `pip3 install virtualenv`
- 创建一个独立的Python运行环境，命名为venv  
  ` virtualenv --no-site-packages venv` 
  - 其中加入参数`--no-site-packages`，这样，已经安装到系统Python环境中的所有第三方包都不会复制过来
- 进入环境  
  `source venv/bin/activate`
- 退出环境  
  `deactivate`

## 关于如何指定python2和python3
- 如果要创建python2的环境的话，命令为  
  `virtualenv -p /usr/bin/python2.7 env2.7`
- 如果要创建python3的环境话，命令为  
  `virtualenv -p /usr/bin/python3.5 env3.5`