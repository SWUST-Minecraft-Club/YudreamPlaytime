# 编译依赖

- `libs/MainMenu-mc26.3-plugin-1.10.1-beta.1.jar`：compile/test only; full plugin JAR, not embedded；[来源](https://github.com/SWUST-Minecraft-Club/mcPlugin/tree/2ed15975fd633057321a52cc08b2de8e0d9a21fb/Minecraft-26_3-plugin/MainMenu)。SHA-256 见锁文件。

固定完整插件 JAR 仅用于编译和测试，不能作为精简 API JAR 宣传；运行时由服务器插件类加载器提供类，最终产品不嵌入这些依赖。更新时同时更新 Gradle 路径和锁文件。
