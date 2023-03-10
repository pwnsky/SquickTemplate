# Squick Template

方便让Squick核心代码与项目工程代码实现解耦，让项目代码与核心代码进行分离。



命令:

squick_ctl init: 自动根据squick_version.txt拉取squick代码，计算squick代码的所有文件hash，并生成squick_files.txt

squick_ctl patch: 将当前的更改patch到代码中。

squick_ctl add: 将更改的代码保存起来到diff文件夹下。

