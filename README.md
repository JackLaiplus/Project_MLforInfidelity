# Project_MLforInfidelity

本專案運用機器學習（Machine Learning, ML）技術，蒐集個人背景、婚姻與社會等特徵資料，預測受試者會不會發生婚外情的可能性。本專案目的透過建立模型與特徵分析，我們希望對婚姻中發生外遇行為背後的原因能有更深入的理解，並探索如何降低其發生率。

### 🎯 專案目標

1. **建立預測模型：**  
   利用監督式機器學習方法預測個體是否有外遇行為。

2. **特徵重要性分析：**  
   找出最能影響外遇可能性的關鍵因素。

3. **提出預防建議：**  
   根據模型結果，提供改善婚姻關係與降低外遇風險的可能方向。

### 📊 資料集說明

本專案資料來自 **Ray Fair（1977）** 的經典研究，最初發表於 *Journal of Political Economy*。數據共包含 **6,366 筆觀察樣本**，涵蓋多項與婚姻和個人背景有關的變項。

### 📊 主要變數：

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

- Python 3.x
- Pandas / NumPy
- Scikit-learn
- Jupyter Notebook

### 🚀 如何使用

```bash
git clone https://github.com/JackLaiplus/Project_SECOM_PatternMining.git
cd Project_SECOM_PatternMining
pip install -r requirements.txt
jupyter notebook Project_SECOM_PatternMining.ipynb
```
### 📚 參考資料

Fair, Ray (1978). A Theory of Extramarital Affairs. Journal of Political Economy, 86(1), 45–61.



