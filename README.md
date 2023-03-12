# MoreCommands

## 安装
1. 下载Fabric加载器 [Fabric installer](https://fabricmc.net/use).
   - 按照教程安装Fabric加载器
   - 然后使用你的Minecraft启动器启动一次游戏
1. 下载 [Fabric API](https://minecraft.curseforge.com/projects/fabric)
   将它放进 (`.minecraft/mods`).
1. 下载 [MoreCommands](https://github.com/SmailPangCN/MoreCommands/releases)
   并将其放进 (`.minecraft/mods`).

## 关于
本模组是开源模组，在这里开放下载
本模组给游戏中添加了一些实用的命令

## 编辑
1. 克隆存储库
   ```
   git clone https://github.com/SmailPangCN/MoreCommands
   cd MoreCommands
   ```
1. 生成Minecraft代码
   ```
   ./gradlew genSources
   ```
   - 注意: 如果你使用的Windows，那么请使用 `gradlew` 而不是 `./gradlew`.
1. 将项目导入到IDE中
   1. 如果使用IntelliJ（首选选项），则可以简单地将项目导入为Gradle项目。
   1. 如果您使用Eclipse，则需要`/gradlew-eclipse`，然后将项目作为eclipse项目导入。
1. 编辑代码
1. 在IDE中测试之后，构建一个JAR来测试它是否也在IDE之外工作
   ```
   ./gradlew build
   ```
   JAR可以在“build/libs”目录中找到

## 参与测试
如果你想要参与测试可以在Afdian上赞助Small Fat Server即可获取MoreCommands的测试版
afdian地址： [爱发电](https://afdian.net/a/small-fat-server)

如果你在使用中出现了问题，请在 [提交反馈](https://github.com/SmailPangCN/MoreCommands/issues) 提交
