//心得
//这次的难度很大，一开始没看清题干用了uart,之后问了同学才回到正轨。
//之后用尝试了好多种方法，最后选用了我能理解的，但是在测试的过程中总是乱码。
//我的思路是1：实现高低电平输出HAL_GPIO_Write
//2:波特率（psc+1）*（arr+1）/tclk=868
//3:奇校验：将各个位上的1相加在取余2判断是否加1
//最后输出
//目前我尝试了许多种方式都没能是小灯亮起来，在之后也会继续尝试


https://github.com/user-attachments/assets/a3f7ee69-d6e1-457b-bc1c-0afcec1a3645

