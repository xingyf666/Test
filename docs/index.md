# Welcome to MkDocs

[TOC]

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

![xx](pic/xx.png)

<table border="1">
    <!--标题，居中显示-->
    <caption>学生信息</caption>
    <!--头部-->
    <thead>
        <!--行标签-->
        <tr>
            <!--表头，内容居中，加粗显示-->
            <th>姓名</th>
            <th>性别</th>
            <th>年龄</th>
            <th>民族</th>
            <th>政治面貌</th>
        </tr>
    </thead>
    <!--主体-->
    <tbody>
        <!--行标签-->
        <tr>
            <!--单元格标签-->
            <td>张三</td>
            <td>男</td>
            <td>18</td>
            <td>汉族</td>
            <td>团员</td>
        </tr>
        <tr>
            <!--单元格标签-->
            <td>李四</td>
            <td>女</td>
            <td>16</td>
            <td>满族</td>
            <td>群众</td>
        </tr>
        <tr>
            <!--单元格标签-->
            <td>王五</td>
            <td>男</td>
            <td>19</td>
            <td>回族</td>
            <td>党员</td>
        </tr>
    </tbody>
    <!--脚注-->
    <tfoot>
        <tr>
            <!--单元格标签-->
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>共计：3人</td>
        </tr>
    </tfoot>
</table>