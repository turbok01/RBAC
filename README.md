# RBAC
# 一 目录
# 2020/1/7
课时86

查询所有菜单权限sys_perssion 三层架构


# 2020/1/8
课时87

查询菜单权限树装结果递归查询返回

sys_permission菜单权限表

# 2020/1/12
课时88

新增菜单权限，返回菜单列表

课时89

查询角色分页权限

# 2020/1/13
课时90

查询所有权限到按钮

新增角色

# 2020/1/14
91角色查询


# 2020/1/16
总结

# 2020/1/17

92 部门管理 查询所有列表

93 返回部门树

94 新增部门

95 用户管理

96 新增用户

97 用户管理支持多条件查询
# 2020/1/18
98 赋予用户角色

# 2020/1/19
99 jwt自动刷新

100 编辑用户

# 2020/1/21
101 用户删除 批量删除

102 菜单权限编辑

103 删除菜单权限

# 2020/1/28

104 编辑角色
	1）先获取角色信息
	2) 更新角色

105 删除角色

106 编辑部门

107 删除部门

108 日志管理

109 日志分页

110 日志多条件查询

111 删除日志 物理删除

112 接口管理，SQL监控，登出

113 首页用户信息 查询 编辑

114 用户编辑密码

115 加用户权限

116 前端无权限的反应 前端+权限控制

117 不懂

118 不懂


# 二 思路

## 1）实际背景（编）
## 2）梳理整个项目
	* 功能
	* 有哪些模块
	* 数据库哪几张表
## 2）自己仍需要搞清楚的点及亮点
* shrio的认证详细流程
	* 找博客介绍
	* 看课程介绍shiro的pdf
	* 项目中的使用
	* token--jwt token
* 前端vue怎么权限控制
	* 找博客
* redis
	* 看课程介绍shiro的pdf
	* 项目中的使用
* mysql
	* 涉及哪些连表查询
	* 调优	
* 接口的输出结果做了一个Result封装（接口规范）
	* 回顾pdf
* 对错误的代码做了一个CodeMsg的封装（错误代码规范）
	* 回顾pdf
## 3）遇到的困难
* 117，118
* 没想好

## 4）参考
* 三份简历
* [类似博客补充维提](https://blog.csdn.net/weixin_44417042/article/details/106858739)
* [亮点参考](https://blog.csdn.net/qq_36281031/article/details/104699492?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522161183251316780265464873%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fblog.%2522%257D&request_id=161183251316780265464873&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_v2~rank_v29-1-104699492.pc_v2_rank_blog_default&utm_term=%E9%A1%B9%E7%9B%AE&spm=1018.2226.3001.4450)