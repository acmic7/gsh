# gsh(shell)
还没想好


### shell和bash
shell 是运行在终端中的文本互动程序，bash（GNU Bourne-Again Shell） 是最常用的一种 shell，其是当前大多数 Linux 发行版的默认 shell。

shell 相当于翻译器，其可以将计算机上的操作或用户输入的命令翻译为计算机可识别的二进制命令，传递进内核，以便调用计算机硬件执行相关的操作；同时，计算机执行完命令后，再通过 shell 翻译成自然语言，呈现在我们面前。

除了 bash 以外，有许多其他的 shell 如：sh、ksh、rsh、csh 等。Unbuntu 系统常用的是 bash，Bio-linux 系统是基于 unbuntu 定制的，但是却使用了 zsh。

这里的 sh 全名为 Bourne Shell，名字中的 Bourne 就是这个 shell 的作者。

而最常使用的 bash 全名是 Bourne Again Shell。最开始在 Unix系统中流行的是 sh，而 bash作为 sh 的改进版本，提供了更加丰富的功能。一般来说，都推荐使用 bash 作为默认的 shell。

这里可以使用 echo $SHELL 查看当前系统中 shell 的类型。

Shell命令的分类
shell 命令可分为如下三类：

- 内建函数(built-in function)：shell 自带的功能；
- 可执行文件(executable file)：保存在 shell 之外的脚本，提供了额外的功能；
- 别名(alias)：给某个命令的简称。
可以使用 type 命令查看 shell 命令的类型，如果是内建命令会显示 xx is a shell builtin，如果是可执行文件会显示该命令的可执行文件位置，如果是别名则会显示 xx is aliased to xx。
