# 脚本去广告

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) ![](https://shields.io/badge/-MITM--HOSTNAME合并-brightgreen) ![](https://shields.io/badge/-正则推导HOSTNAME-033da7) 

本项目的脚本去广告规则由《规则生成器》自动整合与去重。

重写规则所有数据均收集自开源项目，不代表我们支持或使用这些服务。

请通过我国(中华人民共和国)合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。
## 规则说明
整合知乎 什么值得买APP去广告，及脚本去除开屏广告复写。

## 规则统计

最后更新时间：2022-05-19 16:20:29

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| DOMAIN | 4  | 
| IP-CIDR | 1  | 
| IP-CIDR6 | 1  | 
| URL-REGEX | 4  | 
| USER-AGENT | 1  | 
| HTTP-REQUEST-SCRIPT | 1  | 
| HTTP-RESPONSE-SCRIPT | 27  | 
| REJECT | 17  | 
| MITM | 23  | 
| TOTAL | 79  | 


## Stash 

#### 规则链接
**MASTER分支 (每日更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rewrite/Stash/AdvertisingScript/AdvertisingScript.stoverride

**MASTER分支 CDN (每日更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rewrite/Stash/AdvertisingScript/AdvertisingScript.stoverride

**RELEASE分支 (不定时更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rewrite/Stash/AdvertisingScript/AdvertisingScript.stoverride

**RELEASE分支CDN (不定时更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rewrite/Stash/AdvertisingScript/AdvertisingScript.stoverride

## 子规则

当前分流规则，未包含其他子规则。


## 数据来源

《脚本去广告》的数据来自以下链接，如与本项目的《脚本去广告》规则混合使用，可能造成部分重写重复。

- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/zhihu/zhihu_plus.lnplugin
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.lnplugin
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/startup/startup.sgmodule


感谢以上规则作者的辛勤付出（排名不分先后）。

## 最后

### 感谢

[@Tartarus2014](https://github.com/Tartarus2014)  [@chenyiping1995](https://github.com/chenyiping1995) 

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。