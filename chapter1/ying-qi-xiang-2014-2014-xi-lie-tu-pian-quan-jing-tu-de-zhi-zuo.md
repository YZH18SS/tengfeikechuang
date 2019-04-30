&lt;!--  
 /\* Font Definitions \*/  
 @font-face  
	{font-family:"Cambria Math";  
	panose-1:2 4 5 3 5 4 6 3 2 4;  
	mso-font-charset:0;  
	mso-generic-font-family:roman;  
	mso-font-pitch:variable;  
	mso-font-signature:3 0 0 0 1 0;}  
@font-face  
	{font-family:等线;  
	panose-1:2 1 6 0 3 1 1 1 1 1;  
	mso-font-alt:DengXian;  
	mso-font-charset:134;  
	mso-generic-font-family:auto;  
	mso-font-pitch:variable;  
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
@font-face  
	{font-family:"等线 Light";  
	panose-1:2 1 6 0 3 1 1 1 1 1;  
	mso-font-charset:134;  
	mso-generic-font-family:auto;  
	mso-font-pitch:variable;  
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
@font-face  
	{font-family:"\@等线 Light";  
	mso-font-charset:134;  
	mso-generic-font-family:auto;  
	mso-font-pitch:variable;  
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
@font-face  
	{font-family:"\@等线";  
	panose-1:2 1 6 0 3 1 1 1 1 1;  
	mso-font-charset:134;  
	mso-generic-font-family:auto;  
	mso-font-pitch:variable;  
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
 /\* Style Definitions \*/  
 p.MsoNormal, li.MsoNormal, div.MsoNormal  
	{mso-style-unhide:no;  
	mso-style-qformat:yes;  
	mso-style-parent:"";  
	margin:0cm;  
	margin-bottom:.0001pt;  
	text-align:justify;  
	text-justify:inter-ideograph;  
	mso-pagination:none;  
	font-size:10.5pt;  
	mso-bidi-font-size:11.0pt;  
	font-family:等线;  
	mso-ascii-font-family:等线;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:等线;  
	mso-fareast-theme-font:minor-fareast;  
	mso-hansi-font-family:等线;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;  
	mso-font-kerning:1.0pt;}  
h2  
	{mso-style-priority:9;  
	mso-style-qformat:yes;  
	mso-style-link:"标题 2 字符";  
	mso-style-next:正文;  
	margin-top:13.0pt;  
	margin-right:0cm;  
	margin-bottom:13.0pt;  
	margin-left:0cm;  
	text-align:justify;  
	text-justify:inter-ideograph;  
	line-height:173%;  
	mso-pagination:lines-together;  
	page-break-after:avoid;  
	mso-outline-level:2;  
	font-size:16.0pt;  
	font-family:"等线 Light";  
	mso-ascii-font-family:"等线 Light";  
	mso-ascii-theme-font:major-latin;  
	mso-fareast-font-family:"等线 Light";  
	mso-fareast-theme-font:major-fareast;  
	mso-hansi-font-family:"等线 Light";  
	mso-hansi-theme-font:major-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:major-bidi;  
	mso-font-kerning:1.0pt;}  
a:link, span.MsoHyperlink  
	{mso-style-priority:99;  
	color:\#0563C1;  
	mso-themecolor:hyperlink;  
	text-decoration:underline;  
	text-underline:single;}  
a:visited, span.MsoHyperlinkFollowed  
	{mso-style-noshow:yes;  
	mso-style-priority:99;  
	color:\#954F72;  
	mso-themecolor:followedhyperlink;  
	text-decoration:underline;  
	text-underline:single;}  
span.2  
	{mso-style-name:"标题 2 字符";  
	mso-style-priority:9;  
	mso-style-unhide:no;  
	mso-style-locked:yes;  
	mso-style-link:"标题 2";  
	mso-ansi-font-size:16.0pt;  
	mso-bidi-font-size:16.0pt;  
	font-family:"等线 Light";  
	mso-ascii-font-family:"等线 Light";  
	mso-ascii-theme-font:major-latin;  
	mso-fareast-font-family:"等线 Light";  
	mso-fareast-theme-font:major-fareast;  
	mso-hansi-font-family:"等线 Light";  
	mso-hansi-theme-font:major-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:major-bidi;  
	font-weight:bold;}  
.MsoChpDefault  
	{mso-style-type:export-only;  
	mso-default-props:yes;  
	font-family:等线;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;}  
 /\* Page Definitions \*/  
 @page  
	{mso-page-border-surround-header:no;  
	mso-page-border-surround-footer:no;}  
@page WordSection1  
	{size:595.3pt 841.9pt;  
	margin:72.0pt 90.0pt 72.0pt 90.0pt;  
	mso-header-margin:42.55pt;  
	mso-footer-margin:49.6pt;  
	mso-paper-source:0;  
	layout-grid:15.6pt;}  
div.WordSection1  
	{page:WordSection1;}  
--&gt;  


## 一、

一开始做这个任务的时候想的是能不能单靠java实现全景图的制作，为此需要解决的问题主要有两个：

一是两张图片的任意拼接，即拼接位置的任意性；

二是获取像素值以进行复数图片的定位，即如何将大块像素相同的区域重合到一起,从而使系列图片能组合成一个整体

第一个问题的解决需要创建**Graphics**对象和建立**BufferedImage**，核心是createGraphics\(\)和drawImage\(\)，如此可将图片并到一起。第二个问题同样涉及**Graphics**对象和**BufferedImage**，可以通过getRgb\(\)获取图片各个像素的值再移位运算将rbg转为数字。但是一张图片中有很多像素值重复的区块，并且代码在运行过程中总是出现莫名其妙的问题，因此这个纯理论的想法没能实现。

## 二、

后来开始学习使用opencv，因为opencv开发大多使用c++\(其实我对c/c++和java的区别没有具体了解\)。用stitch类就很容易实现图片的拼接。现在还在学习java上的opencv使用

附上教程网站：[https://blog.csdn.net/haikuotiankong7?t=1](https://blog.csdn.net/haikuotiankong7?t=1)

https://blog.csdn.net/luckyfairy17/article/details/81239356

