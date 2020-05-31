# SS-Plugin

## 関係図
![プラグイン関係](https://github.com/sya-ri/SS-Plugin/raw/master/SS-Plugin.png)

[draw.io](http://draw.io/)

## レポジトリ
### - [SS-Kotlin](https://github.com/sya-ri/SS-Kotlin) v1.3
### - [SS-Core](https://github.com/sya-ri/SS-Core) v2.10
### - [SS-World](https://github.com/sya-ri/SS-World) v1.1
### - [SS-Battle](https://github.com/sya-ri/SS-Battle) v1.0-dev
### - [SS-Item](https://github.com/sya-ri/SS-Item) v1.0-dev
### - [SS-Job](https://github.com/sya-ri/SS-Job) v1.0-dev
### - [SS-GUI](https://github.com/sya-ri/SS-GUI) v1.0-dev
### - [SS-Economy](https://github.com/sya-ri/SS-Economy) v1.0
### - [SS-Votifier](https://github.com/sya-ri/SS-Votifier) v1.1
### - [SS-Chat](https://github.com/sya-ri/SS-Chat) v1.0
### - [SS-Discord](https://github.com/sya-ri/SS-Discord) v1.0

## [mvn-repo](https://mymavenrepo.com/repo/It7YYM2R0nvQscV8EThI/)
### build.gradle.kts
```build.gradle.kts
repositories {
    maven {
        url = uri(properties["ssMavenRepoURL"] as String)
    }
}
```

### gradle.properties
```
ssMavenRepoURL=https://mymavenrepo.com/repo/It7YYM2R0nvQscV8EThI/
```
