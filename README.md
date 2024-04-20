# Trilium-jsmind
![image](https://github.com/waterovo/Trilium-jsmind/assets/61768530/0df428b3-1562-4670-9fb9-fbda110541cb)

在trilium创建jsmind思维导图，可以编辑并实时保存
（Trilium 0.63.5）
## 如何安装
1. 导入笔记，取消勾选安全导入选项
2. 修改config
- JM_CANVAS_NOTE_ID 渲染笔记trilium-jsmind笔记的ID；
- JM_DIR_NOTE_ID 新建jsmind笔记存放的目录（自己新建一个笔记，然后复制笔记ID填入该参数）；
- JM_SAMPLE_NOTE_ID sample笔记的ID；
- JM_TPL_NOTE_ID 模板目录下的jsMind-intro笔记的ID；
- cssNoteIdList jsmind.css和css笔记的ID。
3. 修改trilium-jsmind笔记的jmNote关系，指向sample笔记
4. JmNoteOpenWidget添加#widget标签（可选）
  
![image](https://github.com/waterovo/Trilium-jsmind/assets/61768530/52df0a07-6422-43ab-8121-514b341cb2d2)
