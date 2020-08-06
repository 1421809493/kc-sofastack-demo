# 学习SOFA的“快速”开始
原地址：  
https://www.sofastack.tech/  
https://github.com/sofastack-guides/kc-sofastack-demo.git  

## 遇到的坑
* 本地没管理员权限，无法安装sofa-register  
* 浏览器报CORS（has been blocked by CORS policy）
* MYSQL5.7报错（ONLY_FULL_GROUP_BY）  

#### 一、本地没管理员权限，无法安装sofa-register

使用直连模式directurl。  

#### 二、浏览器报CORS（has been blocked by CORS policy）

增加过滤器，补充responsehead  

#### 三、 MYSQL5.7报错（ONLY_FULL_GROUP_BY）

修改mysql配置  

