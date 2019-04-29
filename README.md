# 西电本科生学位论文LaTeX模板
***
2018.05.20<br>
更新了封面题目的字体字号与诚信声明书页<br>
目录内去掉“摘要及目录”的方法：<br>
第一次编译thesis-bachelor.tex后，用记事本打开编译生成的thesis-bachelor.toc（目录文件），<br>
将前三行删除并保存，之后重新编译thesis-bachelor.tex即可。<br>
为了方便PDF的文本复制，本次更新重新加入了Adobe字体支持（Adobe Song Std & Adobe Heiti Std），<br>
使用中易字体（SimSun & SimHei）复制会产生乱码，另一种方法可参考Issues中@wenfengand同学的方法。<br>
摘要页及目录页页码的删除与修改，本人用了偷鸡的方法，使用Adobe Acrobat直接编辑PDF文件修改即可。<br>
附一个可直接安装使用的Adobe Acrobat（Windows）<br>
https://pan.baidu.com/s/1Db8AKr3vjhsy2chNsYPi5A password：dbca <br>
***
目前已满足基本需求，可以正常使用，细节待优化；<br>
参考自电子工程学院齐飞老师：[xduthesis](https://github.com/fredqi/xduthesis)；<br>
本模板开发和测试所使用的 TeX 发行版是 texlive ；<br>
需要使用 XeLaTeX 和 xeCJK 宏包（这两个必须安装）；<br>
任何使用本模板造成的格式错误等问题，均由模板使用者个人承担；<br>
使用其他TeX发行版本导致编译失败，耽误时间等问题请模板使用者自己解决；<br>
如编译过程中提示字体缺失，安装相应字体后重新编译即可。<br>

## 模板文件（xduthesis.cls)更新说明
修改了一些显示效果。<br>


## 需要的字体
 - `Adobe Song Std`
 - `Adobe Heiti Std`
 - `Times New Roman`
 - `Arial`
 - `Courier Std`
 - `SimSun`
 - `SimHei`
 - `SimKai`

## 文件说明

模板中的各个文件功能如下：<br>
 - `thesis-bachelor.tex` 本科学位论文主文档<br>
 - `abstract.tex` 摘要<br>
 - `ch01-intro.tex` 模板总体说明//第一章<br>
 - `ch02-options.tex` 模板选项介绍//第二章<br>
 - `ch03-frontmatter.tex` 论文前置部分使用说明//第三章<br>
 - `ch04-mainmatter.tex` 论文主体部分使用说明//第四章<br>
 - `ch05-backmatter.tex` 论文后置部分使用说明//第五章<br>
 - `ch06-conclusions.tex` 参考文献排版指南//第六章，结论<br>
 - `acknowledgments.tex` 致谢<br>
 - `thebibliography.tex` 参考文献<br>
 - `SConstruct` 用于自动编译论文的 scons 脚本<br>
 - `xdulogo.eps` 校徽<br>
 - `xdubadge.eps` 本科学位论文使用的校名图案<br>
 - `xduthesis.cls`&`xduthesis.cfg` 模板文件<br>

