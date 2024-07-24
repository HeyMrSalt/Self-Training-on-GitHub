# Self-Training-on-GitHub

- [20240721 Practice using Fork with Nicky and QQhan](#20240721-practice-using-fork-with-nicky-and-qqhan)
- [20240725 Git Commit Message Conventions](#20240725-git-commit-message-conventions)

## 20240721 Practice using Fork with Nicky and QQhan

Note1 : User Clone to local computer ready for editing\
Note2 : Use command line and cd to Clone file\
Note3 : After editing, `git add .`\
Note4 : After, `git commit -m "MESSAGE"` (MESSAGE : What would you like to describe)\
Note5 : You can use `git status` to see the status\
Note6 : You can use `git branch -a` to Confirm branch and Remote repository\
Note7 : After, `git push`\
Note8 : After, Pull request (Pull request is executed using the web page)\
Note9 : After, Merge

---

## 20240725 Git Commit Message Conventions

feat: 新增/修改功能 (feature)\
fix: 修補 bug (bug fix)\
docs: 文件 (documentation)\
style: 格式 (不影響程式碼運行的變動 white-space, formatting, missing semi colons, etc)\
refactor: 重構 (既不是新增功能，也不是修補 bug 的程式碼變動)\
perf: 改善效能 (A code change that improves performance)\
test: 增加測試 (when adding missing tests)\
chore: 建構程序或輔助工具的變動 (maintain)\
revert: 撤銷回覆先前的 commit 例如：revert: type(scope): subject (回覆版本：xxxx)

![image](https://github.com/user-attachments/assets/2209c595-eed5-4b62-8957-139e1cdd22a1)

舉例來說 如果我今天要新增 Commit 內容為新增暗黑模式瀏覽功能 我們可以這樣下

git commit -m '\
feat: dark mode added
Users can switch to dark mode through the menu in the upper right corner to browse\
-\
'

Refer : [AngularJS Git Commit Message Conventions](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit#heading=h.greljkmo14y0)

---
