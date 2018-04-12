# Logcat  
[![](https://jitpack.io/v/tianzhijiexian/Logcat.svg)](https://jitpack.io/#tianzhijiexian/Logcat)     

## 打开log界面

```JAVA
Logcat.jumpToLogcatActivity(context);
```
  
## 运行log服务

```JAVA
Logcat.startLogCatServer(context);
```

### Download   
Add it in your root build.gradle at the end of repositories:  
```  
repositories {
    maven {
	url "https://jitpack.io"
    }
}
```   
Add the dependency:     
> compile 'com.github.tianzhijiexian:Logcat:[Latest release](https://github.com/tianzhijiexian/Logcat/releases)'

### More Detail  
You can see more detail in [Logcat.java](https://github.com/tianzhijiexian/Logcat/blob/master/lib/src/main/java/kale/debug/log/LogCatCmd.java)

### Phone
![](./images/phone.png)
### Web
![](./images/pcweb.png)

### Developer   
![](https://avatars3.githubusercontent.com/u/9552155?v=3&s=460)

Jack Tony: <developer_kale@foxmail.com>  

### License

    Copyright 2016-2019 Jack Tony

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
