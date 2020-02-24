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