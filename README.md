# 安裝方式

把 `My Exported Templates` 的目錄，複製到類似的位置，通常在【我的文件】的 Visual Studio 底下

 - `C:\Users\Mac\Documents\Visual Studio 2019\Templates\ItemTemplates`
 - `C:\Users\Mac\Documents\Visual Studio 2019\Templates\ProjectTemplates`
 
### 針對使用 Visual Studio 2019 的用戶
然後，在 CMD 執行 Visual Studio User Data 清空指令 (注意，這會清掉 User Data)

*如果不這麼做， Visual Studio 將不會讀到這些範本，這似乎是 Visual Stduio 2019 的 Bug
```
devenv.exe /Resetuserdata
```

# 注意事項

當你啟動一個範本，可能會跳錯找不到參考，這時候請自行手動指定位置到 `xxxx\SharpDevelop-5.0.0\bin` Sharpdevelop 的 `bin` 目錄。
