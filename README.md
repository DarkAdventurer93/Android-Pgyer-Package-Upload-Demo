# Android-Pgyer-Package-Upload-Demo
安卓蒲公英新版API自动打包上传示例
<br><br>
1.使用：在app下的buidl.gradle中apply项目中的packagePygerUpload.gradle
<br><br>
2.在build.gradle下进行打包配置，如下
<br><br>
![image](https://user-images.githubusercontent.com/24764220/219619854-a2b79f07-a026-4de8-8644-9a1b51674d21.png)
<br><br>
这里示例是打包完成之后发送到企业微信并通知测试，若需要修改成钉钉可以自行修改代码
<br><br>
3.配置完成之后点击Android Studio右侧的gradle栏目，找到packagePygerUpload脚本，双击执行
<br><br>
![image](https://user-images.githubusercontent.com/24764220/219620385-c504d4a1-f0d9-4017-8575-4674d946b93e.png)
<br><br>
AndroidStudio底部的run栏目查看，效果图：
<br><br>
a.开始执行：
<br><br>
![image](https://user-images.githubusercontent.com/24764220/219620618-6d57b57d-faf0-4eb2-9253-73961ea107b5.png)
<br><br>
b.执行完成,正在上传应用：
<br><br>
![image](https://user-images.githubusercontent.com/24764220/219621178-a3035a08-6f6d-43a0-9a0c-154d89427744.png)
<br><br>
c.检查应用发布状态：
<br><br>
![image](https://user-images.githubusercontent.com/24764220/219621520-b9e067f8-acfc-4da5-8730-bf05b5354c69.png)

