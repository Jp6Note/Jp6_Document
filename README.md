# GitBook 建構步驟

PS: VScode ctrl+shuft+v 可以即時更新 markdown

```Bash
#GitBook 建構步驟
Step1. 辦一個gmail
Step2. 辦一個github並建立Repo
Step3. 使用github登陸gitbook
Step4. Integration gitbook with github
Step5. 同步文件資料夾: Jp6-Document
Step6. 簡單測試文件修改後上傳
Step7. 測試小烏龜上傳
```

### Jp6 GitBook Repo
https://github.com/Jp6Note/Jp6_Document   #github repo

https://jp6note.gitbook.io/jp6-document/  #GitBook

https://app.gitbook.com/@jp6note/spaces   #GitBook 管理頁面



### IAC GitBook Repo
https://github.com/IAC-Document/Doc.git       #github repo

https://peng-daniel.gitbook.io/iac-document/  #GitBook

https://app.gitbook.com/login                 #GitBook 管理頁面




# gitbook 同步命令整理

情境一: 同步IAC-Doucment
```Bash
mkdir gitbook
cd gitbook
git clone https://github.com/Jp6Note/Jp6_Document
git pull
```

情境二: 修改README.md文件並上傳
```Bash
先用editor修改README.md內容

然後執行以下命令: 
git add README.md
git commit -m "fix README.md"
git push -u origin main
```
