1、![1](https://user-images.githubusercontent.com/102397160/189475217-3d99c6e5-4162-4a70-a7f8-0a37ca124e3e.png)

2、![2](https://user-images.githubusercontent.com/102397160/189475219-29c39d5f-0ff4-45dd-936e-12bf8cad7681.png)

3、![3](https://user-images.githubusercontent.com/102397160/189477652-8981209a-0b09-4aee-8c43-d34bd4ae2d44.png)



为了便于复制，代码放在下边了。这样修改完android_builder和release都行了。

implementation files('libs\\xwalk_shared_library-23.53.589.4.aar')

flatDir { dirs './libs' }

 第2项文件：xwalk_shared_library-23.53.589.4.aar放这个文件夹里：app/libs/  

文件在这个文件夹里：https://github.com/dlgt7/TVbox-interface/tree/main/xwalk_shared_library23.53.589.4



最简单的办法如下：

//maven { url 'https://download.01.org/crosswalk/releases/crosswalk/android/maven2' }
        
maven { url 'http://9xi4o.tk/maven2' }


