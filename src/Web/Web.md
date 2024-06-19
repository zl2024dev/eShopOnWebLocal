Web 展示层
Areas 区域 
Configuration 服务注册
Controllers
Extensions
Features 功能 用到Core Specifications内的规约
HealthChecks 数据库，接口等检查
Interfaces 页面呈现需要的接口 VModelservices
Pages raz页面
Services raz页面调用获取数据的服务
ViewModels 页面展示需要的 VModel
Views

--
顺序
Routing-->Controllers-->Action-->Features-->{Features}Handler-->Core.Specifications-->{Infrastructure.Data.Config}-->Core.Entites-->ViewModels--------->Controller-->return Views
Routing---------------->Pages-->Interfaces-->Services---------->Core.Specifications-->{Infrastructure.Data.Config}-->Core.Entites-->Pages.{}ViewModel-->Pages------->return 
