本项目是利用repo管理github上的一些Android开源项目，使用本项目须遵守该项目中所有开源项目所涉及到的License，具体的请参见各项目

各项目相关的介绍以及相关的内容或License参见地址：

1、androidkit                  https://github.com/kymjs/androidkit
2、android-smart-image-view    https://github.com/loopj/android-smart-image-view
3、android-websockets          https://github.com/koush/android-websockets
4、fqrouter                    https://github.com/fqrouter/fqrouter
5、iosched                     https://github.com/google/iosched
6、KJFrameForAndroid           https://github.com/kymjs/KJFrameForAndroid
7、osmdroid                    https://github.com/osmdroid/osmdroid
8、pinyin4j                    https://github.com/belerweb/pinyin4j
9、ThinkAndroid                https://github.com/white-cat/ThinkAndroid
10、其余的项目参见地址         https://github.com/Trinea/android-open-project

使用该项目需要安装git和repo，repo的安装和使用介绍具体的参见http://source.android.com/source/downloading.html，http://source.android.com/source/using-repo.html
安装repo：
		$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
		$ chmod a+x ~/bin/repo
使用repo init初始化项目：
		$ repo init -u https://github.com/aw691190716/manifests
下载项目中所涉及的源码：
		$ repo sync

## License

    Copyright 2014 aw691190716@gmail.com

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
