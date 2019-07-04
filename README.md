# study-flowable
## UI模块与API的联系

flowable为我们提供的UI模块与API要有关联的话,必须操作同一张表,这样才能保证两者之间的关联。以IDM-UI为例,当我们通过代码的IdentityService新增用户、组、权限的时候,如果与IDM-UI连接的同一个数据库的话,那么代码新增的用户UI模块也能看到。UI模块新增的用户通过我们的java代码也能查询出来。

以上就完成了UI模块与我们生产代码的关联。