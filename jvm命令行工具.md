jvm命令行工具

java Java应用的启动程序  
javac JDK内置的编译工具  
javap 反编译class文件的工具  
javadoc 根据Java代码和标准注释，自动生成相关的API说明文档。  
javah JNI开发时，根据Java代码生成需要的.h文件  
extcheck 检查某个jar文件和运行时扩展jar有没有版本冲突，很少使用  
jdb Java Debugger； 可以调试本地和远端程序，属于JPDA中的一个demo实现，供其他调试器参考。开发时很少使用  
jdeps 探测class或jar包需要的依赖  
jar 打包工具，可以将文件和目录打包成 .jar 文件； .jar文件本质上就是zip文件， 只是后缀不同。 使用时按顺序对应好选项和参数即可。  
keytool 安全证书和密匙的管理工具；（支持生成，倒入，导出等操作）  
jarsigner JAR文件签名和验证工具  
policytool 实际上这是一款图形管理工具，管理本机的Java安全策略  

jps/jinfo 查看java进程  
jstat 查看JVM内部gc相关信息  
jmap 查看heap或类占用空间统计  
jcmd 执行JVM相关分析命令（整合命令）  
jrunscript/jjs 执行js命令  

jmap  
-heap 打印堆内存（内存池）的配置和使用信息。  
-histo 看哪些类占用的空间最多，直方图  
-dump:format=b,file=xxxx.hprof Dump堆内存  

