# sztu-scramble-for-class
SZTU教务抢课小脚本V1.0终终终于发布啦！你还在为抢不到课而烦恼吗？你还在为网速慢而丧气吗？sztu抢课脚本它来辣！
# How to use?
这是一份面向有一点动手基础的用户的一个小脚本，相比于锁子哥的js版本，此版本直接提供了Win的可执行文件，更加方便哦！

## 安装
<code>
pip install -r requirements.txt
</code>
## 使用

  username指学号
  password指密码
  课程是指课程的ID，不是课程的名称。你可以在F12中找到它。
  #### 1。基础版
  在要选的课的选课按钮上单击右键-检查
  <img width="460" alt="8e8701f618a6830723a4cb18663b19b" src="https://user-images.githubusercontent.com/50409074/221406356-b8957fb1-43cf-4ae2-84c0-95852e18f345.png"> 
  长串数字为jx0404id 课程号或字符串为kcid（格式不确定），仔细对照后填写！
  #### 2进阶版
  在选课之前按F12，点击网络，点击选课，查看出现的第一个请求，按照请求里面的填写配置文件
  <img width="1123" alt="deeb398a1f1b7c4cab5bb0f34afe0a7" src="https://user-images.githubusercontent.com/50409074/221406505-6b820976-5616-4174-96cf-2c04a5f31a7f.png">
<img width="1118" alt="d0ca5b8f062d8b90b0c92d68a6e2616" src="https://user-images.githubusercontent.com/50409074/221406512-2fb37d7f-add2-43e6-abf6-db8103eb9349.png">
## 注意
配置文件需要完整填写并和脚本放在同一个目录，否则无法运行
