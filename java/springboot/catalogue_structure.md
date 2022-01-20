### springboot 项目目录结构

#### 顶级目录结构
* 项目根目录/src/main/java：放置项目Java源代码
* 项目根目录/src/main/resources：放置项目静态资源和配置文件
* 项目根目录/src/test/java：放置项目测试用例代码

 
而位于/src/main/java目录下各个目录详细介绍：
```
|_annotation：放置项目自定义注解
|_aspect：放置切面代码
|_config：放置配置类
|_constant：放置常量、枚举等定义
   |__consist：存放常量定义
   |__enums：存放枚举定义
|_controller：放置控制器代码
|_filter：放置一些过滤、拦截相关的代码
|_mapper：放置数据访问层代码接口
|_model：放置数据模型代码
   |__entity：放置数据库实体对象定义
   |__dto：存放数据传输对象定义
   |__vo：存放显示层对象定义
|_service：放置具体的业务逻辑代码（接口和实现分离）
   |存放业务逻辑接口定义
   |__impl：存放业务逻辑实际实现
|_utils：放置工具类和辅助代码
```