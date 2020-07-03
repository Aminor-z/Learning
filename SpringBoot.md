### Spring Boot中参与数据传输的都需要加入一下一种控制器：
    @Controller 渲染控制器  
    @RestController 无渲染控制器
### 获取参数
    object Function(@RequestParam("param") String _param){return object}