MyGreenDAO
==========

<p>
<img src="http://7xikfc.com1.z0.glb.clouddn.com/gr_logo.png" width="100px" height="100px" align="left" hspace="15px" />
MyGreenDAO 是我在学习使用 ORM 框架 greenDAO 时在官方提供的 Example Project 上精简出来的 Demo，为此添加了详细的注释说明，旨在帮助大家能快速了解、上手使用并扩展 greenDAO。我会持续跟新 MyGreenDAO，不断优化与添加新的功能，欢迎大家 Fork 与 Star 。                                      
</p>       

<img src="http://7xikfc.com1.z0.glb.clouddn.com/mygreendao-1.1.gif" alt="screenshot" title="screenshot" width="300" height="533" />

**Demo is still in development so more features will be added soon**

  - [Usage](#usage)
  - [Download](#download)
  - [Documentation](#documentation)
  - [Thanks to](#thanks-to)
  - [Contact Me](#contact-me)
  - [License](#license)

# Usage

### Dependency - 依赖
  - Java Development Kit (JDK) 8 +
  - com.android.tools.build:gradle:1.2.3
  - Android SDK
    - Android SDK Build-tools 22.0.1


### Build - 构建

    git clone https://github.com/tangqi92/MyGreenDAO.git

用最新的 IntelliJ IDE 导入工程（Import Project），然后等待 IDE 下载 gradle 和依赖包即可

This project uses the Gradle build system. To build this project, use the "gradlew build" command or use "Import Project" in Android Studio.

对啦，是时候和 Eclipse 说拜拜了，赶紧拥抱 [Android Studio](https://developer.android.com/sdk/index.html) 吧：D

### Modify - 修改

如一切正常（compileSdkVersion 与 buildToolsVersion 等需根据自己实际情况更改），你只需要修改 [ExampleDaoGenerator](https://github.com/tangqi92/MyGreenDAO/blob/master/daoexamplegenerator/src/main/java/me/itangqi/ExampleDaoGenerator.java) 类中如下这条语句，"..."替换为你实际的存放目录即可   

```java
new DaoGenerator().generateAll(schema, ".../MyGreenDAO/app/src/main/java-gen");
```  

# Download

直接下载：[MyGreenDAO-1.1.0.apk](https://github.com/tangqi92/MyGreenDAO/releases/download/v1.1.0/app-release-unsigned.apk)

# Documentation

项目主页：[ORM 框架之 greenDAO 使用心得](http://itangqi.me/2015/07/26/orm-greendao-summary/)  

# Thanks to

再次感谢：[greenDAO](https://github.com/greenrobot/greenDAO)  

# Contact Me

- Weibo：[@汤奇V](http://weibo.com/qiktang)
- Gmail：[imtangqi#gmail.com](mailto:imtangqi@gmail.com "欢迎与我联系")
- Blog: [http://itangqi.me](http://itangqi.me)  

# License

<pre>
The MIT License (MIT)

Copyright (c) 2015 Qi Tang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
</pre>