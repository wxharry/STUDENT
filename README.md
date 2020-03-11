# STUDENT -Powerbuilder

## 已经通过宋老师的验收了，没发现什么bug

## 遇到的坑:  
可以修改学生表和数据表，但是不能修改成绩
* 修改dw中该列的taborder为非零  
> 打开d_score_input-DataWindow  
找到工具栏上面taborder图标（或者找到窗口的Format-Tab Order）  
点击打开 可以看到列上出现红色小数字  
点击修改数字到非零 一般修改成整十数 该顺序就是tab的顺序  
  
* 勾选dw中的allow update  
> 打开d_score_input-DataWindow  
找到窗口的Rows-Update Properties  
点击并进入Specify Update Properties窗口界面  
勾选Allow Updates  
Table to Update: 选择sc表  
点击OK确认  
	
