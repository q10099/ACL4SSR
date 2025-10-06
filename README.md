使用proxy-providers和rule-providers，无需订阅转换（需要订阅链接支持clash），
可混合订阅多个机场，甚至混合自建节点，实现跨机场自动选择和负载均衡。
可自由搭配ACL4SSR和clash-rules等所有公开项目下的规则，并且混入个人自定义规则。
代理节点，规则无耦合，所有订阅和规则集均可单独更新，更新订阅后不会覆盖任何已设置的分组和规则，同样地，修改规则对订阅也是无感知的。

将config文件Clash/extra/config/clash-url.yaml复制到本地使用，或者安全托管后复制url导入clash，托管url方式可实现多端同步，修改订阅和规则在Github或安全托管平台即可完成。
