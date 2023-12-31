# 什么是HTML?

**HTML(HyperText Markup Language)** - 超文本标记语言, 是一种用于构建网页及其内容的代码, [参考](./01-什么是HTML.html)

## HTML的基本骨架

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML的基本骨架</title>
</head>

<body>

</body>

</html>
```

### vscode 中自动生成骨架

1. 新建HTML文件
2. 在英文状态下, 输入一个**!**
3. 按**Tab**键即可自动生成HTML的基本骨架

### HTML骨架分析

```html
<!-- 用于声明文档的类型 -->
<!DOCTYPE html>
<!-- 该元素包含页面上的所有内容, 也被称为根元素 -->
<!-- lang="en" 用于告诉浏览器当前页面的主要语言 -->
<html lang="en">

<head>
  <!-- 设置当前HTML应使用的字符集 -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- 设置文档的标题, 会显示在浏览器的Tab上 -->
  <title>HTML结构分析</title>
</head>

<body>
<!-- 包含我们希望网络用户在访问页面时向其显示的所有内容 -->
</body>

</html>
```

## 标题

标题标签一共有6个等级：h1 - h6, 其字体大小会随着标题等级的提升而减小, 并且所有的标题都会加粗

```html
<h1>1级标题</h1>
```

**如何使用emmet快速生成HTML代码**

```html
<!-- h$*6>{$级标题} + Tab -->
```

## 段落

在HTML中使用`<p>`定义段落, 浏览器会自动地在段落标签前后添加空行

**需要注意的是**

1. HTML中的连续空格或者空行, 浏览器会自动删除这些多余的空格/空行, 即默认为一个空格
2. 强制换行：`<br />`

