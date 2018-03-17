# Python-Machine-Learning
>This is a note which studying Machine Learning with python, you could learn it with me if you want.
>　Welcome to contact me by send a mail or issues ~
# AI學習筆記
> [常見名詞觀念釐清](https://www.zhihu.com/question/57770020)
![](https://i.imgur.com/EOiLBrj.jpg)

## 人工智能的範疇
![](https://pic1.zhimg.com/80/v2-e358e127afbe5963f5b8622e2dd5b49f_hd.jpg)

* 專家系統
* 機器學習
* 進化計算
* 模糊邏輯
* 計算機視覺
* 自然語言處理
* 推薦系統等

## 機器學習
[William Mou's Github](https://github.com/William-Mou/Python-Machine-Learning)

* 傳統算法
    * 決策樹
    * 聚類
    * 貝葉斯分類
    * 支持向量機
    * EM
    * Adaboost
* 學習方法的分類  
    * 半監督學習
    * 集成學習
    * 深度學習
    * 監督學習（如分類問題）
        * 分類法
            1. 訓練數據集中學習
            2. 回歸分析導出模型
            3. 對新數據做出預測
        * 回歸預測
            1. 預測變數+反映變數
            2. 發覺變數間的關係
            3. 找出變數的適合曲線 
    * 強化學習
        1. 與環境互動改善自身技能
        2. 透過測量函數回傳度量質
        3. 透過方式最大化獎勵：
            * 嘗試錯誤
            * 審議式規劃
    * 非監督學習（如聚類問題）
      沒有已知的結果和獎勵函數，透過探索數據本身的結構得到資訊
        1. 探索式數據分析技術
        2. 允許組織技術至有意義的「子族群」
        3. 使特徵有一定程度的相似性，發現特殊分群

### 深度學習，一種實現機器學習的技術
* 背景
    > 深度學習本來並不是一種獨立的學習方法，其本身也會用到有監督和無監督的學習方法來訓練深度神經網絡。但由於近幾年該領域發展迅猛，一些特有的學習手段相繼被提出（如殘差網絡），因此越來越多的人將其單獨看作一種學習的方法。

    > 最初的深度學習是利用深度神經網絡來解決特徵表達的一種學習過程。深度神經網絡本身並不是一個全新的概念，可大致理解為包含多個隱含層的神經網絡結構。為了提高深層神經網絡的訓練效果，人們對神經元的連接方法和激活函數等方面做出相應的調整。

* 缺點

    1. 深度學習模型需要大量的訓練數據，才能展現出神奇的效果，但現實生活中往往會遇到小樣本問題，此時深度學習方法無法入手，傳統的機器學習方法就可以處理。
  
    2. 有些領域，採用傳統的簡單的機器學習方法，可以很好地解決了，沒必要非得用複雜的深度學習方法。
  
    3. 深度學習的思想，來源於人腦的啟發，但絕不是人腦的模擬，舉個例子，給一個三四歲的小孩看一輛自行車之後，再見到哪怕外觀完全不同的自行車，小孩也十有八九能做出那是一輛自行車的判斷，也就是說，人類的學習過程往往不需要大規模的訓練數據，而現在的深度學習方法顯然不是對人腦的模擬。

* 理念
    >Science is NOT a battle, it is a collaboration. We all build on each other's ideas. Science is an act of love, not war. Love for the beauty in the world that surrounds us and love to share and build something together. That makes science a highly satisfying activity, emotionally speaking!
    >
    >這段話的大致意思是，科學不是戰爭而是合作，任何學科的發展從來都不是一條路走到黑，而是同行之間互相學習，互相借鑒，博採眾長，相得益彰，站在巨人的肩膀上不斷前行。機器學習的研究也是一樣，你死我活那是邪教，開放包容才是正道。
