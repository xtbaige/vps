####################################
#### 创建者：xtbaige
##### 客户端：Clash ，Quantumult X , V2yareN 
##### 更新时间：2024-1-08 23:49:04
#### 感谢大家一路支持卖货的老张，
##### 欧易客户端下载：http://xtbaige.myDS.me:5000/sharing/x4rqjEDqb

### 以下各平台的配置方法
   ## 如何使用QX懒人配置文件
第一步 下载预配置文件
  1.复制 https://raw.githubusercontent.com/xtbaige/vps/main/quantumult_x_20240108.conf
预配置文件链接（大家也可以在浏览器内打开该预配置文件链接以查看具体配置详情，好做进一步的理解）；
  2.进入 QuantumultX ，点击右下角 [三菱按钮/设置按钮]
  3.找到 [配置文件] 模块下的 [下载] 点击
  4.粘贴 刚刚复制的配置 [链接]，点击 右上角 [确定] 按钮
  5.确认，届时 QuantumultX 已添加 8个策略

✅ 解决办法：1.复制以下内容（ 其实就是 full.conf 预配置文件内的内容 ）；2.打开 Quantumult X ，点击 右下角 三菱按钮🔘，往下滑，找到 配置文件，点击编辑，长按任意位置，出现选择/全选/粘贴按钮，点击全选，然后点击粘贴；3.点击右上角完成按钮保存；
⚠️ Quantumult X 最新版本中在你还没有订阅机场节点（即第三步完成）前，APP主界面可能不会直接出现这8个策略；（02.19.2021）

✅ 解决办法：在第三步完成后会自行出现；
### 第二步 生成并配置证书

如果再此之前已经生成并信任证书则 生成并配置证书这一步可选择忽略；
进入 QuantumultX ，点击右下角 [三菱按钮]
找到 [MitM] 模块 - 生成并配置证书📄
进入QuantumultX，点击页面右下角三菱按钮，找到MinM模块，点击生成证书，提示生成成功，点击安装证书此时会跳转至 Safari，提示此网站...下载一个配置描述文件。您要允许吗？，点击允许，网页提示已下载描述文件；
进入 iOS 系统设置- 通用-描述文件-已下载的描述文件-选中，并安装，输入密码...完成描述文件安装；
进入 iOS 系统设置- 通用-关于本机-证书信任设置-针对根证书启用完全信任-选中刚刚安装的并启用即可；
找到 [重写] 模块 - 开启按钮 🔘
找到 [MitM] 模块 - 开启按钮 🔘
⚠️ 点击安装证书后不是在 Safari 打开，而是在其他浏览器打开，导致证书无法安装；

✅ 解决办法：打开 iPhone 设置 app - 搜索或下滑找到 Safari浏览器 点击 ， -找到 默认浏览器App ，选择 Safari浏览器， 然后重试第二步即可。
