# CS_NOTE
nano Ctrl C：顯示游標所在
     Ctrl W：查詢命令，按下後會跳轉到末行的反白位置，輸入要查詢的內容在回車及可。
vi/vim 一般模式：可使用上下左右進行游標 宜動、刪除字元及複製貼上檔案 資料 。
       編輯模式：編輯文字
       命令列模式  :w  將編輯的資料寫入硬碟檔案中
                  :q  離開
                  :wq 儲存後離開(若為 :wq!則為強制儲存後離開)
                  :w[filename] 將編輯的資料儲存成另一個檔案（類似另存新檔）
                  :r[filename]在編輯的資料中，讀入另一個檔案的資料
                  :set nu顯示行號，設定後會在每一列的自首顯示該列的行號
                  ！為 強制 的意思
gz ip
    壓縮：gzip File Name
    解壓縮：  gun zip  File Name. gz
             gz ip -  dFile Name. gz
xz
  壓縮：xz - zFile Name
  解壓縮：xz -dFile Name.xz
tar. gz
  壓縮：tar -  zcvf File Name.tar.gz DirName
  解壓縮：tar -  zxvf  File Name.tar.gz
which filename
  -n <文件名长度>指定文件名長度，指定的長度必須大於或等於所有文件中最長的文件名。
  -p <文件名長度>與-n参數相同，但此處的<文件名長度>包括了文件的路徑。
  -w指定輸出欄位的寬度。
  -V顯示版本訊息。


