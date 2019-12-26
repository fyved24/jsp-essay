# jsp-essay
jsp 大三课程设计

## 功能设计

游客

- 查看留言
- 浏览文章
- 搜索文章

用户

- 游客全部功能

- 文章管理

  - 写文章

    > markdown

  - 发布文章

  - 修改文章

  - 文章标签

  - 收藏文章
  - 删除文章

- 留言

- 打赏

  - 仅点赞
  - 打赏金额

- 余额

  - 查看收入
  - 充值

管理员

- 修改文章权值
- 删除文章
- 置顶文章



系统逻辑

- 文章权值 

  > x=点赞数，y=打赏金额
  >
  > $w=0.2x+0.8y$





### 页面设计



通用部分

1. header

   - 首页
   
   - 用户中心
   
     > 未登录是**登录/注册**
   
2. footer

   > created by fyved24 with ♥

页面分析

1. 登录页面

   - body 

     > 登录

2. 个人中心页面

   - left

     > - 最近五篇文章
     > - 最近五篇收藏
     > - 天气  ??

   - 组成

     - 中心
     
       > 最近浏览量
     
     - 收藏页面
     
       > 收藏列表
     
     - 文章管理页面

3. 写作页面

   - body 

     > 编辑框

4. 首页

   - body

     > 最近权值比较高的文章
     
   - left 
   
     > 天气
   
5. 文章查看页面

   - body

     > 文章

   - left

     > 打赏按钮