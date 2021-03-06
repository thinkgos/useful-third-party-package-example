# useful-third-party-package-example

非常有用的第三方包示例或新feature,并做简单笔记,以备将来不时之需,可以快速的使用起来.

## package example

- code generate 代码生成器
    - [genny](code_generate/genny_generics_code) [genny](github.com/cheekybits/genny) 使用genny根据模板生成代码
    
- feature go新版本特性测试
    - [embed-go1.16](feature/embed-go1.16) go1.16 embed测试

- runtime_statistics
    - [statsview](runtime_statistics/statsview) [statsview](github.com/go-echarts/statsview) stats view 
    - [statsviz](runtime_statistics/statsviz) [statsviz](github.com/arl/statsviz) stats viz

- http client
    - [gout](httpclient/gout) [gout](github.com/guonaihong/gout)
    - [resty](httpclient/resty) [resty](github.com/go-resty/resty)

-image    
    - [zxing](image/gozxing) [zxing](github.com/makiuchi-d/gozxing) 示例
    - [zxing-qrcode](image/barcode) [zxing](github.com/makiuchi-d/gozxing) 和 [barcode](github.com/boombuler/barcode) 示例
    - [qrcode](image/qrcode) [qrcode](github.com/skip2/go-qrcode) 与上面为不同实现方案

- database
    - [embedded](database/bbolt) [bbolt](https://github.com/etcd-io/bbolt) An embedded key/value database for Go.

- [git](git) [git](github.com/go-git/go-git) git 客户端纯go实现
- [process_daemon_monitor](process_daemon_monitor) 自守护加监控,采用进程树实现.
- [tail](tail) [tail](github.com/hpcloud/tail) or 更新了fork分支的[tail](github.com/nxadm/tail) 类似linux命令tail,可用于日志文件读取.