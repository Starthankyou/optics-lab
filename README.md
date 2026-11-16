# 面鏡與透鏡成像互動實驗室
這是一份國中理化光學教材。拖曳物體、改變焦距或移動紙屏，就能觀察像的位置、大小和方向如何變化。教材涵蓋平面鏡、凹面鏡、凸面鏡、凹透鏡與凸透鏡，並提供同步比較、生活應用、成像總表和練習題。

線上教材　發布後，可在本專案的 Settings → Pages → Visit site 找到網址。請將該網址分享給學生。
操作方式
1. 選擇鏡種。 拖曳畫布上的物體，或用物距滑桿與焦點位置按鈕改變物距。
2. 切換光路。 選「作圖光線」，逐條觀察用來判斷像位置的光線。選「光束」，看物體頂端與底部發出的光如何會聚或發散。畫面上的實線表示光的行進路徑，虛線表示反向延伸。
3. 移動紙屏。 把紙屏拖到實像的位置，觀察投影變化。再把凸透鏡前的物體移到焦點內，試試能否用紙屏接到看到的像。
4. 做對照。 在同步比較頁用同一個滑桿改變四種凹凸面鏡與透鏡的物距，觀察像移動的方向。
可用電腦瀏覽器操作。頁面也提供手機排版和觸控拖曳，實機觸控尚待驗證。分享前可用手機直向試拖物體與紙屏，再切換一次光路。頁面會透過網路載入 Tailwind CSS，完整樣式需要網路連線。
安裝與發布
這個專案使用單一 HTML 檔，可直接用瀏覽器開啟 index.html。部署到 GitHub Pages 時也可以直接上傳，無須安裝套件或編譯。
1. 若教材檔名是 optics-lab.html，先改成 index.html。
2. 在 GitHub repo 的 Code → Add file → Upload files 上傳 index.html，將它與 README.md 放在同一層，提交到 main。
3. 到 Settings → Pages，將 Source 設成 Deploy from a branch，選擇 main 和 /(root)，再按 Save。GitHub Free 可使用公開 repo 部署，repo 內的教材原始碼也會公開。
4. 發布完成後，從 Settings → Pages → Visit site 打開教材。若 repo 名稱為 optics-lab，網址通常是 https://你的帳號.github.io/optics-lab/。
5. 日後把新版上傳到同一位置，更新 index.html 並提交即可。若出現 404，先確認首頁檔名與發布分支，再到 Actions 查看部署狀態。
參考來源
- Ray Optics Simulation 提供光束、反向延伸線和觀察位置的設計參考。
- PhET Geometric Optics 提供光路顯示與紙屏操作的設計參考。
- GitHub Pages 發布設定
