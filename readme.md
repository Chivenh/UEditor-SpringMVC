### UEditor SpringMVC 版
     和jsp版区别主要是配置初始化部分和文件上传部分做了修改
     初始化修改为请求:Controller,在SpringMVC控制器中返回配置参数,并映射其它如:上传文件等命令的执行.
#### 注意:除了 json.jar 包外,其它包使用SpringMVC项目环境中的包,没有再附加到UEditor-1.4.3.jar包中. 