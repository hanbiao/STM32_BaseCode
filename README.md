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
	

+BSP - 板载设备驱动, 主要来源于Keil的DFP package

+License - 各种库的license

+Middleware - 第三方库
	+FreeRTOSv10.2.1 - 内核

+Libraries - 外设驱动库, 驱动库来源于STM32F4-Discovery_FW_V1.1.0, HAL库来源于Keil的DFP package
    +STM32F4xx_StdPeriph_Driver - 用这个库的时候要替换Device文件夹下的stm32f4xx.h
	    +inc - 外设API头文件
		+src
	STM32F4xx_HAL_Driver - 默认使用HAL库
		+Inc - HAL层头文件
		+Src
		
+Config - 库的配置文件
	+HAL Libraries
		stm32_assert.h  - 自定义assert实现
		stm32f4xx_hal_conf - HAL库配置
	+Standard Libraries
		stm32f4xx.h  - 要用标准库，则需要用这个头文件
		stm32f4xx_conf - 标准库模块配置
	+FreeRTOS 
		FreeRTOSConfig.h - 内核剪裁配置文件
		
+Utilities - 辅助接口

