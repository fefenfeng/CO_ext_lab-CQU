## CO_ext_lab-CQU

重庆大学计算机硬综拓展实验，对应在写的教材。

## 计划
1. axi接口实验  实现将CPU从sram接口封装成类sram接口，再封装成axi接口
2. Cache实验  实现写回的cache
3. TLB实验    实现基于TLB的MMU模块，了解MIPS基于TLB的虚拟地址转换过程
4. [展望] 运行系统
    - 需要一个更完整的SoC，可考虑移植龙芯杯系统测试soc到N4DDR上（含串口控制器、SPI flash、DDR3）[已完成]
    - 参考龙芯杯系统测试资料，运行[清华监控程序](https://github.com/z4yx/supervisor-mips32/)[已完成]
    - 移植运行[ucore](https://github.com/kiukotsu/ucore)
