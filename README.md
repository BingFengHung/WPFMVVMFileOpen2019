# WPFMVVMFileOpen2019

## 緣由
在開發 WPF 時，通常只能在 Xaml 與 Xaml 的 cs 檔案之間進行切換，
但是 WPF 核心主要是使用 DataBinding MVVM 的模式，一般來說，一個畫面會分為 
View 與 ViewModel 的檔案。

但是，通常只能在 View 畫面時，只能透過手動自行切換到對應的 ViewModel 檔案，
為此，開發一個快捷鍵的 Extension，能夠在 View 與其綁定的 ViewModel 之間快速進行切換。

## 支援
目前支援 Visual Studio 2019 版本

## 開發套件
- Microsoft.VisualStudio.SDK  => 16.0.202
- Microsoft.VisualStudio.Threading => 16.0.102
- Microsoft.VSSDK.BuildTools => 16.0.2264
