# PetShop
petShop 宠物店
项目描述：
1.拥有电商的基础业务和功能，前端主要包括宠物的浏览，查看详情，加入购物车并结算等基础功能；
2.后端采用Bootstrap框架，主要功能是用户管理，订单管理；
3.基于maven开发、Tomcat为引擎Web项目。
4.采用MVC设计模式
Controller层处理用户交互的部分从视图读取数据，控制用户输入，并向模型发送数据；
Service层，负责实现业务逻辑。业务逻辑层以DAO层为基础，通过对DAO组件的正面模式包装，完成系统所要求的业务逻辑。 
DAO层，负责与持久化对象交互。该层封装了数据的增、删、查、改的操作。Daomain层持久化对象，通过实体关系映射工具将数据库的数据映射成对象,实现以面向对象方式操作数据库。
