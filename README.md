# 安卓lxc-docker内核修改

# 开启/关闭配置


./LXC-DOCKER-OPEN-CONFIG.sh <xxx_defconfig> -w


# 打补丁1(有则打无则过)
xt_qtagui.patch




# 打补丁2(找准cgroup.c文件和函数位置打)
cgroup.patch
