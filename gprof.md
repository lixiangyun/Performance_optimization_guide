# grof

- 1、添加-pg编译选项
- 2、运行可执行文件
- 3、导出报告
```
gprof ./binary | gprof2dot | dot -Tpng -o binary.png
```

