## 码匠社区

## 资料
- [Spring Web 文档](https://spring.io/guides/gs/serving-web-content/)
- [elastic 社区](https://elasticsearch.cn/explore)
- [Github OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)
- [Bootstrap 文档](https://v3.bootcss.com/components/)
## 工具
- [Git](https://git-scm.com/downloads)

## 脚本
```sql
create table user
(
    id           int auto_increment
        primary key,
    account_id   varchar(100) null,
    name         varchar(50)  null,
    token        char(36)     null,
    gmt_create   bigint       null,
    gmt_modified bigint       null
);
```