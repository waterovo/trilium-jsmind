# README
trilium-jsmind
--------------

![](README_image.png)

在trilium创建jsmind思维导图，可以编辑并实时保存 （Trilium 0.63.5）

### 如何安装

1.  导入笔记，取消勾选安全导入选项（如果您不熟悉trilium的小部件，请谨慎操作）
2.  检查下列笔记是否已经添加标签（默认已经添加）
    1.  TriliumJsmindWidget笔记添加 `#widget` 标签
    2.  template添加 `#jsMindWidgetTemplate` 标签
    3.  css和jsmind.css添加 `#jsMindWidgetCss` 标签
    4.  jsMind笔记添加 `#template` 标签
3.  开始使用

### 使用说明

#### 如何创建jsMind笔记

![](1_README_image.png)

如何进行图像引用

因trilium的api限制，本插件通过创建一个图像笔记间接实现图像引用。

![](2_README_image.png)

点击【Save image note】，会在jsMind笔记下生成一个jsMind-export图像子笔记。

![](3_README_image.png)

复制引用，插入到其他笔记。

![](4_README_image.png)

更新完思维导图后，点击【Save image note】会更新jsMind-export图像子笔记，可以看到其他笔记内的引用也更新了。

### 正在实现的功能

> 或者待修复的bug

- [x] 图像引用
- [x] ~全屏显示~（准确的说是隐藏编辑框）
- [x] 记录jsMind主题颜色
- [x] 渲染更改为显示在笔记右侧
- [x] ~更详细的说明~（已经去除繁琐的操作）

### 版本历史

**v1.1.0（当前版本）**

渲染更改为显示在笔记右侧，更加适配trilium的操作逻辑；无需再配置笔记ID；生成图像子笔记，间接实现图像引用。

**v1.0.0**

验证版本，能够渲染和编辑jsmind。
