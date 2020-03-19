# shmily-cnblogs-theme

## 主题介绍

1. 风格简约、响应轻快
2. 摒弃 jQuery，使用原生 JS
3. 兼容 IE 9 及以上浏览器
4. 支持 PC、手机双端响应式设计

## 快速使用

1. 在博客园后台设置界面申请 js 权限

2. 将博客园主题设置为 BlueSky

3. 按照文件名将代码复制到设置界面的对应文本框中

4. 勾选 css 代码框下的禁用模板默认CSS

5. 在页脚 HTMl 代码中，设置 profile 以调整个人参数，设置 news 以调整首页滚动公告

   followId 可以在任意一篇博文页面，进入 f12 开发者工具栏搜索”follow“，结果如“follow('54ceedb5-de8f-4136-e346-08d7804a3aa0')”，括号内字符串即为 followId

   ```
   <!--parameter-->
   <script type="text/javascript">
       var profile = {
           "icon": "https://blog-static.cnblogs.com/files/pgjett/favicon.ico",
           "logo": "https://blog-static.cnblogs.com/files/pgjett/logo.ico",
           "github": "https://github.com/pgjett",
           "links": "https://www.cnblogs.com/pgjett/p/12294879.html",
           "about": "https://www.cnblogs.com/pgjett/p/12294875.html",
           "mail": "http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=eAgfEh0MDDgJCVYbFxU",
           "followId": '54ceedb5-de8f-4136-e346-08d7804a3aa0'
       };
       var news = [
           {
               "title": "武汉加油，中国加油！",
               "url": "javascript:;"
           },
           {
               "title": "努力永远不会太迟。",
               "url": "javascript:;"
           }
       ];
   </script>
   ```

## 注意事项

1. 博文封面设置

   在编辑随笔时插入摘要图片，请使用占用较小的图片，并且将插入的标签 src 改成 data-src，可以实现图片懒加载 ，更快进入首页，提升浏览体验

2. IE 浏览器显示问题
