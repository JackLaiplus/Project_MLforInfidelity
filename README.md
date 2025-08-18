# Project_MLforInfidelity

在現代婚姻研究中，外遇行為不僅影響家庭穩定與伴侶、親子關係，也與心理健康、社會價值觀和生活滿意度息息相關。然而，外遇行為的成因往往複雜，涉及個人、伴侶與社會多層面因素。隨著人工智慧（AI）的發展，透過機器學習（Machine Learning, ML）技術進行行為數據分析，提供了新的方式來理解並預測婚姻外遇行為。因此，本專案想問的是，

我們能否運用機器學習方法更有效地理解與預測外遇行為？

故本專案旨在運用機器學習（Machine Learning, ML）技術，和蒐集外遇相關行為特徵資料，用以預測受試者會不會發生婚外情的可能性。本專案目的在透過建立模型與特徵分析，我們希望能對婚姻中發生外遇行為背後的原因能有更深入的理解，並探索如何降低外遇行為的發生率。

### 🎯 專案目標

1. **建立預測模型：**  
   利用監督式機器學習方法預測個體會發生外遇行為的可能性。

2. **特徵重要性分析：**  
   找出最能影響外遇可能性的關鍵因素。

3. **提出預防建議：**  
   根據模型結果，提供改善婚姻關係與降低外遇風險的可能方向。

### 📊 資料集說明

本專案資料來自 **Ray Fair（1977）** 的經典研究，最初發表於 *Journal of Political Economy*。數據共包含 **6,366 筆觀察樣本**，涵蓋多項與婚姻和個人背景有關的變項。

- 主要變數：

| 變數名稱             | 說明                                                                  |
|----------------------|-------------------------------------------------------------------------|
| `affairs`            | 過去一年外遇次數（類別變項）                                            |
| `gender`             | 性別：0 = 女性，1 = 男性                                               |
| `age`                | 年齡                                                                |
| `yearsmarried`        | 結婚幾年                                                            |
| `children`           | 子女人數：0 = 無，1 = 1個以上                                          |
| `religious`          | 宗教信仰程度：1 = 反宗教，5 = 非常虔誠                                 |
| `education`               | 教育程度：9 = 小學，20 = 博士／醫學博士等高等學位                      |
| `occupation`              | 受訪者職業類別（依 Hollingshead 分類反向編碼）                         |
| `rating`             | 婚姻滿意度自評：1 = 非常不滿意，5 = 非常滿意                           |

### 🛠️ 使用技術

**(1) 建模與資料分析工具**
- Python 3.x
- Pandas / NumPy
- Scikit-learn
- Jupyter Notebook

**(2) 建模與分析流程**
1.使用 StandardScaler 進行**特徵**標準化
2.train_test_split 將資料分割為訓練集與測試集
3.訓練 Logistic Regression **統計模型**
4.透過 confusion_matrix、classification_report、roc_auc_score 評估**統計模型**表現

### 💍 分析與結論

| 分析項目 | 結論說明 |
|------|------|
| **外遇可能性** | 模型預測個案外遇機率約 **23% ~ 25%**，風險中等。 |
| **主要影響因素** | 1. 婚姻滿意度（越低風險越高）<br>2. 結婚年數（7 年以上較高）<br>3. 宗教信仰程度（越虔誠風險越低）<br>4. 年齡（30~40 歲偏高）<br>5. 是否有子女（有子女略低） |
| **預防建議** | - 提升婚姻滿意度與正向溝通<br>- 關注婚姻倦怠期（7~10 年）<br>- 強化價值觀與承諾<br>- 提供高風險族群心理與情感支持 |gi

### 📚 參考資料

Fair, Ray (1978). A Theory of Extramarital Affairs. Journal of Political Economy, 86(1), 45–61.

### 🚀 如何使用

```bash
git clone https://github.com/JackLaiplus/Project_SECOM_PatternMining.git
cd Project_SECOM_PatternMining
pip install -r requirements.txt
jupyter notebook Project_SECOM_PatternMining.ipynb
```



