# based on

https://github.com/ToiCF/GrainTCP

https://github.com/sskkvw/GrainTCP

thanks to ToiCF、sskkvw

workers或pages部署二选一即可

默认的UUID是
```text
7f3a9c2e-6b41-4d8f-a5e7-92c1f4b8d630
```

强烈建议修改 UUID 后再部署，UUID在线生成：https://www.uuidgenerator.net/version4

workers部署后，必须绑定自定义域名，然后把 **your.domain** 替换成你绑定的自定义域名

pages部署后，将分配给你的pages域名替换掉 **your.domain** ，如果pages你也绑定了自定义域名，那么可以把 **your.domain** 替换成你绑定的自定义域名

UUID 替换为你自己的 UUID

```text
vless://UUID@your.domain:443?encryption=none&security=tls&sni=your.domain&insecure=0&allowInsecure=0&type=ws&host=your.domain&path=%2F#vle
```
