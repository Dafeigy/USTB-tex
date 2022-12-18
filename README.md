

<h1 align="center"><color='blue'>USTB-Tex</color></h1>
<p align="center">
    <color='gray'>A Latex Template for USTB report</color>
</p>
<p align="center">
    <a href="">
        <img src="https://img.shields.io/badge/Platform-Windows-blue.svg" alt="Platform">
    </a>
    <a href="">
        <img src="https://img.shields.io/badge/Version-0.1-red.svg" alt="Version">
    </a>
    <a href="https://github.com/Dafeigy">
        <img src="https://img.shields.io/badge/Readme-Clickhere-yellow.svg" alt="README">
    </a>
    <a href="mailto:@1070642765@qq.com">
        <img src="https://img.shields.io/badge/Email-Homepage-brightgreen.svg" alt="Contact">
    </a><p align="center">
    <a href="">
        <img src="https://img.shields.io/badge/Build-passing-purple.svg" alt="Build">
    </a>
    <a href="">
        <img src="https://img.shields.io/badge/Support-Pytorch-orange.svg" alt="Support">
    </a>
    <a href="">
        <img src="https://img.shields.io/badge/License-GLWT-critical.svg" alt="License">
    </a>
</p>

## Feature

🌟单栏排版，应付大部分课程需要，自动生成目录页码；

🌟图片、引用、参考文献、超链、公式、普通表格、跨页表格均有demo（当然都很丑）；

🌟超高自由度的组件修改，包含页眉、页脚、；

🌟支持中日英三语书写、代码书写，其他功能可用自定义包扩展。

<center>
    <img src = 'https://s2.loli.net/2022/12/18/Nhxzd34VsH5WycX.png' style="zoom:50%;">
    <img src="https://s2.loli.net/2022/12/18/b3f1MXUdRkTZW8y.png"  style="zoom:50%;">
    <img src = 'https://s2.loli.net/2022/12/18/Wxrwiae5lAdhX9N.png' style="zoom:50%;">

​    

## Usage

* 封面信息修改：

  更改`preface/cover.tex`。预定义的信息可直接修改，如果需要配合封面信息的话需要自定义宏变量。

* 封面格式修改：

  更改`setup/format.tex`中的`makecover`函数，~~不会的话那我也帮不了你。~~

* 包拓展：

  修改`setup/package.tex`即可，导入需要的包：`\usepackage{xxx}`

* 文体格式修改：

  更改`setup/format.tex`中各种定义，可以照着给的例子自行修改。自定义字体需要自行放入`font`文件夹。
  
* 参考文献修改：

  在`references\reference.bib`中添加Bibtex信息。
  
* 图片修改：

  将图片文件放入`figures`文件夹。
  
* 复杂表格可使用[Create LaTeX tables online – TablesGenerator.com](https://www.tablesgenerator.com/#)完成。

## Acknowledgment

本模板是根据天津大学的本科毕业论文LaTex模板修改而成（虽然我也不明白为啥最后跟我说模板有问题，笑嘻了），该模板系由天津大学2010级管理与经济学部信息管理与信息系统专业硕士生@[张井](mailto:prayever@gmail.com) 和 天津大学2008级精密仪器与光电子工程学院测控技术与仪器专业本科生@[余蓝涛](mailto:lantaoyu1991@gmail.com)提供，并由苯人修改而成。