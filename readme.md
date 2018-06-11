## 下载安装
如果没有搭建环境： [宝塔搭建laravel所需要的lnmp环境linux-nginx-mysql-php-composer-git](https://baijunyao.com/article/149)  
如果不熟悉laravel项目的安装使用： [如何正确的下载安装使用别人的laravel项目？](https://baijunyao.com/article/148)  
针对博客的说明：[开源项目系列之laravel-bjyblog博客](https://baijunyao.com/article/129)  
最后需要初始化全文搜索的索引；  
```bash
php artisan scout:import "App\Models\Article"
```
关于全文搜索具体的可以查看文章；  
[laravel下TNTSearch+jieba-php实现全文搜索](https://baijunyao.com/article/154)
## 项目介绍
1. 纯手工前台响应式页面布局适配PC、平板、手机；
2. 带表情的ajax无限级评论系统；
3. 队列邮件通知；
4. QQ、微博、github第三方登录；
5. markdown 编辑器；

## 版权
项目使用 MIT 协议；免费开源可随意使用；

