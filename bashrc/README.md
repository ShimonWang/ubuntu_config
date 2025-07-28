## 文件路径

~/.bashrc

## 使用须知

隐藏文件

ctrl+h切换显示

## 修改配置

1. 只在非conda环境下加载ROS
```
# 只在非conda环境下加载 ROS
if [ -z "$CONDA_PREFIX" ]; then
# ROS Noetic 环境
    source /opt/ros/noetic/setup.bash
    # echo "Loading catkin_ws..."
    [ -f ~/catkin_ws/devel/setup.bash ] && source ~/catkin_ws/devel/setup.bash
    # echo "Loading baxter_ws..."
    [ -f ~/baxter_ws/devel/setup.bash ] && source ~/baxter_ws/devel/setup.bash
fi
```

2. 启动终端默认不加载conda base环境
```
# 可选：如果希望 conda base 环境不自动激活（避免干扰系统 Python）
# conda config --set auto_activate_base false
conda config --set auto_activate false
```
