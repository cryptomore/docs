# 如何在本站添加你的文档

## 创建中文文档
- [去这里创建新文件](https://github.com/cryptomore/docs/new/master/zh-cn)，或
- 点击右上角GitHub图标进入文档仓库，进入zh-cn目录后点击Add file->Create new file新建文件
  - 文件名遵循[驼峰命名规范](https://zh.wikipedia.org/zh-tw/%E9%A7%9D%E5%B3%B0%E5%BC%8F%E5%A4%A7%E5%B0%8F%E5%AF%AB)
  - 文件名只能为英文组成
- 使用Markdown语法编辑你的文档内容
  - 使用github.com内嵌Markdown编辑器编辑和预览文档，或
  - 将[文档仓库](https://github.com/cryptomore/docs.git) fork到自己的空间并下载到本地编辑后上传
- 创建pull request将新文档合并到源仓库

## 将文档访问路径添加到导航
- 在zh-cn目录下的_sidebar.md文件添加```- [目录显示名称](zh-cn/你的md文件名)```
- 点击Propose changes->Create pull request提交你的pr请求
- 等待管理员合并你的pr请求

## 创建英文文档
- 在根目录创建你的文档
- 在根目录下的_sidebar.md文件添加英文文档访问路径
- 其他流程与创建中文文档一致

## 修改文档
- 在本站阅览时点击当前文档顶部的EDIT DOCUMENT按钮即可跳转至对应的仓库地址并进行编译操作
- 编辑完成后点击Propose changes->Create pull request提交你的pr请求

## 引用内部文档链接
- 在[内部文档仓库](https://github.com/cryptomore/docs-internal)添加你的文档
- 在本站的_sidebar.md文件添加```- [目录显示名称](内部文档仓库地址)```
