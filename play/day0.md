# day 0 Get Start

## 0x00 VerB还是VerC？

开始搞机之前 得先弄明白你的计算器版本

有些搞机的操作在不同版本之间并不相同

版本号越是往后的机型，系统越是稳定，漏洞也越少，导致有些能在VerB上执行的操作在VerC上无法执行。

查看计算器版本的方法：

 	1. 同时按下Shift+7+ON
 	2. 9
 	3. 5次Shift
 	4. 第一行后半句就是版本号

此外还可以顺便看看计算器的序列号：

5. 菜单键
6. AC

## 0x01 119

指搞机后按开机键恢复不了的情况

如果别人告诉你某个搞机的公式会119的话，请谨慎尝试公式

退出119的方法不算难：

​	拆下电池（打开计算器的背面小块盖板）



## 0x02 68模式

指开机后保留历史记录的模式，进入68模式极其复杂，目前暂无VerC进入68模式的公式



## 0x03 开启字符转换器

公式：

	1. 1
 	2. Shift
 	3. 8（单位换算）
 	4. ↓
 	5. 2
 	6. 7
 	7. ＝
 	8. 上
 	9. ←

如果公式输入无误，那么显示屏将会出现：

​	【光标】1

### 刷出中文字符

进入字符转换器后，键入下表中的任意一个：

| 按键                | 转换后的效果 |
| ------------------- | ------------ |
| °                   | 1g>厘        |
| ）                  | 1m^2^>勺     |
| ÷                   | 1分>mm       |
| ×                   | 1cm>寸       |
| +                   | 1m>尺        |
| -（减号）           | 1寸>cm       |
| -（负号）           | 1L>斗        |
| optn     2     1    | 毛>g         |
| optn     2     2    | g>毛         |
| optn     2     3    | 厘>g         |
| Shift     ×         | 町>m         |
| Shift     ÷         | m>町         |
| alpha     calc（=） | 1尺>m        |



## 0x04 刷an

刷出an后能做很多奇怪的事情

公式（括号内为注释）：

   	1. 菜单
      	2. 2（进入虚数模式）
         	3. 进入字符转换器
            	4. shift
               	5. .（小数点）
                  	6. ←
                     	7. ←
                        	8. →
                           	9. i（虚数i）
                              	10. 左
                                 	11. 9

如果公式输入无误，那么显示屏将会出现：

​	1a>m^2^an@



## 0x05 刷框

框就是一个卡西欧计算器中用来填数字的地方，但是单纯只有一个框只有刷bug才能做到

公式一：

1. 进入字符转换器
2. Shift
3. 8
4. ↓
5. 2
6. 1

如果公式输入无误，那么显示屏将会出现：

​	1Unknow[]【光标】

删除框外字符即可

公式二：

1. 6
2. ÷
3. 3
4. （
5. （
6. 2
7. +
8. 1
9. ：
10. 根号
11. ←
12. ←
13. 根号按到不能按为止
14. 1（任意数字）
15. calc
16. ＝
17. →

此时就能看到框了，把框外的字符删除即可

PS.这是目前已知的唯一一种不需要用到字符转换器的刷框的公式，如果以后字符转换器被修复了，就只能靠这个公式刷框了。



## 0x06 隐藏变量$

打出$的公式：

1. 进入字符转换器
2. Shift
3. 8
4. ↓
5. 2
6. 8

如果公式输入无误，那么显示屏将会出现：

​	1Unkow$【光标】

然后删除除$外其他字符即可

赋值：只需按下calc即可



## 0x07 隐藏变量@

打出@的公式：

1. 进入字符转换器
2. Shift
3. 7
4. 1
5. 4

如果公式输入无误，那么显示屏将会出现：

​	1tl&*&9<9<9E@【光标】

然后只要→ DEL DEL即可删除多余字符

赋值：只需按下calc即可