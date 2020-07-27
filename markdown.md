# Markdown 语法
建议使用 Markdown 浏览器查看

## 字体处理
- *\*斜体\**
- _\_斜体\__
- **\*\*粗体\*\***
- ***\*\*\*加粗斜体\*\*\****

## \#\# 分级标题（这是二级标题，最多6个\#）

## 超链接
- `行内式` \[[GitHub](https://github.com/yzy613)\](https://github.com/yzy613)

- `图片` \!\[![图片](https://img.shields.io/badge/github-yzy613-00acd7)\](https://img.shields.io/badge/github-yzy613-00acd7)

- `参考式` \[[网站][1]\]\[1\]  
`别忘了后面还要写下面这一行`
```
[1]:https://yzyweb.cn
````

- 自动链接 \<<https://yzyi.top>\>


[1]:https://yzyweb.cn

## 列表
### 无序列表
* * *  星号
+ + + 加号
- - - 短横
### 有序列表
1. 第一
2. 第二
3. 第三

## 缩进（也是空格）
- |基准
- &ensp;|\&ensp; 半角空格
- &emsp;|\&emsp; 全角空格

## 引用
> > > \> 右向尖括号。引用可嵌套

## 分割线
- 三个短横
- 三个星号
---

## 代码块
\```golang
```golang
package main
import "fmt"
func main() {
    fmt.Println("Hello Markdown")
    return
}
```
\```
- \``./ddns-client`\`

## 换行
- 一行的最后空两个空格
- \<br />
- 多空一行

## 转义
- \\ 只转义紧跟在 `\` 后的第一个字符

## 表格
|\|时间\||\|事件\||\|备注\||
|:-|:-:|-:|
|\|\:-\||\|:-:\||\|-:\||
|\|2009-11-10\||\|golang 诞生\||\|go go go\||
|\|2020-01-05\||\|加入了 GitHub\||\|hub\||
