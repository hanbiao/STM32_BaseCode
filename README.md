# STM32_BaseCode
stm32 open source project base

+Device - 设备相关的代码, 主要来源于Keil的DFP package
    +ST
		+STM32F4xx
			+Include
				stm32f4xx.h - 外设寄存器定义
				system_stm32f4xx.h - 时钟配置接口
			+Source
				startup_stm32f407xx.s  - 启动代码
				system_stm32f4xx.c
				
+CMSIS - ARM内核库, 主要来源于ARM的CMSIS软件包
	+Core
		+core_cm4.h - 内核寄存器, 指令集操作
		+cmsis_compiler.h - 编译器命令
	

+BSP - 板载外设驱动, 主要来源于Keil的DFP package

+License - 各种库的license

