# RuoYi-Geek-SpringBoot3核心逻辑理解

<img align="right" src="./images/流程图1.png" alt="basectr流程图" width="500"/>

## 分页处理

1、startPage：开始分页。

2、startOrderBy：设置排序规则。

3、clearPage：清理分页线程变量。

4、getDataTable：返回分页数据，包含总记录数和当前页的数据列表。

## 响应处理

1、success：返回成功消息（无参数）。

2、error：返回失败消息（无参数）。

3、success(String message)：返回带有自定义消息的成功响应。

4、success(Object data)：返回带有数据的成功响应。

5、error(String message)：返回带有自定义消息的失败响应。

6、warn(String message)：返回带有警告消息的响应。

7、toAjax(int rows)：根据影响行数返回成功或失败响应。

8、toAjax(boolean result)：根据布尔结果返回成功或失败响应。

## 用户信息获取

1、getLoginUser：获取当前登录用户的缓存信息。

2、getUserId：获取当前登录用户的 ID。

3、getDeptId：获取当前登录用户的部门 ID。

4、getUsername：获取当前登录用户的用户名。

5、redirect(String url)：页面跳转。
