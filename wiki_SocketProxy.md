## 端口转发映射代理穿透
- https://github.com/fatedier/frp    //Golang。用于内网穿透的高性能的反向代理应用，多协议支持，支持点对点穿透，范围端口映射。greatjob,25k。
- https://github.com/inconshreveable/ngrok    //Go。端口转发，正反向代理，内网穿透.17K。
- https://github.com/L-codes/Neo-reGeorg    //Py。‘reDuh’‘reGeorg’的升级版，把内网端口通过http/https隧道转发形成回路。用于目标服务器在内网或做了端口策略的情况下连接目标服务器内部开放端口（提供了php，asp，jsp脚本的正反向代理）。goodjob。
- https://github.com/cnlh/nps    //Go。内网穿透代理服务器。支持tcp、udp流量转发，支持内网http代理、内网socks5代理，同时支持snappy压缩、站点保护、加密传输、多路复用、header修改等。WebGUI,多用户。
- https://github.com/vzex/dog-tunnel    //Go。Linux下基于kcp的p2p端口映射工具，同时支持socks5代理。2k。G:SECFORCE/Tunna;G:securesocketfunneling/ssf;G:sysdream/ligolo;--
- https://github.com/Dliv3/Venom    //Go。类似于Termite/EarthWorm架构的多节点连接跳板构建多级代理工具。W:rootkiter.com/Termite/;G:ls0f/gortcp;Github:rtcp;Github:NATBypass;--
- https://github.com/decoder-it/psportfwd    //PowerShell。无需admin权限进行端口转发。
- https://github.com/davrodpin/mole    //Go。基于ssh的端口转发。
- https://github.com/fbkcs/thunderdns    //Py。将tcp流量通过DNS协议转发，不需要客户端和socket5支持。
- https://github.com/esrrhs/pingtunnel/    //go。构建icmp隧道转发tcp/udp/sock5流量，端口转发、绕过验证。G:jamesbarlow/icmptunnel;--
### 端口复用
- https://nets.ec/Shellcode/Socket-reuse    //C。套接字重用。
- https://github.com/earthquake/UniversalDVC    //C++。利用动态虚拟通道注册dll文件，进行rdp服务端口复用
- https://github.com/cloudflare/mmproxy    //C。在负载均衡HAProxy代理的基础上支持proxy-protocol协议，可以传递客户端TCP协议的真实IP。配合Netsh、Iptables实现端口复用。
- https://github.com/BeetleChunks/redsails    //PY,C++。利用WinDivert驱动程序与windows内核交互，不更改端口开放状态进行端口复用TCP流量到另一个主机，在目标主机上执行命令且无需创建任何事件日志以及网络连接，可使用powershell。testjob。
### 代理池
- https://github.com/SpiderClub/haipproxy    //Py3。Scrapy and Redis，高可用ip代理池
- https://github.com/chenjiandongx/async-proxy-pool    //py3。异步爬虫ip代理池
- https://github.com/audibleblink/doxycannon    //Py。使用一个openvpn代理池，为每一个生成docker，当连接某一个vpn后，其它的进行socks5转发做流量分发。
- https://github.com/realgam3/pymultitor/    //Py。使用多线程Tor代理
### IPv6安全相关
- https://github.com/sfan5/fi6s    //ipv6端口快速扫描器
- https://github.com/fgont/ipv6toolkit    //C。si6networks.com组织的ipv6工具集
- https://github.com/lavalamp-/ipv666    //Go。ipv6地址枚举扫描
- https://github.com/christophetd/IPv6teal    //Py。利用ipv6隐蔽隧道传输数据
## Cross超越边界
- https://github.com/bannedbook/fanqiang/wiki    //cross汇总
- https://github.com/ToyoDAdoubi/doubi    //各种常用一键脚本。G:Nyr/openvpn-install;G:quericy/one-key-ikev2-vpn;G:teddysun/shadowsocks_install;G:teddysun/across;--
- https://github.com/netchx/Netch    //C#。类似于sockscap64通过进程选择代，通过虚拟网卡转为类VPN全局代理SSTAP，类proxifier架构，需要.NetFramework4.8。welljob。
- https://github.com/guyingbo/shadowproxy    //ss/socks5/http//https 等多种网络代理
- https://github.com/ssrpanel/SSRPanel    //ss\ssr\v2ray用户分布式管理
- https://github.com/Ahref-Group/SS-Panel-smarty-Edition    //ss用户分布式管理，兑换码功能、商城系统，服务器信息。G:xuanhuan/ss-panel;G:shadowsocks/shadowsocks-manager;
G:Ehco1996/django-sspanel;G:leitbogioro/SSR.Go;--
- https://github.com/txthinking/brook    //Go。支持Linux/MacOS/Windows/Android/iOS的代理与vpn
- https://github.com/Ccapton/brook-web    //brook程序服务端Web后台管理服务器（Linux\MacOS），基于python、flask、flask-restful
- https://github.com/Ccapton/brook-ok    //Bash。Brook一键安装脚本
- https://github.com/v2ray/v2ray-core    //Go。多协议代理平台，自定义代理工具。G:2dust/v2rayN;--
- https://github.com/p4gefau1t/trojan-go    //go。支持自动证书申请/多路复用/路由功能/CDN中转，多平台，无依赖。G:gwuhaolin/lightsocks;--
- https://github.com/Umbrellazc/BypassCampusNet    //校园网防断网; UDP 53 免流上网。
- https://github.com/ntkernel/lantern    //蓝灯unlimited-landeng-for-win，无限流量蓝灯。W:psiphon3.com;W:mono.sh //飞机场。mymonocloud;W:windscribe.com;W:hide.me;--
- https://ding-doc.dingtalk.com/doc#/kn6zg7/hb7000    //钉钉内网穿透。G:open-dingtalk/pierced--
### Cross自组网
- http://www.vpngate.net    //日本国立筑波大学云局域网。SoftEther开源、跨平台、多重协议的虚拟专用网方案
- https://github.com/slackhq/nebula    //GO。slack采用p2p自组网。goodjob。P:红蓝对抗之组一个安全的网;--
- https://github.com/zerotier    //C++。网络虚拟化平台云自组网
- https://www.wireguard.com/install/    //新一代跨平台npv协议。G:angristan/wireguard-install;--
- https://www.radmin-vpn.cn/    远程组网服务。
- https://github.com/microsoft/SDN    //PS。此存储库包括脚本，模板和示例交换机配置，以帮助管理员部署Windows Server 2016软件定义网络（SDN）堆栈并将其连接到其现有网络拓扑。
- https://feisky.gitbooks.io/sdn/    //sdn-handbook SDN网络指南