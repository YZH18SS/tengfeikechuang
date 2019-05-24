## 一、为什么使用GitBook？

GitBook是使用GitHub / Git和Markdown（或AsciiDoc）构建漂亮书籍的命令行工具（和Node.js库）。

GitBook可以将您的内容作为网站（可定制和可扩展）或电子书（PDF，ePub或Mobi）输出。

我们将通过Github来进行这本电子书的版本管理，如何使用Github，大家已经会了，在此不加赘述，阅读至此你可以先将这个仓库同步到本地，监测我的仓库，并与自己的远程仓库相关联。当你将更改后的电子书上传到你的GIthub仓库后，可以向我发送合并请求，待我同意后，所有人就都可以更新自己的仓库。

GitBook.com是使用GitBook格式创建和托管图书的在线平台。它提供托管，协作功能和易于使用的编辑器。但是使GitBook.com官网需要翻墙才能登陆注册，如果使用它，那么大家就只能在联通校园网的情况下编辑这本电子书，考虑到大家的不同情况，只能稍微牺牲一点大家的方便程度了。所以我们可以使用Gitbook editor来进行编辑。在此之前我们可以先下载Gitbook。这里有个安装链接：

[https://www.cnblogs.com/kingsonfu/p/10255123.html](https://www.cnblogs.com/kingsonfu/p/10255123.html)

### 注意！

这里我们是使用已有的电子书，所以无需按照文章所述创建新的电子书，安装即可，接下来将介绍如何使用GitBook Editor来编辑我们的开发手册。

## 二、如何使用Gitbook editor?

1. 点开之后不要登陆，因为我们一开始就是打算绕开Gitbook官网的。直接点击Do that later，开始使用。

2. 点击左上方Gitbook Editor 菜单，选择open，然后在你的电脑上选择你同步到本地的那个仓库。

3. 现在你可以开始编辑了，这里是一个参考链接：[https://www.crifan.com/try\_gitbook\_editor\_edit\_markdown\_post/](https://www.crifan.com/try_gitbook_editor_edit_markdown_post/)

4. 你可以事先了解一下markdown语法，以便更熟练地编辑。

5. 点击左上方Book菜单中的Repository Settings 设置你的上传仓库（注意是你自己的Github仓库），编辑完之后点击右上方save保存，然后点击publish就可以上传到你的Github上了。

### 注意！

编辑时如果要换行注意使用ctrl + 回车，否则会进入编码模式。也不要使用空格来进行首行缩进，不然也会导致同样的问题。



## 三、题外话

1. 在使用过程中如有其他问题，待解决后，请在《操作指南》章节下新增文章，描述你所遇到的问题，并附上解决方案，并且署名，如因我考虑不周给你造成麻烦请接受我真挚的道歉。另关于这一部分内容有想补充的东西也可以以相同方法进行增补。
2. 还记得安装git book时使用的npm以及node.js吗？他们其实是JavaScript开发工具，目前js生态环境相当成熟，你可以使用他们来下载已有的js工具包，进行js开发。如果只是用他们下载完git book后就弃之不用，未免有些明珠暗投的遗憾了。据我所知，我们班有位大佬决定采用js来进行web的后端开发，他使用的包就是通过这种途径下载下来的。



