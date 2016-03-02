dproxy DNS proxy server
===
dproxy DNS 代理服务器 [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) writing in GO

# 功能:
> * 使用redis存储name记录
> * 区别内外网
> * 没有的记录通过其他代理返回结果并缓存
> * 增加DNS记录管理功能

# TODO:
> - [ ] Implement DNS server
> - [ ] Implement config system
> - [ ] Records backend store
> - [ ] Implement bind two interface for different dns records result
