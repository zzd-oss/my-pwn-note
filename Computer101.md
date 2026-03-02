## Your First Programme
一般来说现在的CPU有16个寄存器
用as -o 生成一个 可重定位的ELF
再用ld -o 生成一个可执行的ELF
格式如下：
as -o program.o program.s
ld -o program program.o
这个program就是可以执行的了
program.s里面是汇编语言，
exit退出：要求rax=60，rdi=很多值，可以是42，也可以是其他，其中-o是你想起的名字。