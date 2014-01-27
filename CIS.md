# Bizdev UI组件通用接口规范 #
*Bizdev Common Interface Specification for  UI Component*
## 目录（Contents） ##
* [简介（Introduction）](#简介)
 * [更新日志（Change Log）](#更新日志)
 * [关于本规范（About）](#关于本规范)
 * [贡献者（Contributors）](#贡献者)
 * [阅读指南（Guides）](#阅读指南)
* [简单组件（Simple Component）](#简单组件)
 * [按钮（Button）](#按钮)
 * [遮罩（Mask）](#遮罩)
 * [提示（Tooltip）](#提示)
* [表单类组件（Form Component）](#表单类组件)
 * [单选框（Radio）](#单选框)
 * [复选框（Checkbox）](#复选框)
 * [输入框（Input）](#输入框)
 * [文本框（Textarea）](#文本框)
 * [下拉列表（Select）](#下拉列表)
* [导航类组件（Navigation Component）](#导航类组件)
 * [面包屑（Breadcrumb）](#面包屑)
 * [标签（Tab）](#标签)
 * [下拉菜单（Dropdown Menu）](#下拉菜单)
* [复合类组件（Complex Component）](#复合类组件)
 * [日历（Calendar）](#日历)
 * [表格（Table）](#表格)
 * [对话框（Dialog）](#对话框)
 * [树（Tree）](#树)
 * [翻页（Page）](#翻页)
* [附录（Appendix）](#附录)
 * [API速查表（API Quick Search）](#api速查表)

# 简介 #
## 更新日志 ##
## 关于本规范 ##
### 概述（Overview） ###
### 版权声明（Copyright） ###
### 免责声明（Disclaimer） ###
### 参考文献（References） ###
## 贡献者 ##
## 阅读指南 ##

# 简单组件 #

## 按钮 ##
### 版本（Version） ###
`0.1`
### 描述（Description） ###
按钮和按钮组
### 依赖（Dependencies） ###
`Control.js`
### 继承层级（Inherit Level） ###
`Button` - `Control`
### 初始化参数（Options） ###
> {String} text

描述：按钮文字

默认值：`null`

示例：

    $(".selector").button({text: "提交"});

### 公共方法（Public Methods） ###
> ｛Object} destroy

描述：销毁

参数：`void`

示例：

    $(".selector").button("destroy");

### 事件（Events） ###
> click

描述：销毁

参数：`{Event}event`, `{Object}ui`

示例：

    $(".selector").button({
		click: function(event, ui) {}
	});

## 遮罩 ##
## 提示 ##

# 表单类组件 #
## 单选框 ##
## 复选框 ##
## 输入框 ##
## 文本框 ##
## 下拉列表 ###

# 导航类组件 #
## 面包屑 ##
## 标签 ##
## 下拉菜单 ##

# 复合类组件 #
## 日历 ##
## 表格 ##
## 对话框 ##
## 树 ##
## 翻页 ##

# 附录 #
## API速查表 ##
