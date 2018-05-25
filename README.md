# binary_analysis
A set of tools for binary analysis

## Angr_CFG
Angr生成CFG  

format: python proCFG.py -i <inputfile> -o <outputfile> [inst][vex]   
-i 二进制文件路径  
-o CFG图生成路径  
inst 是否显示汇编指令  
vex 是否显示vex语言  

## extract_raw_binary
extract the raw binary of the .text section from an executable.
