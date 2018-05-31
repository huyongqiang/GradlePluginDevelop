## Gradle插件开发介绍


####  Gradle基础详解：

    这一次一定要系统掌握，你准备好了吗？
    
    
- [初识Gradle 和 领域专用语言](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/day01.gradle)
- [Gradle 版本配置](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/day02.md)
- [Gradle 模块配置](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/day03.gradle)
- [Gradle 插件分类](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/day04.gradle)
- [Gradle Android插件包含的内容](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/android.gradle)
- [Gradle 统一配置你的版本号](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/version.gradle)
- [Gradle 分渠道打包](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/productflavor.gradle)
- [Gradle 配置你的AndroidManifest](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/configManifest.gradle)
- [Gradle 指定你的源码路径、动态去除不需要打包的类·优](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/sourceSet.gradle)
- [Gradle 项目依赖配置](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/project_library.md)
- [Gradle lintOption·优](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/lintOption.gradle)
- [lint报告](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/lint-results-obmDebug.html)
- [Gradle 打包优化配置·优](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/optimization.gradle)
- [Gradle gradle.properties 配置gradle版本和buildTools版本，和一些不便的版本](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/properties.gradle)
- [Gradle 使用variantFilter修改生成apk路径、名字](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/applicationVariant.gradle)
- [Gradle 指定java版本](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/set_java_version.gradle)
- [Gradle packagingOptions解决重复包和文件](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/packageOption.gradle)
- [AndroidStudio常见问题](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/android_studio.xml)
- [Gradle 命令打包apk](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/assemble.md)
- [Gradle 命令行传递参数](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/assembleWithParams.md)
- [Gradle 编译器动态生成java·优](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/operate_file.md)
- [Gradle 创建Task](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/task.md)
- [Gradle 打包选择不同的AndroidManifest.xml](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/diffManifest.md)
- [Gradle 执行顺序](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/exeRank.md)
- Gradle 生成测试报告
- [Gradle 生成接口文档](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/genJavadoc.gradle)
- [AAR 生成](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/aar.md)
- [jar 生成](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/makeJar.md)
- [元编程](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/metaprogramming.md)
- 查看所有tasks命令    *./gradlew tasks --all*

  
#### Gradle高级插件开发
 - [插件开发详细步骤](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/plugin_develop.gradle)
 - [Gradle Transform监听文件编译结束](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/gradle_tranform.gradle)

####Android性能优化
- [apk瘦身优化](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/android_apk_optimization.md) 
- [界面性能UI](https://github.com/UCodeUStory/GradlePlugin/blob/master/source/ui_optimization.md) 


### 问题总结

 - 1.找不到依赖库，需要在repositories中添加jcenter()
 - 2.javassist找不到jar包，就是需要javassist引入jar包
 - 3.发现生成的apk没有变化，删除了build目录重新build，仍然无变化，点击Android Studio setting 清理缓存，重新启动
 - 4.项目app修改名字报错时提示找不到项目，一般根目录.idea就可以解决



