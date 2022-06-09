# BringFido 待解決的問題

1. search_ctr 的藍色 submit 想要靠右
2. div.rating 加了 display: flex 骨頭就不見
   加的目的是希望骨頭在 rating 旁邊
3. search_filter 裡的 All Restaurants, Rating, Search Within Resaults 希望彼此中間有固定空隙，這種只能個別寫 margin 來隔開嗎？因為 space-around 會變成這三個擴展到整列，我不想要他們這麼寬

[2022.06.07 fixed]

1. 希望整體內容都會放在左右間隔固定寬度的 container 裡面
2. header 的 nav 希望可以靠左
   div.hdr_segment 的則是靠右(不過一樣都會放在 1.的 container 裡)
3. search-container 我直接卡住，怎麼搜尋都找不到解法，這部分能不能看你寫一次程式 QQ
4. 文字 LATEST FROM THE BLOG 因為 section.third 裡面的 align-items: center，所以我文字沒辦法靠左，text-align:left 也不會動
5. [其他微調-> 試試看 james 教了 container 和 footer 以後我自己會不會改] - sub_footer 的 footer_left 希望可以靠左
   footer_right 的則是靠右(不過一樣都會放在 1.的 container 裡)
