---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<!-- Gitalk 评论 start  -->

<!-- Link Gitalk 的支持文件  -->
<link rel="stylesheet" href="https://unpkg.com/gitalk/dist/gitalk.css">
<script src="https://unpkg.com/gitalk@latest/dist/gitalk.min.js"></script> 
<div id="gitalk-container"></div>     
<script type="text/javascript">
    var gitalk = new Gitalk({
    // gitalk的主要参数
		clientID: `6d7f2e49feee9ae1b52e`,
		clientSecret: `ff52f7926ca1ec59962baf59cbc8c6ded9ed705d`,
		repo: `BlogPingLun`,
		owner: 'miaooo0000OOOO',
		admin: ['miaooo0000OOOO'],
		id: 'index'
    });
    gitalk.render('gitalk-container');
</script> 
<!-- Gitalk end -->