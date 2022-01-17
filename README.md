# electron
electron demo


https://dotblogs.com.tw/explooosion/2018/03/25/181604

npm run build

electron-packager . AlarmClock：把當前目錄 . 打包起來，並將應用程式命名 AlarmClock
--out AlarmClock：輸出資料夾於 AlarmClock，產出後預設資料夾為 AlarmClock-win32-x64

--overwrite：如果已經存在資料夾和檔案，會進行覆寫

--platform=win32：平台為 Windows（Mac: darwin, Linux: linux）

--arch=x64：應用程式 64位元（ia32, all）

--icon=clock.ico：應用程式 ICON

--ignore=node_modules/electron-*：忽略的檔案

--electron-version=1.7.9：electron 的核心版本

--version-string.CompanyName=Robby：軟體公司名稱（顯示於軟體資訊中）

--version-string.ProductName=AlarmClock：軟體名稱（顯示於軟體資訊中）

---------------------------------------------------------------------------------------------------

** Git LFS 原理、大小檔案都適用
https://haway.30cm.gg/git-lfs/

https://gitbook.tw/chapters/faq/remove-files-from-git