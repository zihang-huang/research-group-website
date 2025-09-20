---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: 组内成员
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - 导师
        - 博士研究生
        - 硕士研究生
        - 访问研究生

      sort_by: Params.role
      sort_ascending: true
    design:
      show_interests: false # 在成员下方显示研究兴趣
      show_role: true # 在成员下方显示职位
      show_social: true #在成员下方显示相关链接的跳转按钮
---