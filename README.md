# xwiki

DatabaseにはAutonomous Databaseを使用。

ディレクトリ構造は以下の通り

```
$ tree
.
├── README.md
├── docker-compose.yaml
├── hibernate.cfg.xml
├── libs
│   ├── ojdbc10.jar
│   ├── oraclepki.jar
│   ├── osdt_cert.jar
│   └── osdt_core.jar
└── wallet
    ├── README
    ├── cwallet.sso
    ├── cwallet.sso.lck
    ├── ewallet.p12
    ├── ewallet.p12.lck
    ├── ewallet.pem
    ├── keystore.jks
    ├── ojdbc.properties
    ├── sqlnet.ora
    ├── tnsnames.ora
    └── truststore.jks
```