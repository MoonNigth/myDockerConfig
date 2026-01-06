通用Docker镜像安装：
1. 编辑docker-compose.yml文件
2. 切换到当前路径下执行 docker compose up -d,拉取镜像并启动容器
HACS安装：
3. docker版本没有HACS，需要进入容器执行 “wget -O - https://get.hacs.xyz | bash -”安装
4. 后续其他用户自定义组件就可以通过HACS来进行安装，如果无法直接安装，可以自行访问对应插件的git说明，手工通过ssh脚本来安装
