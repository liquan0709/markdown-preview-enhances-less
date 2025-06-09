# markdown-preview-enhances-less

## Todo List

- [x] 1. 字体
- [ ] 2. 主题颜色
  - [ ] light
  - [ ] dark
  - [ ] print
- [x] 3. 主体设计
- [x] 4. 标题、目录和侧边栏

## 说明文件

### 变量定义

后缀为`_variables`的文件，包含了大多数`less`文件的全局变量，命名格式为`作用域_属性`，如：`title_bg_color`表示标题文件的背景颜色。

### 字体

字体文件来源于`https://fonts.zeoseven.com`，包含大量的免费商用字体。字体设计为五个层次：标题字体、正文字体、代码字体、公式字体和注释说名字体。标题字体建议选择黑体或圆体，正文选择宋体或者仿宋，注释说名字体以楷体（上图中观体）为主。代码字体选择等宽字体（`Fira Code` 和 `LXGW WenKai Mono G` ），公式字体为`Libertinus Math`。

