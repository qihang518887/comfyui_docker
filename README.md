# comfyui_docker
基于pytorch2.7构建的comfyui docker镜像，适配aaalice的工作流

# 前提条件
操作系统 windows ltsc 2021及更新的版本
显卡 帕斯卡架构及更新的架构
已安装docker

# 使用方法
docker run --gpus=all --network=host mayin/comfyui:20250626
