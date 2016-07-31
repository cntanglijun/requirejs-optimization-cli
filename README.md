# requirejs-optimization-cli
[![npm](https://img.shields.io/npm/v/requirejs-optimization-cli.svg?maxAge=2592000?style=flat-square)](https://www.npmjs.com/package/requirejs-optimization-cli)
[![npm](https://img.shields.io/npm/dm/requirejs-optimization-cli.svg?maxAge=2592000?style=flat-square)](https://www.npmjs.com/package/requirejs-optimization-cli)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/cntanglijun/requirejs-optimization-cli/master/LICENSE)

requirejs的amd模块优化工具

## 安装(Installation)

```bash
npm i requirejs-optimization-cli -g
```

## 用法(Usage)

```bash
rc --src <path> --out <path> --config <path>
```

|参数             |说明            |
|:---------------:|:--------------:|
|--src &lt;path&gt;|指定需要优化的文件或目录|
|--output &lt;path&gt;|设置输出路径(默认在指定文件目录下生成对应的xx.min.js)|
|--config|设置指定requirejs配置文件路径|
|--nocompress|不压缩文件|
|--watch|监视文件变动|

## License

MIT