# 代碼工作原理
## 得到隐写术图
#### 通过隐写术图工厂输入源代码和原图参数，先创建一个编译器将源代码编译成class文件，再由工厂创建隐写术图编码器，由编码器根据图片的位深度和长宽大小获得像素位的RGB数组，再将其由RGB数组与源代码编译后的class文件的字节数组一一根据公式编码成新的RGB数组，并以新的数组和原有的图片参数形成一张编写好的隐写术图。
## 如何使用隐写术图
#### 创建一个隐写术图类加载器并传入隐写术图url,调用加载器加载相应类名，加载器会先在类路径下找是否存在该类代码，如纯在则直接调用，如不存在则创建一个隐写术图编码器对隐写术图进行解码（依据公式逆推编码过程），将解码后得到的字节数组定义为类，则加载结束。

---
# 隐写术图
## 快速排序
![](https://github.com/ChinoJunko/ChinoJunko.github.io/blob/main/2021/10/example.QuickSorter.png?raw=true)

## 希尔排序
![](https://github.com/ChinoJunko/ChinoJunko.github.io/blob/main/2021/10/example.ShellSorter.png?raw=true)

---
# 视频（GIF格式）
## 快速排序
![](https://github.com/ChinoJunko/ChinoJunko.github.io/blob/main/2021/10/2021-10-04%2014-18-45%2000_00_00-00_00_30.gif?raw=true)
## 希尔排序
![](https://github.com/ChinoJunko/ChinoJunko.github.io/blob/main/2021/10/2021-10-04%2014-18-55%2000_00_00-00_00_30.gif?raw=true)

---
# 同学の图
## 同学： 严思远
![严思远版权所有](https://github.com/ChinoJunko/ChinoJunko.github.io/blob/main/2021/10/quick.png?raw=true)
## 结果
### 正确
![](https://github.com/ChinoJunko/ChinoJunko.github.io/blob/main/2021/10/10_04_14_24.PNG?raw=true)

___

<a href="mailto: 598991406@qq.com" target="_blank">邮箱链接</a>