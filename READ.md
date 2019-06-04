## 我的Sprint boot 学习

## 资料
[Spring 文档](https://spring.io/guides)
[Spring 例子](https://spring.io/guides/gs/serving-web-content/)
[Bootstrap 文档](https://v3.bootcss.com/getting-started/)
[Github OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)


## 工具
[Git 下载](https://git-scm.com/download)

## 脚本
```sql
create table USER
(
  ID           INT auto_increment NOT NULL,
  ACCOUNT_ID   VARCHAR(100),
  NAME         VARCHAR(50),
  TOKEN        CHAR(36),
  GMT_CREATE   BIGINT,
  GMT_MODIFIED BIGINT,
  constraint USER_PK
    primary key (ID)
);
```