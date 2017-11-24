# simple-swagger2
通过配置的方式来玩swagger2

使用方式 
公用的启用swagger代码 修改配置就可以

```yaml
swagger:
  enable: true
  o-auth2:
    enable: true
    app-key: basic-api
    app-name: 基础api
    authorization-url: http://39.108.51.1/se/oauth/authorize
  apis:
    user:
      packageName: com.jing21.learn.basic.api.user.controller
      author:
        name: dev1
    system:
      packageName: com.jing21.learn.basic.api.controller
      author:
        name: dev2
      title: dev2 API
      description: 接口文档
    
```  
 
具体的配置查看`SwaggerProperties`