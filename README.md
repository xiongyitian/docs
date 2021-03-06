# docs
Yunba Documentation

## 文档风格

- 文档采用 Github 兼容 Markdown 格式编写，后渲染到官网上。
- 中文文档中如果出现英文、数字、超链接或某些特殊字符的文本时，需要在文本两侧加上空格进行分隔。遇到标点符号时可省略空格。如果必须对文本使用引号，需要使用中文的引号。例如：在 WampServer 解压后的 “...\wamp\bin\php” 路径下搜索 php.init 文件；Yunba 的 Android/iOS 消息推送；保留 50 条。
- Github Markdown 的中文引号始终显示为半角引号，在使用引号后，引号外侧需再加个空格。同样地，遇到标点符号时可空格省略。（参考上面的例子）
- 中文文档，一律使用中文标点符号。夹杂英文或其他非中文字符时，尽量只在字符外侧使用空格进行分隔，不使用引号。
- 专用名词统一。特别是中英文翻译，使用统一的对照表。
- API 输入参数使用表格描述。
- 文档的图片使用 Github URL：https://raw.githubusercontent.com/yunba/docs/master/image/xxx.png
- 提到某个函数时，用：`函数名`。例如，`subscribe()`。
- 不便透露的内容，用大写的 X 表示。例如，appkey:"XXXXXX"。
- 注意事项另起一行，这样写：**注**：XXXX。
- 文档标题为 # 级别，以此类推。
- 需要用到序号时，使用：1. 1.1 1.2 样式。
- 添加代码的首行统一顶格，其余行则遵守代码格式。

## 渲染后效果问题
- 换行：Github Markdown（简称 GM）支持 br 换行，但云巴网页（简称 YB）渲染后不支持。（GM 一次换行无效果，两次换行最终效果是一次换行。）
- 标题字号：GM 上 #### 级的字，在 YB 上比普通正文字体还要小。因此，约定 GM 上最多使用 ### 级，再往下，采用双星号加粗表示标题。还可以使用 1. 1.1 样式。
- GM 上使用单个大于号所引导的内容，在 GM 上显示为灰色背景的深灰色字，而在 YB 上渲染后为红色字、有缩进且带大边框，不建议使用。

## 文档文件名命名规则

- 文档的文件名由模块名、文档类型组成。
- 文件名各个部分用 "_" 连接。

例如：Android_QuickStart.md
