# 微型问卷系统

## 功能

1. 创建问卷、删除问卷、预览问卷、编辑问卷截止时间
2. 问卷结果统计，样本数据查看，已填写问卷用户查看
3. 使用 Excel 批量导入用户、批量删除用户，单个添加、修改、搜索、删除用户
4. 问卷调查页面适配移动端
5. 问卷单题目交叉分析

## 开发环境

- 安装 [Nginx](http://nginx.org/) 或者 [Apache](http://httpd.apache.org/)，配置 [PHP](http://php.net) 环境，推荐使用 [xampp](https://www.apachefriends.org/download.html), [MAMP](https://www.mamp.info/en/downloads/), [wamp](http://www.onlinedown.net/soft/82112.htm)
- Node.js

## 部署说明

``` bash

# 克隆项目到 Nginx 或者 Apache 的根目录
git clone https://github.com/wuliupo/vue-questionnaire.git

cd vue-questionnaire/front-end

# 安装依赖
npm install

# 本地访问地址：http://localhost:9090
npm run dev

# 线上部署编译
npm run build

```

## 数据库配置

- 数据库配置文件：`api/application/config/database.php`
- 数据库初始化文件： `api/database.sql`

## 打赏给原作者

<https://github.com/52admln/vue-questionnaire>
