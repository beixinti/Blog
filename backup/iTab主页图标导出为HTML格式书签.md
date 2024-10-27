## 1. 所需工具：

• VSCode

• Excel

• World

## 导出步骤

### 删除iTab自带小部件

如图所示iTab自的小部件，所有点开是弹窗而不是直接跳转网页的图标，全部都需要删除。

此步骤可能会遗漏了一些小部件，没关系，后面逐个排除即可。

![5a451cd74e3eb1a4fd329f39aba96f5fe8a99a6d](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024097.jpeg)

### 导出iTab备份数据

![f70d8ae5b1aa94b895d21ac6719f2ee5b3362860](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024098.jpeg)

### 美化代码

1. 将导出的iTab备份-\*\*\*\*-\*\*-\*\* \*\*\_\*\*.itabdata用VSCode打开!

2. 复制全部内容，并粘贴到代码美化网站，点击格式化

3. 复制内容，返回VSCode，Ctrl+N新建文件，把代码粘贴进去（文件名为Untitled-1）

### 提取图标名称和网址

1. 点击左侧搜索，搜索 name

2. 右键任意结果点击"全部复制"

![721daa29276390aaedc02d7b4857dc2dbd79573d](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024099.jpeg)

3. Ctrl+N新建一个文件，把结果粘贴进去（文件名为Untitled-2）

4.
回到先前的Untitled-1，和刚刚一样搜索url并右键任意结果点击"全部复制"，Ctrl+N新建一个文件，把结果粘贴进去（文件名为\`Untitled-3）

5. 关闭Untitled-1文件

6. 打开Untitled-2，如图所示逐行删除侧边栏分类名称，一般名为\*\*\*.4:\"\*\*\"且缩进较短。

此步骤可能会遗漏了一些，后面逐个排除即可。

![87d99c85646880d239f7452e58e75e38ce632df8](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024101.jpeg)

如图所示进行操作

![fa51462a6d7efc386bf7b309546738264c0fbe17](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024102.jpeg)

删去一个点，选中剩下的进行替换

![8b805ff3723801bf201ed4c5f7ebcfb76208f696](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024103.jpeg)

最后的,\"也同样使用搜索并替换的方法去除

![8956e8bfc6bf1b3f7f4810cd4a9b8f63a2cb0a5b](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024104.jpeg)

另外一个Untitled-3中的url也用同样的办法替换掉

## 提取成果演示

![45b944dd291185741247f903e956b7bff4aa097b](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024105.jpeg)

![87d99c85646880d239f7452e58e75e38ce632df8](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024101.jpeg)

## 制作HTML格式书签

1. 新建 Excel 表格文档

2. 在A1写上"标题"，第B1写上"网址"

如图，将在VScode中提取出来的标题和网址填入，并调整列宽（可选）

![578a20a2667e8a5248eb553d56a3684191f3e809](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024106.jpeg)

查看最后一个标题与网址是否对应，若标题多出几个，检查从哪里开始不对应并把多余出来的标题删去，直到每个标题对应正确的网址。

![8302bf8e7ae0b44e0bf37ca92126e7484b426509](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024107.jpeg)

3. 保存 Excel 文档

4. 新建 Word 文档，复制下面面代码到word

\<DT\>\<A HREF=\"网址\"\>网站标题\</A\>

点击邮件选项卡\>选择收件人\>使用现有的列表

选择刚才做的Excel表格

![9fe6a313a54acaca265af489d15d7391f7ad92c6](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024108.jpeg)

5. 选中网址，点击插入合并域。选选择http网址

选中网站标题，点击插入合并域。选选择网站名称

http网址和网站名称的两名带有书名号就标识成功了

![a5085d289dadd482fb4bb84541f0fb071664f8c1](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024109.jpeg)

6. 点击完成合并\>编辑单个文档\>全部，点击确定

这样Excel表中的数据就被导入到word来了

![1250d6ed1a412d1f0085cd1e8ceac6c4bd830e46](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024110.jpeg)

7. 按Ctrl+A全选整个word文档，然后Ctrl+C复制

回到VSCode，Ctrl+N新建文档，Ctrl+V复制

最后保存即可

![5c6f823a1427824b77c01101cf6b34ec51b808ac](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024111.jpeg)

## 完成

![43bb902cfc9efa74d7cd562981bd251c8ccb4ef2](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202408010024112.jpeg)

**可直接导入浏览器**

感谢

• 知乎@dsaaa

提供批量从文本中导入书签到浏览器思路
