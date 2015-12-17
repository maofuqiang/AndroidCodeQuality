# AndroidCodeQuality

When run "gradle assembleXX" or build your app,it will auto check the code quality with checkstyle,pmd,findbugs. 

1.It will run checkstyle,pmd before your build task and run findbugs after your assemble task.

2.You can config 'ignoreFailures = false' to force stop your build task. This will force you to optimize your code.

#Usage: 
1、copy the /doc folder to your_android_studio_project/app/

2、input "apply from: './doc/quality/quality.gradle'" to your build.gradle in your_android_studio_project/app. 

3、run your app or gradle assembleXX,this gradle script will auto check the code quality.

#To go further
-------------
This project is based on these two other projects, which are awesome. Consider take a look at them :
 - [Quality-Tools-for-Android](https://github.com/stephanenicolas/Quality-Tools-for-Android).
 - [vb-android-app-quality](https://github.com/vincentbrison/vb-android-app-quality).

#Contact me:

Blog:http://blog.csdn.net/masonblog

Email:MasonLiuChn@gmail.com

#License:
    Copyright 2013 MasonLiu, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

