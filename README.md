## IPv4 address locations by 纯真网络
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fritaswc%2Fzx-ip-address.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fritaswc%2Fzx-ip-address?ref=badge_shield)

IPv4 address locations by 纯真网络
##### version 4.0.1.123
## IPv6 address locations by Zx Inc.
IPv6 address locations by Zx Inc.composer php
##### database updated at 2020-05-06 with 140993 records

## usage
```shell script
composer require ritaswc/zx-ip-address
```
For Example
```php
$result = \Ritaswc\ZxIPAddress\IPv4Tool::query('114.114.114.114');
/*
$result = [
    "start" => "114.114.114.114"
    "end" => "114.114.114.114"
    "addr" => array:2 [
        0 => "江苏省南京市"
        1 => "南京信风网络科技有限公司GreatbitDNS服务器"
    ]
    "disp" => "江苏省南京市 南京信风网络科技有限公司GreatbitDNS服务器"
]
 */
```

```php
$result = \Ritaswc\ZxIPAddress\IPv6Tool::query('240e:e9:8819:0:3::3f9');
/*
$result = [
    "start" => "240e:e9:8800::"
    "end" => "240e:e9:8fff:ffff::"
    "addr" => array:2 [
        0 => "中国江苏省苏州市"
        1 => "中国电信IDC"
    ]
    "disp" => "中国江苏省苏州市 中国电信IDC"
]
 */
```

## Official Website
- [纯真IPv4数据库](http://www.cz88.net/ip/)
- [IPv6地址查询工具 Nanjing China](http://ip.lsy.cn)
- [IPv6地址查询工具 Tokyo Japan](http://ip.zxinc.org)
- [IPv6地址查询工具 Ningbo China](http://ip.ss.zxinc.org)

## Author
- [Charles的小星球](https://blog.yinghualuo.cn)

## License
ZxIpAddress is licensed under [MIT](https://github.com/ritaswc/zx_ip_address/blob/master/LICENSE).

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fritaswc%2Fzx-ip-address.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fritaswc%2Fzx-ip-address?ref=badge_large)