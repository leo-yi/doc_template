## 说明
这是一个 docsify 驱动的文档模版

## 使用方法

1. 安装 docsify
    
    自行到官网查看
    [docsify.js.org](https://docsify.js.org/#/zh-cn/)

2. 克隆项目

    ``` sh
    git clone git@github.com:leo-yi/doc_template.git
    ```

3. 驱动

    ``` sh
    docsify serv doc_template/
    ```

### 自定义 title 和 侧边栏文案

自行修改 index.html 的内容

### 写文档

只需要添加 markdown 文件，并且在 _sidebar.md 文件中添加对应关系即 

###### 1. 强调内容

``` markdown
!> 一段重要的内容，可以和其他 **Markdown** 语法混用。
```

!> 一段重要的内容，可以和其他 **Markdown** 语法混用。

###### 2. 普通提示

``` markdown
?> _TODO_ 完善示例
```

?> _TODO_ 完善示例