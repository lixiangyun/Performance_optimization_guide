# Valgrind

## 安装方法

- 1、先从http://valgrind.org/上将安装包
- 2、./configure && make -j && make install

## 使用方法
```
valgrind --tool=callgrind --separate-threads=yes ./demo
```

## 导出图
```
gprof2dot -f callgrind callgrind.out.xxx |dot -Tpng -o report.png
```

工具安装：[gprof2dot](gprof2dot.md)
