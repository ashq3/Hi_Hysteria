#### 防火墙问题

请提前放行防火墙，保证该udp端口可达！

仅对于faketcp模式，则为放行server的tcp端口。

如果不使用自签方式，则应该放行TCP 80/443供hysteria内置的ACME验证。

`0.2.9`**版本后脚本自动放行所需端口，请注意！**