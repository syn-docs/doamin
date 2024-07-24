# 域名配置文档

每当添加域名时，需要:

1) 在 [Ali云域名服务](https://dc.console.aliyun.com/next/index#/domain/list/all-domain) 上新增域名。
2) 在 [Ali云解析DNS/域名解析](https://dns.console.aliyun.com/#/dns/domainList) 上新增域名解析,如CNAME,A 记录等
例如：hotcoin.cc--> `www.hotcoin.cc.relartemis.com`[cdn服务](https://console.cdnetworks.com/cas/login?service=https://console.cdnetworks.com/cdn/auth/ticket)
3) 在 [CDN服务上配置阿里的LB](https://console.cdnetworks.com/cas/login?service=https://console.cdnetworks.com/cdn/auth/ticket)。
1) 在 [在Ali的LB上配置](https://slb.console.aliyun.com/slb/ap-southeast-1/slbs) 转发策略-类似nginx配置。
4) 确认域名能正常访问以及与转发策略正确。




## 域名新增记录

📝 改动记录这里

| S/N | 日期            | 修改                             |
|-----|-----------------|-------------------------------------| 
| 1   | 23/7/2024     | 新增域名hotcoin.cc  hotcoin.zone  hotcoin.link           
