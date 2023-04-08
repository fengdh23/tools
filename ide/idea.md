# 内存优化
```
-Xms4096m 
-Xmx4096m  
-XX:ReservedCodeCacheSize=512m  
-XX:+IgnoreUnrecognizedVMOptions  
-XX:+UseG1GC  
-XX:SoftRefLRUPolicyMSPerMB=50  
-XX:CICompilerCount=2  
-XX:+HeapDumpOnOutOfMemoryError  
-XX:-OmitStackTraceInFastThrow  
-ea  
-Dsun.io.useCanonCaches=false  
-Djdk.http.auth.tunneling.disabledSchemes=""  
-Djdk.attach.allowAttachSelf=true  
-Djdk.module.illegalAccess.silent=true  
-Dkotlinx.coroutines.debug=off  
-XX:ErrorFile=$USER_HOME/java_error_in_idea_%p.log  
-XX:HeapDumpPath=$USER_HOME/java_error_in_idea.hprof  
  
--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED  
--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED  
  
-javaagent:D:\tools\develop\jetbra\ja-netfilter.jar=jetbrains
```

# 插件
