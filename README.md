[🇬🇧](README-EN.md)|[🇨🇳](README.md)

## Enso
enso 是固化PSVITA的工具。

按照 molecule 团队的说法，操作不当可能会导致 PSV 变砖，不过目前尚未发现变砖的情况。 

3.60系统 卸载固化，格卡格机就可以升级玩正版系统了。3.65系统卸载固化可能会导致 PSV 变砖，请谨慎卸载。

## Compile

确保你已经安装了最新版的 VITASDK；
确保你已经安装了 python2。

```shell
make # 生成 fat.bin
mv fat.bin installer/res
mkdir build && cd build
cmake .. && make
```
## Usage

* X 键安装固化
* △ 键卸载固化
* □ 键修复启动配置（如果taiHEN未在启动时加载，请选择此选项）
* O 键退出菜单

## TODO
* [ ]  增加对其他语言的支持。

