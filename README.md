# C-
C#初學

✅ 方式一：使用 dotnet run（推薦，最穩定）
✅ 步驟如下：
1️⃣ 打開終端機（cmd）切到你的 .cs 資料夾：
bash

cd "C:\Users\Leon\Desktop\程式語言資料\C#"
2️⃣ 建立一個 C# 專案（只需做一次）：
bash

dotnet new console -n HelloApp
這會自動產生 HelloApp 資料夾，裡面包含一個預設的 Program.cs 與 .csproj 專案設定檔。

3️⃣ 將你的 hello.cs 內容複製到 HelloApp\Program.cs 裡面覆蓋掉
或者直接把 hello.cs 改名成 Program.cs 蓋過去也行。

4️⃣ 執行專案：
bash

cd HelloApp
dotnet run
🎉 這樣你的 hello.cs 就會執行起來啦！

