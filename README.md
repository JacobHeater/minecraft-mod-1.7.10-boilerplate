# minecraft-mod-1.7.10-boilerplate
A boilerplate repository for Minecraft 1.7.10 modding.


## Setup

1. Download [JDK 8](https://www.oracle.com/java/technologies/javase/javase8u211-later-archive-downloads.html).
2. Run ` ./gradlew clean setDecompWorkspace eclipse` in your working directory.
3. You should now be able to import the Gradle project in Eclipse.

## Possible Issues

1. `Unable to find javac compiler;`

If you run into this error, you may need to move a file from the JDK folder
to the `JAVA_HOME` path. You can solve this by running the following command.

```bash
sudo cp /Library/Java/JavaVirtualMachines/jdk1.8.0_351.jdk/Contents/Home/lib/tools.jar "/Library/Internet Plug-Ins/JavaAppletPlugin.plugin/Contents/Home/lib/"
```
