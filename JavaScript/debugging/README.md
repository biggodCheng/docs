* console.time('title') | console.timeEnd(); 兼容性：ALL
* console.trace('title' 从代码运行的起点追踪到最终目的地（trace所在），并将期间所有的函数按照顺序输出在控制台中 兼容性：IE10+
* debug() -> 运行要调试的函数 兼容性：chrome（only）相比较手动加断点与代码加断点(debugger)它的好处在于可以在控制台快速针对的在某个函数添加断点，但是局限在于，它只能为全局的函数添加断点，对于私有以及匿名的函数无效。

* blackboxing（黑箱）：用于屏蔽在调试期间不需要进入的JS文件。强烈建议在调试之前就设置好将那些JS文件放入黑箱中
  Chrome可以右击 -> blackbox script 然后再 settings -> blackboxing 中进行管理
  Firefox：调试器 -> 目标JS文件，然后下面有一个眼睛的图标。
* DOM监控：Chrome 对着要监控的HTML节点右击:Break on.. -> [subtree | attribute | remove]
