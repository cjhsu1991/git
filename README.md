git 使用筆記

下載 git 工具 : https://git-scm.com/

安裝 git 

設定 git

    1. git config --global user.name "輸入github上的username"
    
    2. git config --global user.email "輸入github上的email address"
    
初始化專案

Clone 別人或自己在github上的 Repository - 切換到git資料夾後執行 git clone "github上的 Repository" (project name) => 如果要設定專案名稱可在最後加上project name

建立一個新的 Repository - 創建一個專案資料夾執行 git init

開始使用git - git 基本功能

 git status - 查看目前 git 狀態
 
 git add - 
 
     上傳特定檔案 - git add "檔案名稱"
 
     上傳所有修改後的檔案 - git add .
 
     (這是尚未完成資料add)
 
 必須在做git commit 才完成 git add 的動作
 
 git commit -m "git_add_test_data.txt(提交訊息)"
 
 Modify data 
  
  git commit -m "modify的檔案名稱"

 Push 
   
   git push -f /*強制覆蓋原有檔案*/
   
   git pull，沒有指定remote 和 branch的情況下，git會採用remote（也就是origin) 來merge在master branch上所有的改變

