
实验目的
基于FPGA的自动售咖啡机设计与实现，将高级数字系统设计方法应用于实际项目中，并用Verilog HDL语言对电路进行描述及仿真验证，最终在FPGA开发板上进行硬件实现。
（1）	熟练应用基于FPGA的数字系统设计方法；
（2）	熟练使用Verilog HDL进行硬件描述；
（3）	熟练进行功能仿真及硬件调试。
实验要求
完成基于FPGA的自动售咖啡机的代码编写、仿真、逻辑综合、布局布线及下载，进一步熟悉基于FPGA的数字系统设计流程及EDA工具的使用，并规范撰写项目报告。
附加项目：
   使设计的自动售咖啡机电路具有找零功能，自动售咖啡机#3。
实验内容：
咖啡机功能要求：
1.	只售咖啡；
2.	三元/杯；
3.	接收一元/五角硬币；
4.	不找零钱；
5.	售货机中的杯子永远用不完。

实验原理：
    从投币口投入1元或5角硬币后,系统对钱币进行计数,当计够 3 元钱,便自动出咖啡一杯。如果投入的钱币大于3 元,如 3.5元,不进行找零,并且在卖出一次咖啡后,系统钱数清零。
