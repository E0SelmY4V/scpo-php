Don't read Chinese? [README-en.md](README-en.md)

# ScpoPHP

ScpoPHP是一个包含很多有用函数的PHP函数库，主要语言为中文。目前由幻想私社维护。

### 目前包含的功能

- Api: API相关实用函数
- Cache: 缓存相关实用函数
- Db: SQL数据库增删改查实用函数
- Email: PHPMailer实用函数
- Errpage: HTTP错误相关函数
- Rewrite: URL重写对应实用函数
- S2h2b: 字符串、十六进制和二进制之间相互转换的函数

# 如何使用

1. 将git库克隆到本地
2. 复制`config.default.php`为`config.php`
3. 修改`config.php`的配置
4. 在项目中添加代码`require 'scpo-php/xxx.php'`
5. 使用`ScpoPHP\Xxx::function()`来愉快的调用函数
