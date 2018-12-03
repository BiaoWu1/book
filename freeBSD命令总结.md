* [窗口操作](#一窗口操作)
  


# 一、窗口操作

  * ctrl + alt + F1 ~ F6 : 开启窗口
  * tty : 查看当前所在窗口
# 二、创建 Makefile文件：

  * Makefile文件作用：当编译文件较多时，手动一个一个的编译比较耗费时间，Makefile文件实现自动化编译
  * 编译方式如下：
  ```
  vim Makefile.c 进入编辑页面
  //编辑如下命令
  text: text.c              //前面的text名字可以任意起
    cc text.c -o hello.c   //此处cc前面必须是一个tab
  ```
  
# 
  
