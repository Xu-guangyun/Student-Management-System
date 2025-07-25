# Student-Management-System
![GitHub stars](https://img.shields.io/github/stars/Xu-guangyun/Student-Management-System) 

## 简介

本程序使用ISO C++14 标准，基于MFC框架编写。用于管理学生信息，支持读取，添加，删除，修改，查找，保存等功能（读取本地txt文件，保存到原路径）

## 技术依赖

1.IDE 及工具链：Microsoft Visual Studio 2022（需安装“使用 C++ 的桌面开发”工作负载）

2.编译器与生成工具：MSVC v143 生成工具（Visual Studio 2022 对应的最新 C++ 工具集，包含在上述工作负载中）

3.MFC 组件：适用于 v143 生成工具的 C++ MFC 库（可在 Visual Studio 安装器的“单个组件”中勾选“适用于最新v143生成工具的C++MFC（x86和x64）”）

## 使用步骤

1.点击Code，再点击Download ZIP，下载本仓库的压缩包。

2.找到该压缩包并解压，找到Student Management System Setup.exe，此为程序的安装程序。

3.运行安装程序，默认安装路径为C:\Program Files\Student Management System，可自行更改。

4.安装完成后，运行程序Student Management System.exe，可使用根目录中的 学生信息.txt（范本）进行测试。

5.如果要卸载该程序，请运行unins000.exe，确定卸载。

## 功能介绍

1.打开：可从本地导入用于存储学生信息的txt文件，注意格式，第一行只有一个数字用于记录学生数量，下面一行记录一个学生的信息，格式是：学号 学院 班级 姓名 性别。格式错误会导致打开失败。

2.增加：增加功能使用前需成功完成打开操作。添加学生的各项信息不能有空缺，且学号不能与已有学生重复。

3.删除：先选中一个学生，再点击删除，点击确定。

4.修改：先选中一个学生，再点击修改，该学生各项信息会自动填充在修改界面，选择要修改的部分修改，注意学号不能修改。

5.查找：输入学生的学号，点击查找即可完成索引。

6.保存：点击保存，跳出保存成功提示即完成保存。

7.退出：退出系统前要确认已经完成保存。

## 开源协议

本项目采用 MIT License，详细许可条款请见 LICENSE 文件。
