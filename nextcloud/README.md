## 部署

修改相关参数。

```
docker-compose up -d
```

## 查看日志

```
docker logs nextcloud_db // 查看数据库配置是否完成
docker logs nextcloud_web // 查看 nextcloud 是否配置完成
```

## 添加信任域名

打开 `nextcloud/config/config.php` 文件，找到以下配置：

```
'trusted_domains' =>
array (
  0 => 'localhost',
  1 => 'nextcloud.***.com',
),
```

根据需要添加域名。
