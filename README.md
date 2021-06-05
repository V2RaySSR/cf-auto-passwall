## 自动替换 PassWall 里面的 WS 节点地址 为 CF 优选的IP


用途：用于自动筛选 CF IP，并自动替换优选 IP 为 PassWall 的节点地址

网站： www.v2rayssr.com （已开启禁止国内访问）

YouTube频道：波仔分享

本脚本源于 GitHub：Lbingyi 以及 Paniy

本教程视频演示地址：等等

使用说明：加在 openwrt 上系统 计划任务里 添加定时运行，如 0 4 * * 2,4,6 bash /root/cf-aoto-passwall.sh > /dev/null

0 4 * * 2,4,6 的意思是在每周二、周四、周六的凌晨4点会自动运行一次。/root/cf-aoto-passwall.sh 是你脚本的绝对地址

## 注意事项

1、请在脚本中修改你期望优选 IP 的带宽大小（默认50M）

2、请更改 427 行 的 xxxxxxxxxx 字符串，为你自己 PassWall 的节点值（不会请看视频教程或是博客）
