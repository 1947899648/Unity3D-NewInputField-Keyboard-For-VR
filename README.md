# Unity3D-NewInputField-Keyboard-For-VR

一种改善Unity3D系统自带InputField原生组件在VR程序（Apk格式）里进行UI射线点击触发字符输入功能失效问题的包。  
A package that improves the failure of the Unity3D system's own InputField native component to trigger character input by UI ray clicks in VR programs (Apk format).  

包提供了VR虚拟键盘和自制的“InputField”，如下所示。  
The package provides a VR virtual keyboard and a self-made "InputField" as shown below.  

特别说明：不依赖其他插件及包，导入本包，选中预制体拖进场景即可使用。  
Special Note: Do not rely on other plug-ins and packages, import this package, select the prefab and drag it into the scene to use.  

![Screenshot 2023-01-02 221418](https://user-images.githubusercontent.com/32610394/210243194-afb8d2cb-3f48-42fe-9cc7-2d25c8a1041d.png)
（可能需要额外添加XR UI交互组件，比如XR Interaction Toolkit里Tracked Device Graphic Raycaster组件，你们应该会）  
(It may be necessary to add additional XR UI interaction components, such as the Tracked Device Graphic Raycaster component in the XR Interaction Toolkit, you should know)  

已经过 Pico4 安装并实机验证（不采用Preview Tool工具）  
Pico4 has been installed and verified on the actual machine (without using Preview Tool)  
![2eebe843e13fc0475c35e63316d5a9e](https://user-images.githubusercontent.com/32610394/210244091-441fb4fc-35f4-499d-9658-b71b68efe94e.png)


特别说明：本包中VR虚拟键盘功能不是很完善，目前只有数字、大小写字母等键位输入，而且键盘的外观“皮毛”是我从某个网站扒下来的，链接如下：
https://blog.csdn.net/qq_40401591/article/details/120532647  
Special Note: The function of the VR virtual keyboard in this package is not very perfect. At present, only numbers, uppercase and lowercase letters and other key positions are input, and the "fur" of the appearance of the keyboard is picked up from a certain website by me. The link is as follows:
https://blog.csdn.net/qq_40401591/article/details/120532647  
