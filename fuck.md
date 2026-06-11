# 使用教程

## 准备工作

下载Easytier

- [Windows x86](https://ghfast.top/https://github.com/EasyTier/EasyTier/releases/download/v2.6.4/easytier-gui_2.6.4_x64-setup.exe)
- [Android Arm64](https://ghfast.top/https://github.com/EasyTier/EasyTier/releases/download/v2.6.4/app-arm64-release.apk)
- [Linux GUI x86](https://ghfast.top/https://github.com/EasyTier/EasyTier/releases/download/v2.6.4/easytier-gui_2.6.4_amd64.deb)
- [Linux GUI AArch64](https://ghfast.top/https://github.com/EasyTier/EasyTier/releases/download/v2.6.4/easytier-gui_2.6.4_arm64.deb)
- [Linux CLI x86](https://ghfast.top/https://github.com/EasyTier/EasyTier/releases/download/v2.6.4/easytier-linux-x86_64-v2.6.4.zip)
- [Linux CLI Arm](https://ghfast.top/https://github.com/EasyTier/EasyTier/releases/download/v2.6.4/easytier-linux-arm-v2.6.4.zip)

确保您已安装并打开 EasyTier GUI 客户端。

## 使用步骤

### 1. 获取并复制节点配置文件

在浏览器中打开[配置生成页面](https://et.fmys.de/)，在URL后缀添加密码`1145141919810`
页面中会显示一段以 TOML 格式编写的 EasyTier 节点配置，全选并复制（Ctrl + A 然后 Ctrl + C）红框内的所有配置文本。
![1](https://github.com/fmys2010/cuntu/blob/main/Generated%20Image%20June%2011,%202026%20-%202_08PM.png?raw=true)

### 2. 在 EasyTier GUI 中创建新网络

打开 EasyTier GUI 客户端，点击右上角的 “+ 创建新网络” 按钮，这会为您新建一个默认的网络配置模版。
![2](https://github.com/fmys2010/cuntu/blob/main/Generated%20Image%20June%2011,%202026%20-%202_14PM.png?raw=true)

### 3. 进入“编辑为文件”

在新创建的网络配置页面中，找到左上角的 “编辑网络” 区域，点击 “编辑为文件” 按钮。此时客户端会弹出一个可以直接编辑底层 TOML 配置的代码文本框。
![3](https://github.com/fmys2010/cuntu/blob/main/Generated%20Image%20June%2011,%202026%20-%202_14PM(1).png?raw=true)

### 4. 替换并保存配置

在弹出的 “配置文件” 弹窗内，将原有的默认配置内容全部清空，将您在第一步中复制的网页配置代码，全选粘贴（Ctrl + V）到该输入框中，确认无误后，点击右下角的绿色 “保存” 按钮。
![4](https://github.com/fmys2010/cuntu/blob/main/Generated%20Image%20June%2011,%202026%20-%202_14PM(2).png?raw=true)

### 5. 启动网络

配置文件保存后，回到 EasyTier GUI 主界面，滑动到页面底部，点击绿色的 “运行网络 →” 按钮。稍等片刻，当状态显示为“已运行”时，表明您的 EasyTier 节点已根据该配置成功启动。
![5](https://github.com/fmys2010/cuntu/blob/main/Generated%20Image%20June%2011,%202026%20-%202_14PM(3).png?raw=true)

## 结语

> 要是这样你都不会用，那你真是个傻逼
> ——余华
>
> 如果你有什么问题，就去问AI，它会解决的
> ——马克·吐温
