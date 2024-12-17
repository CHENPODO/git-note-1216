# 12/16 Git Note

## 官方文件

- **約定式提交**

  🔗:https://www.conventionalcommits.org/zh-hant/v1.0.0-beta.4/

  **自動化程式**

        - zapier
        - n8n
        - make

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

   **刪除分支** `git branch -d`

8. **透過剪貼到指定分支(但其實他沒有不見)** `git rebase cat`
   A rebase B & B rebase B 結果不太一樣
9. **git reset c4 (become 成那個座標)**

`git reset`
**--mixed** > 工作 /**--soft** >暫存區 /**--hard** > X

- caret ^ 退一步，退回第一個 parents
- tilde ~ ~50 退 50 步

10. **看到`HEAD`移動紀錄** `git reflog`
11. **修訂最後** `git commit -amend`
12. `git rebase -i `
13. `git rebase -continue`

# 12/17 Git Note

14. **更改現有分支到 main**

    `git branch -M main`

15. **新增遠端書籤，origin 可更改喜愛的名稱**

    `git remote add origin -網址 `

16. **SSH KEY 會產生公、私鑰**
17. **http -> github acc**
18. **上傳 main 分支上 origin**
    `git push origin main`
19. **-u = --set-upstream 設定追蹤**

    `git push --set-upstream origin main`

20. `git push origin main:dev`

    **會把 dev 遠端分支刪除**

    `git push origin NULL:dev`

21. **抓取** `git fetch cat main`
22. **發 PR -> Pull Request** `git pull`
    GitLab -> 發 MR -> Merge Request
23. **抓檔案下來**

    `git clone -網址`
