# 飞腾派驱动开发训练营第三周作业

## QEMU实验（任选其一完成）

所有实验基于 ArceOS 实现

ArceOS仓库：https://github.com/arceos-org/arceos

完成后，请将运行效果截图和代码仓库链接提交至 https://github.com/kunyuanxu-star/hw-deiver-week3/issues/1

### 实验 1：基于 QEMU ARM64 Virt 的 UART 驱动实现

#### 目标

实现 UART 驱动，支持 QEMU virt 机型的 PL011 UART 控制器，实现串口输出和输入功能。



### 实验 2：基于 QEMU ARM64 Virt 的 I2C 驱动实现

#### 目标

实现简化的 I2C 驱动，支持 QEMU virt 机型的 Allwinner I2C 控制器（或其它型号 I2C 控制器），实现基本数据写入功能。



### 实验 3：基于 QEMU ARM64 Virt 的 SPI 驱动实现

#### 目标

实现简化的 SPI 驱动，支持 QEMU virt 机型的 Allwinner A10 SPI 控制器（或其它型号 SPI 控制器），实现简单的数据传输（发送并接收固定数据）。



**如希望在飞腾派开发板上进行实验，请参考docs/第三周课后作业（飞腾派）--王晓东**



## 部分资料

可供参考的Linux驱动和SDK驱动及技术文档如下：

- 飞腾派相关开发文档： https://github.com/elliott10/dev-hw-driver/tree/main/phytiumpi/docs
- ArceOS for 飞腾派驱动开发参考案例： [arceos-org/arceos#222](https://github.com/arceos-org/arceos/pull/222)
- 飞腾派Linux代码 https://gitee.com/phytium_embedded/phytium-linux-kernel
- [飞腾派Linux用户使用开发手册](https://gitee.com/phytium_embedded/phytium-embedded-docs/blob/master/phytiumpi/linux/飞腾派OS用户使用开发手册 v2.1.pdf)
- 飞腾派SDK代码 https://gitee.com/phytium_embedded/phytium-standalone-sdk
- [飞腾派裸机SDK指导手册 （含各类驱动示例）](https://gitee.com/phytium_embedded/phytium-embedded-docs/blob/master/phytiumpi/rtos/飞腾派裸机SDK指导手册-v1.0.pdf)

飞腾派OS-I2C 驱动：

https://gitee.com/phytium_embedded/phytium-linux-kernel/tree/linux-5.10/drivers/i2c

飞腾派OS-SPI 驱动：

https://gitee.com/phytium_embedded/phytium-linux-kernel/tree/linux-5.10/drivers/spi

飞腾派OS-串口驱动：

https://gitee.com/phytium_embedded/phytium-linux-kernel/tree/linux-5.10/drivers/tty/serial