# 工作流：
# 1）在代码运行器新建文件，将这些代码复制入
# 2）点击运行
# 3）输入总层数和层与层之间的间隔，通常是0.2
# 4）输入各层对应的参数，注意如果你将X的跨度设置的更高，那么对于材料来说，X方向是Active layer，走线方向垂直于Y轴
# 5）选择是否使用相位器功能，Y使用：同样间隔的层的纤维将会异相位，N不使用则，方向一致并间隙距离相等的纤维将会同相位
# 6）程序会自动保存代码至桌面，格式为Gcode，双击可以直接使用 Repetier-Host打开
# 7）打开应用后，可以点击打印预览，查看几何形态或者编辑Gcode
# 8）开始你的模型设计或打印

## 额外注意 #关于运行环境# ：要在规定python版本下运行，以及装载好math, numpy, os
## *1 在终端中输入python --version，检查是否是Python 3.12.1
##    -如果不是Python 3.12.1，就去python官网下载一个
## *2 确认版本无误后，使用vscode打开该程序， 检查pip是否是最新版本（vscode终端输入）python -m pip install --upgrade pip 或输入 python.exe -m pip install --upgrade pip
## *3 确认pip版本正确后，终端输入pip install numpy


# Workflow:
# 1. Create a new file in the code runner and copy these codes into it.
# 2. Click run.
# 3. Enter the total number of layers and the spacing between layers, usually 0.2.
# 4. Input the parameters corresponding to each layer. Note that if you set a higher span for X, then in terms of materials, the X direction is the active layer, and the routing direction is perpendicular to the Y-axis.
# 5. Choose whether to use the phase function. If Y is used: the fibers in the same interval layer will be out of phase. If N is not used, the fibers with consistent direction and equal gap distance will be in phase.
# 6. The program will automatically save the code to the desktop in Gcode format, which can be opened directly with Repetier-Host by double-clicking.
# 7. After opening the application, you can click on print preview to view the geometric shape or edit the Gcode.
# 8. Start your model design or printing.
