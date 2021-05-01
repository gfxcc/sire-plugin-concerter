# sire-plugin-concerter
自动转换SIRE插件.

# Warning
**本工具只做了简单的encoding,和后缀处理，不适用于所有的SIRE Plugin**

# Usage

```
» ./sire-plugin-converter -h
usage: sire-plugin-converter [-h] [-f FILE]

SIRE Plugin version converter

optional arguments:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  Path to input file


» ./sire-plugin-converter -f test-data/特技-养寇.sirecm
Converted file is generated: 特技-养寇.scp

» ./sire-plugin-converter -f 特技-养寇.scp
Converted file is generated: 特技-养寇.sirecm
```

# Tested Plugins

- [战场迷雾](http://san11pk.org/categories/1/packages/58)
- 敌军移动范围可视化()