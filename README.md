# FBReaderJ

1.Android studio版本环境

# 针对这个项目的简单说明

1.去除了原有的网络模块，如果需要网络，可以自己添加

2.去除了本地书库和网络书库

3.针对设置界面做了简化

4.阅读背景的替换

5.项目中针对关键的地方加入大量的log 输出

6.后续会继续优化。

在MainActivity 中的数据源，需要修改为你自己数据

```
  // 雍正皇帝.epub 这个需要改为自己的epub 图书
 File file = new File(Environment.getExternalStorageDirectory().getPath() + "/雍正皇帝.epub");
```

