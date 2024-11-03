# Prompt Selector Plugin for ComfyUI

一个用于管理和选择提示词的ComfyUI插件。

## 功能
- 支持输入多个键值对格式的提示词
- 提供下拉选择框选择特定提示词
- 输出选中提示词的值

## 安装
1. 将此文件夹复制到ComfyUI的`custom_nodes`目录下
2. 重启ComfyUI

## 使用方法
1. 在文本框中输入提示词对，每行一个，格式如下：
   "key1":"value1",
   "key2":"value2",
   "key3":"value3"
2. 从下拉框中选择想要使用的提示词
3. 节点将输出所选key对应的value

## 示例输入
"风格1":"写实风格",
"风格2":"动漫风格",
"风格3":"油画风格"