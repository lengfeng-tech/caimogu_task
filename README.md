# 踩蘑菇每天6点影响力

## 配置方式
1.  fork仓库

2. 配置三个仓库参数
   - `OWNER_REPO` 用户名/仓库名
   - `CAI_MO_GU_TOKEN` 踩蘑菇的Token cmg_token
   - `MY_GITHUB_API_TOKEN` githubapiToken 需要读写权限

3. 删除文件
   - run.txt     (记录上一次运行时间)
   - acIds.txt   (记录已经评价的游戏)
   - postIds.txt (记录已经评论的帖子)

## 更新

- 2025.12.10
  - 帖子回复
- 2025.12.12
  - cmgToken问题修复(10-12号之间fork的需要重新修改)
  - 个人主页问题修复
  - 触发器恢复