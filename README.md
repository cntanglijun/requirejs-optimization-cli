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
rc <path> [options]
```

| 参数 | 必填 | 说明 |
|:-:|:-:|:-:|
| &lt;path&gt; | 是 | 指定 amd 文件 |
| -f &lt;path&gt; | 否 | 输入文件到指定路径 |
| -d &lt;path&gt; | 否 | 输入文件到指定目录 |
| -c &lt;path&gt; | 否 | 指定 amd 配置文件路径 |
| -w | 否 | 监视文件变动 |
| --nocompress | 否 | 不压缩文件 |

## License

MIT