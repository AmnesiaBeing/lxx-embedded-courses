请协助完成Rust嵌入式项目的搭建：

# 背景信息
1. 目标开发芯片：STM32F103ZET6
2. 目标调试工具：J-Link
3. 当前开发环境：TRAE
4. 希望使用probe-rs进行调试
5. 开发板上有两个LED，分别连接在PB5、PE5引脚，低电平亮起
6. 当前目录已完成基础项目的搭建，包含main.rs、Cargo.toml、.vscode/launch.json等文件，并包含了stm32相关依赖

# 任务目标
编写代码，实现通过PAC方式控制LED的亮灭
