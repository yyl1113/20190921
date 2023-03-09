# Social-Media-Analysis
### 動機和分析目的
每個人都有使用五倍券的權利，希望可以暸解大眾對於五倍券從綁定到領取以及最後使用，情緒上的變化以及看法。

- **2021/10/28 文字雲**
<img width="1010" alt="image" src="https://user-images.githubusercontent.com/55615998/223938243-b669eaae-32e6-43b0-bfad-4611b0e33bbb.png">

- **情緒代表字**
<img width="633" alt="image" src="https://user-images.githubusercontent.com/55615998/223938544-c818cba3-b834-431d-916f-7365840e587d.png">

- **2021/10/28正負情緒代表字**
<img width="326" alt="image" src="https://user-images.githubusercontent.com/55615998/223938612-5e1617b6-8c20-47b7-9042-04b1ab0a37b4.png">

- **正負情緒文章數量統計圖**
<img width="1061" alt="image" src="https://user-images.githubusercontent.com/55615998/223939086-0fc90d10-497b-4730-9f2b-b0a39817875c.png">

- **統計最常出現的bigram組合**
<img width="193" alt="image" src="https://user-images.githubusercontent.com/55615998/223939488-2ef3a6f5-1962-4889-850f-78f257ccf9c1.png">

- **統計最常出現的trigram組合**
<img width="246" alt="image" src="https://user-images.githubusercontent.com/55615998/223939633-7adc429e-d157-4dba-a85d-beec891cec97.png">

- **預測下一個出現的詞**
<img width="735" alt="image" src="https://user-images.githubusercontent.com/55615998/223939833-c0d8c2ae-47c9-413b-9197-e9165adef154.png">

- **Bigram視覺化**
<img width="724" alt="image" src="https://user-images.githubusercontent.com/55615998/223939929-a41226f9-d41c-4c7b-bf51-a9f769eb899a.png">

透過上面所建立的bigram和count,我們選擇最常出現的前30大詞彙組合來製作出該關係圖，可以發現「數位 五倍券」、「數位 綁定」、「數位 支付」這幾個組合線特別粗，代表這幾個組合是最常被提及的字詞組合。  

- **和 紙本, 數位 相關性最高的 15 個詞彙**
<img width="770" alt="image" src="https://user-images.githubusercontent.com/55615998/223940436-9a93209d-1ef4-4bbe-b528-d2295f67611d.png">

由上面兩張圖我們可以看出：和「紙本」相關性最高的前五名詞彙為「數位」、「預訂」、「優惠」、「回饋」、「五倍券」;和「數位」相關性最高的前五名詞彙為「綁定」、「紙本」、「支付」、「加碼」、「振興五倍券」等,可以看出不管是數位還是紙本都在關心優惠。  

- **使用詞彙關係圖畫出相關性大於0.4的組合**
<img width="263" alt="image" src="https://user-images.githubusercontent.com/55615998/223940628-2a1f07bd-d94c-47e4-b65d-ac7658de4fd5.png">
<img width="731" alt="image" src="https://user-images.githubusercontent.com/55615998/223940729-105f6c70-2787-42cf-b140-511bbb92ea85.png">

可以看出此圖與上面bigram視覺化的結果相似，相關性大於0.4的組合有「店家 好食券」、「經濟 振興」、「台北 熊好券」。除了討論五倍券以外其他加碼券的討論聲量也很高。



### 結論
1. 可以看出9/22數位綁定後討論聲量徒增，但是系統不堪負荷導致網友抱怨連連負面情緒高漲
2. 10/08開始使用五倍券後民眾負面情緒有所減緩
3. 可以從相關性看出不管是選擇紙本或是綁定數位的民眾都很在意優惠的部分

