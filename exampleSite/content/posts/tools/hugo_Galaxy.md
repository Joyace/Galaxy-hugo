---
title: "Hugo主题 Galaxy"
date: 2019-03-20T21:51:00+08:00
categories: [工具]
tags: [Hugo]
---
[Galaxy](https://github.com/JokerQyou/maupassant-hugo) 主题由 [Maupassant](https://github.com/rujews/maupassant-hugo) , [LeaveIt](https://github.com/liuzc/LeaveIt) 两个主题修改而来.

# 设置相关
帖子放在固定的目录 posts 中:

```toml
defaultLayout="posts" # DO NOT CHANGE IT
```


# 帖子格式

- 头部的时间别忘记 +08:00, 我们在东八区
- 同一帖子可以属于多个目录, 所以用 [] 的方式定义分类是更合理的

```markdown
---
title: "Hugo主题 Galaxy"
date: 2019-03-20T21:51:00+08:00
categories: [工具]
tags: ["web","golang"]
---
```

# 参考

- [https://www.gohugo.org/doc/overview/configuration/](https://www.gohugo.org/doc/overview/configuration/)
- [https://timx.cn/post/maupassant/](https://timx.cn/post/maupassant/)