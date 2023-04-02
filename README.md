# kubernetes
集群部署相关适配脚本

执行以下脚本

    chmod +x kube_init.sh
    
    ./kuber_init.sh
    # 安装flannel 插件
    kubectl apply -f kube-flannel.yml
    # 验证是否是Ready状态
    kubectl get nodes
