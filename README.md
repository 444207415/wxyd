# wxyd

qinglong面板，微信阅读

收益：一天1.8-2.2元（当前每日30篇*6轮180篇文章约2.2元），自动提现


微信打开：https://zl0114225029-1314804847.cos.ap-nanjing.myqcloud.com/index.html?upuid=10701353

ios用stream抓包
抓包m.*.shop域名下cookie，
复制udtauth16=abcd; PHPSESSID=abcd的内容，

打开青龙面板的配置文件config.sh,并插入新的参数：


export yuedu="udtauth16=abcd; PHPSESSID=abcd"


![image](https://user-images.githubusercontent.com/127284854/223635745-f96b0ec8-d205-48e9-97da-deda110d39a1.png)


ps：每天会验证2次左右，碰到验证文章手动打开看一篇即可


