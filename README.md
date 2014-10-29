
# 农历事件生成器

lunar-calendar 可以自动生成按农历重复的事件，并导出 iCal 文件。

## 安装

```
$ npm install lcal -g
```

## 用法

```
$ lcal data.md
```

data.md:

```markdown
- 1980/10/04+100Y 张三的农历生日
- 1982/8/15+100Y 李四的农历生日
```

默认生成 data.ics 文件，包含了张三（农历一九八〇年十月初四日）和李四（农历一九八二年八月十五日）的 100年的农历生日事件，
导入到 Google Calendar 或 Mac Calendar.app 等即可。

## 导入

* [参考文档](https://github.com/hotoo/lcal/wiki#%E5%AF%BC%E5%85%A5)
