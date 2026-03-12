# Manager-of-Danbooru-Artists
Localize, store, and manage prompts of artists

# UI 介绍

# UI Introduction

<img width="895" height="528" alt="e4472d3cdce79008457e9e9df307f64b" src="https://github.com/user-attachments/assets/c0906ba9-6f95-4c38-927f-89eaa38f2d0e" />

在上方，设置界面，选择图片数据的来源文件夹，其中png文件的名称应该为(.+)_\d{5}_\.png（前面为画师名），以及选择本程序的资源储存目录（建议单独建一个文件夹），还有ui界面的调节也在这个面板。

At the top, the settings interface, select the source folder of the image data, where the name of the png file should be (.+)_d{5}_.png (The preceding part is the artist's name), and select the resource storage directory of this program (it is recommended to create a separate folder), and the adjustment of the UI interface is also in this panel.

<img width="2560" height="1374" alt="17ca9eed07150af6fba238c4edbe0f59" src="https://github.com/user-attachments/assets/0f8cc778-e56d-4699-9fa4-66b1fbd70c37" />

在导入图片数据后，左侧为画师列表；中间上部为画师名下的不同画作与备注，中部为预览图，下部为加入对比的图片信息；右侧上部为已选画师清单，中部为常用画师串的选择，下部为画师串导出或导入的文本框。

After importing image data, the left side shows the list of artists; the upper middle shows different artworks and notes under each artist's name, the middle shows preview images, and the lower middle shows the information of images added for comparison; the upper right shows the list of selected artists, the middle right shows the selection of frequently used artist strings, and the lower right is the text box for exporting or importing artist strings.

# 附录 1：在正式开始之前的建议流程

# Appendix 1: Recommended procedure before officially starting

comfyui固定提示词、参数与随机种子生成以画师名开头的png文件，然后装一个文件夹作为来源文件夹。

ComfyUI fixed prompts, parameters, and random seed generate PNG files starting with the artist's name, then set up a folder as the source folder.

使用时先设置好数据库文件夹在那里，这样才能保存数据。（ui大小、画师目录、图片数据等）

When using, first set the database folder location, so that data can be saved (UI size, artist directory, image data, etc.).

# 功能一：
# Function 1:
上下键，快速浏览画师的首张图片，双击画师名，添加到右侧画师串。

Up and down keys, quickly browse the artist's first image, double-click the artist's name to add it to the artist chain on the right.

# 功能二：
# Function 2:
<img width="1305" height="1376" alt="image" src="https://github.com/user-attachments/assets/30988fbb-1799-4427-b9e2-4b9d22d5e18c" />

双击图片名，查看原图。

Double-click the image name to view the original picture.

# 功能三：
# Function 3:
<img width="1794" height="1213" alt="7b08962ed0f4c500854fb99f418aef45" src="https://github.com/user-attachments/assets/0fcd90f5-9e08-43d9-99fb-17546c3a6ae3" />

添加图片加入对比栏，并查看对比图。注意，左上方的删除选中图片是从数据库中删除，右下角的清空才是清空对比栏。

Add images to the comparison bar and view the comparison images. Note that deleting a selected image in the upper left corner removes it from the database, while the clear button in the lower right corner only clears the comparison bar.

# 功能四：
# Function 4:
在预览图上方，你可以自由书写备注信息。

Above the preview image, you can freely write remark information.

# 功能五：
# Function 5:
<img width="445" height="1310" alt="51b93349a880ecdbd16f9a591cfb00a1" src="https://github.com/user-attachments/assets/40f67713-136e-4476-ac28-3ee2e22e7d4f" />

双击画师栏中的画师可以修改权重。中间部分可以保存当前的画师组合为一个常用画师串进行记录，或者选择常用画师组合进行导入。下方可以复制整理好的画师串，也可以输入同格式的画师串进行解析。

Double-clicking an artist in the artist panel allows you to modify the weight. The middle section lets you save the current artist combination as a commonly used artist string for record-keeping, or select a commonly used artist combination for import. The lower section allows you to copy the organized artist string, or enter an artist string in the same format for parsing.

<img width="425" height="161" alt="26a52c7086c0a013665112611cb4107c" src="https://github.com/user-attachments/assets/d79716f2-6e85-4509-b96f-544ffe4ad9a9" />

解析下部的画师串后，如果有数据库中没有的画师名，会显示为红色（注意，也可能仅仅是书写格式与数据库中的画师不同，比如下划线还是空格）

After parsing the list of artists below, if there are artist names not in the database, they will be shown in red (note, it may also be just a difference in how the name is written compared to the database, such as underscores versus spaces).

# 功能六：
# Function 6:
<img width="354" height="60" alt="4227a70999e0d6e28c6b3200bcb3b394" src="https://github.com/user-attachments/assets/0f401ccc-c97c-479a-ad6f-4cfd25f9c935" />

第二个按钮，检测数据库中，同一画师名下是否有相同的图片，如果有，可以选择删除多余的图片，仅保留一张。

The second button checks whether there are duplicate images under the same artist's name in the database. If there are, you can choose to delete the redundant images, keeping only one.


附录 2：各按键的翻译

Appendix 2: Translations of Each Key

估计没什么人看这个软件，就先省略了。

I guess not many people will look at this software, so I'll skip it for now.
