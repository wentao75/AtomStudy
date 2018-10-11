---
ebook:
  title: MD笔记
  authors: 温涛
---

[TOC]

# 基本MD符号

_无序列表_

* 第一个
    * 1.1
* 第二个
* 第三个
    * 3.1

_有序列表_
1. 第一个
    1. 第1.1
    1. 第1.2
1. 第二个
1. 第三个
    1. 第3.1

## 强调

*这会是 斜体 的文字*
_这会是 斜体 的文字_

**这会是 粗体 的文字**
__这会是 粗体 的文字__

_你也可以**组合**这些符号_

~~这个文字将会被横线删除~~

## 图片和链接

Format: `![Alt Text](url)`

![GitHub Logo](https://assets-cdn.github.com/images/modules/logos_page/GitHub-Mark.png)

http://github.com - 自动生成！
[GitHub](http://github.com)

## 引用

正如 Kanye West 所说：

> We're living the future so
> the present is our past.

## 分割线

如下，三个或者更多的

---

连字符

***

星号

___

下划线


## 行内代码
我觉得你应该在这里使用`<addr>` 才对。

## 代码块

```java {.line-numbers}
import java.io.*

public static int main(String[] args){
    System.out.println("hello, world!")
}
```

```python
def foo():
    if not bar:
        return True
```

without syntax highlight

    def foo():
        if not bar:
            return True


## 任务列表

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## 表格

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

_下面使用的**表格扩展**，需要在atom的setting中进行配置才能生效_


colspan `>` or `empty cell`:

| a | b |
|----|----|
|> | 1 |
| 2 ||

|a |b  |
|---|---|
|1  | 2 |
| ^ | 4 |


## 脚注

Content [^1]

[^1]: Hi! 这是一个脚注，他和内容显示在两个位置

# 缩略

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
The HTML specification
is maintained by the W3C.

# 上标

30^th^

# 下标

H~2~O

# 标记

==marked==

## Emoji

:smile: :fa-car: :cry: :satisfied: :grinning: :sleeping: :sunglasses:
:heart: :sheep: :monkey: :thumbsup: :thumbsdown: :sunny: :umbrella:
:+1: :-1: :ok: :ok_hand: :v: :pig: :rabbit:
:dog: :mouse: :cat: :pig: :monkey_face: :horse: :penguin:
:bug: :ring: :hearts: :gem: :house: :school: :hospital: :hotel:
:wc: :clock1: :1st_place_medal:


## 数学

`$...$`或者`(...)`
$f(x)=sin(x) + 1$ 这是一个行内的公式

`$$...$$`或者 `[...]`
$$f(x)=sine(x)+1$$这是段内公式
