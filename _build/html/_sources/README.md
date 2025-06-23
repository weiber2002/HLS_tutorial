<h1 align="center">📚 高階合成入門 (HLS Tutorial)</h1>
<p align="center">
  <a href="https://weiber2002.github.io/HLS_tutorial/" target="_blank">👉 線上閱讀</a> ·
  <a href="https://github.com/weiber2002/HLS_tutorial/issues/new" target="_blank">回報問題</a>
</p>

本專案以 **Vivado/Vitis HLS** 為例，從 0 到 1 帶你完成
C → RTL → Verification → Implementation 的流程。  
文章、程式碼、Lab 答案全部開源，歡迎 star／fork。

## 快速開始
```bash
git clone https://github.com/weiber2002/HLS_tutorial.git
cd HLS_tutorial
python -m pip install -r requirements.txt
jupyter-book build .
open _build/html/index.html   # macOS，用 start / xdg-open 亦可
