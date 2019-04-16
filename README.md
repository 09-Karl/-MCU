# -MCU
一种纯色块图片无损压缩方法(C语言)；

由于MCU内存的限制，存储图片的数据需要被无损压缩，因此提出一种图片无损压缩方法；

方法限制条件：

1.连续色块较多，纯色块越多压缩率越高；

2.图片像素点≤65536,16bit最大值；


压缩后图片数据格式：颜色数据(2Byte)+像素点个数(1/2Byte)

压缩前为6480 Byte

压缩后为3798 Byte

压缩率为0.58


使用图片取模软件为：Image2Lcd；

图片名称：背景40_80.jpg；

图片取模文件名称：background.h；

编译软件VC++6.0
