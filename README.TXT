HARDWARE 中存放需要硬件的驱动 头文件放在inc 源文件放在src中


OBJ 中存放编译生成的HEX文件


USER 中存放 工程文件

如果有需要可以将STM32F10x_FWLib中的对应库文件加入工程

SYSTEM 存放 sys.c sys.h delay.c delay.h usart.c usart.h



每次推送的时候，先拉取仓库，再修改对应部分，然后推送上来
