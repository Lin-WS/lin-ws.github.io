---
title: 留言板
date: 2024-12-26 14:25:41
---
{% raw %}<article class="message is-info"><div class="message-body">{% endraw %}
欢迎在这里留言！任何问题都可以在这里留言，我会及时回复的，添加email可以获得更快的回复速度，如果没看见评论框，请刷新！
{% raw %}</div></article>{% endraw %}
<head>
    <script src='//unpkg.com/valine/dist/Valine.min.js'></script>
</head>
<body>
    <div id="vcomments"></div>
    <script>
        new Valine({
            el: '#vcomments',
            appId: 'bKHoo2mBwFrS3Qfz1kGPKRjN-gzGzoHsz',
            appKey: 'wm3bBSkgnqZ3bYnkohHixZVK',
            avatar: 'hide'
        })
    </script>
</body>

