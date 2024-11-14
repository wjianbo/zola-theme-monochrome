# zola-theme-monochrome
A chinese friendly zola theme.

Demo 页面还没有做，效果参考[作者博客](https://wjianbo.github.io)。

## 安装

确保使用 `zola init myblog` 创建了你的 zola 博客文件夹，然后将本主题添加到本地 `themes` 文件下：

```
git submodule add https://github.com/wjianbo/zola-theme-monochrome themes/monochrome
```

或者

```
git clone https://github.com/wjianbo/zola-theme-monochrome themes/monochrome
```

之后修改 `config.toml` 文件：

```
theme = "monochrome"
default_language = "zh-CN"
build_search_index = false
```