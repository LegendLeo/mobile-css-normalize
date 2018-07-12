mobile-css-normalize
====================

移动端css初始化文件，包含了部分标签浏览器展示统一化，文本溢出处理，附带了常见的animation动画

如果需要使用到多行文本溢出处理，请将`normalize.less`文件import到你在编辑的less文件，然后在你编辑的选择器中加入`.multi-ellipsis`类名，默认为处理3行溢出，如果需要处理其他行数，请加入`.multi-ellipsis (lines)`，此处`lines`请替换为你需要的行数

生产环境建议使用编译出来的文件名以min.css结尾的压缩文件

欢迎大家提PR以及修改需求，如果觉得不错，给个Star呗