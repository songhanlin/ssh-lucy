### 实现目的

本项目为了实现 ssh 登录的便捷, 希望可以帮助大家

### 需要依赖的项目

1. homebrew
   > 安装其他依赖
2. brew install toilet
   > 使文档颜色美好

### 功能介绍

```
// i 表示init, 用于初始化servers文件
lucy -i

// l表示list, 表示查看列表(不包含密码)
lucy -l

// h表示help, 表示帮助
lucy -h

// s 表示ssh, 也就是平时我们使用的登陆方式
lucy -s 主机名

// p表示password, 展示包含密码的查看列表
lucy -p

// a表示add, 用于向文件新增服务器地址
lucy -a

// f表示find, 用于查找servers的存放路径, 便于批量插入服务器地址
lucy -f


```
