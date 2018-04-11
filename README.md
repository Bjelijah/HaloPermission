## HoloPermission (0.9-rc)
An Android permission library developed by Kotlin language with higher extensibility and compatibility.

Kotlin语言开发的Android权限库，具有更高的扩展性和兼容性。


### Setup

1.在工程(Project)的build.gradle中添加以下语句：

```
    allprojects {
        repositories {
            jcenter()
            maven {
                url 'https://dl.bintray.com/supluo/maven'
            }
        }
```
2.在使用HaloPermission的Module的build.gradle中添加以下依赖：
```
    dependencies {
        compile('halo.android:permission:0.9-rc')
    }

```
### Usage
  
**[查看详细使用](https://github.com/SupLuo/HoloPermission/blob/master/doc/README_USAGE.md)**

### Todo
* 兼容6.0以下权限处理
* 补全更多机型的权限设置界面

### License

    ```
      Copyright (C) 2018 Lucio

      Licensed under the Apache License, Version 2.0 (the "License");
      you may not use this file except in compliance with the License.
      You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
      See the License for the specific language governing permissions and
      limitations under the License.

    ```
