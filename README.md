# Honoka Maven Repository
[![License](https://img.shields.io/github/license/kosaka-bun/maven-repo?label=License&color=blue&logo=Github)](./LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/kosaka-bun/maven-repo?label=Stars&logo=GitHub)

## 简介
本仓库主要用于存储由[Kosaka Bun](https://github.com/kosaka-bun)所开发的几款Java与Kotlin类库与框架，亦用于存储某些在Maven中心仓库中不存在的依赖库。

请参阅：[Maven示例](./example/maven)&emsp;[Gradle示例](./example/gradle)

其包含：

[![honoka-sdk](https://github-readme-stats.vercel.app/api/pin/?username=kosaka-bun&repo=honoka-sdk)](https://github.com/kosaka-bun/honoka-sdk)
[![qqrobot-sdk](https://github-readme-stats.vercel.app/api/pin/?username=kosaka-bun&repo=qqrobot-sdk)](https://github.com/kosaka-bun/qqrobot-sdk)

本仓库仅用于存储和托管文件，不保存更新记录，因此可能随时进行多次force push。

## 使用
### Maven
```xml
<repositories>
    <repository>
        <id>honoka-maven-repo</id>
        <url>https://raw.githubusercontent.com/kosaka-bun/maven-repo/master/repository/</url>
    </repository>
</repositories>
```
或
```xml
<repositories>
    <repository>
        <id>honoka-maven-repo</id>
        <url>https://www.honoka.de/maven-repo/</url>
    </repository>
</repositories>
```

### Gradle
```groovy
repositories {
    mavenCentral()
    maven {
        url 'https://raw.githubusercontent.com/kosaka-bun/maven-repo/master/repository/'
    }
}
```
或
```groovy
repositories {
    mavenCentral()
    maven {
        url 'https://www.honoka.de/maven-repo/'
    }
}
```
