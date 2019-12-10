# 使用说明

下载后根据业务需要：

- 修改文件夹名称。
- 修改 docker-compose.yml 相关参数。

创建容器后将生成两个文件夹：

- `db_data`：存放 MYSQL 文件，对应容器内的 `/var/lib/mysql` 路径。
- `wp_site`：存放 WordPress 文件，对应容器内的 `/var/www/html` 路径。

## 待办

- [ ] 完善各种可用参数说明。
- [ ] 为 WordPress 创建专门的 Docker 组用户，规避安全风险。
- [ ] 补充时区同步参数。