# DWM教学仓库

本文档关联bilibili up [称呼我C先生](https://space.bilibili.com/303522232) 的dwm相关教学视频

尽量做到每一期视频对应一个commit

## COMMIT

1. 初始化 & 文档初始化
2. 添加新布局
3. 配置新窗口在栈的头部还是底部

## DOC

### 项目结构

```plaintext
.
├── config.h       -- 配置文件入口
├── config.mk      -- make相关的配置 一般不需要更改
├── dwm.c          -- 具体业务逻辑
├── drw.c          -- 和draw绘制相关的一些实现
├── drw.h          -- 和draw绘制相关的一些头
├── dwm.png        -- 图标
├── LICENSE        -- 版本说明等
├── Makefile       -- makefile
├── README.md      -- 项目说明文件
├── transient.c    -- 工具类
├── util.c         -- 工具类
└── util.h         -- 工具类
```
