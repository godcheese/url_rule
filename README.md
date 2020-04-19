# url_rule
Web 开发时对设计 URL 约定俗成的规则。
## API URL，约定前缀加“/api/”
- 示例：http://example.com/api/
## URL 约定为小写字母，单词之间用英文下划线（“_”）分割
- 示例：get_entity、get_user、send_something
## 获取单个实体数据
- 示例：get_entity、get_user、get_something
- HTTP 方法: GET
## 获取多个实体数据
- 示例：list_entity、list_user、list_something
- HTTP 方法: GET
## 获取分页数据
- 示例：page_entity、page_user、page_something
- HTTP 方法: GET
## 获取分页数据
- 示例：page_entity、page_user、page_something
- HTTP 方法: GET
## 提交数据
- 示例：add_user、change_password
- HTTP 方法：POST

> - 参考资料：http://www.ruanyifeng.com/blog/2014/05/restful_api.html