# conda_env
Anaconda的各种开发环境

#### Anaconda 环境的常用命令:

- 安装一个package:

  `conda install package_name=version`

  `version`可以指定

- 删除一个package:

  `conda remove package_name`

- 升级一个package:

  `conda update package_name`

- 模糊查询package:

  `conda  search search_term`

- 创建一个新环境:

  `conda create -n env_name`

- 查看有哪些环境:

  `conda env list`

- 进入一个新环境:

  `source activate env_name`


- 退出当前环境:

  `source deactivate`

- 删除环境:

  `conda env remove -n env_name`

- 保存一个环境:

  `conda env export > environment.yaml`

- 从文件还原一个环境:

  `conda env create -f environment.yaml`

