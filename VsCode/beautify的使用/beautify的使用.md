### Beautify 插件使用

-----
参考文章：
https://zhuanlan.zhihu.com/p/131274632

https://github.com/HookyQR/VSCodeBeautify/blob/master/Settings.md

-----
##### 一、安装&使用初衷

###### 使用初衷
ESLint使我心态爆炸，寻求代码规范和人性化操作的平衡点

###### 安装

商店搜索 Beautify 最高下载量那个就是了

-----
##### 二、简单介绍

- Beautify是格式化代码的插件
- 可格式化 JS、JSON、CSS、Sass、HTML（其他类型的文件不行）
- 在文件夹根目录下创建 **.jsbeautifyrc** 文件配置后可用
- 
-----
##### 三、配置规则

###### 适合所有文件类型的规则
|   设置   | 适用 | 描述 |
| ---- | ---- | ---- |
| indent_size | 所有 | [int]缩进大小，默认：4 |
| indent_char | 所有 | [String] 缩进字符，默认：" " |
| eol | 所有 | [String] 行结束符，默认："\n" |
| end_with_newline | 所有 | [Bool] 确保最后一行是新行，默认：false |
| indent_with_tabs | 所有 | [Bool] 用Tab缩进，会覆盖 indent_size 和 indent_char，默认：false |
| preserve_newlines | 所有 | [Bool] 留原有的多余空行，默认：true |

~~~javascript
{
  "indent_char": " ",
  "indent_size": 0,
  "eol": "\n",
  "end_with_newline": false,
  "indent_with_tabs": false,
  "preserve_newlines": true
}
~~~



- **运行方法 Shift+Alt+F （可自定义）**