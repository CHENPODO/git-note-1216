# 12/16 Git Note

## 官方文件

- **約定式提交**

  🔗:https://www.conventionalcommits.org/zh-hant/v1.0.0-beta.4/

  - snapshot 快照
  - 工作目錄 Working Directory
  - 暫存區 Staging Area
  - 儲存區 Repository

## 指令

1. **初始化** `git init`
2. **狀態** `git status`
3. **加入暫存區** `git add`

   那個點是 here `git add .`

   全部加入 `git add --all -A`

4. **留言** `git commit -m 'first commit'`
5. **del** > 恢復 新指令`git restore`

   暫存區(add) >= 存 (commit)

6. **歷史紀錄** > 作者、日期

   退出 q `git log`
   `git log --oneline`

7. **分支** `git branch `

   **開分支** `git branch cat`

   **切換分支** 新指令`git switch cat` 舊指令`git checkout cat`

   **分離分支**

   **刪除分支** `git branch -d `

<<<<<<< HEAD
8.
9.
=======
8. **合併分支** `git merge`
9. **可以看手冊** `git help`
>>>>>>> c7146aab2001e394d01abb1702bbd664c76ce3c5
