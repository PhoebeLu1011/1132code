# 1132程式語言
## 作業
HW1程式碼:[HW1](https://github.com/PhoebeLu1011/1132code/blob/main/1132code_hw1.ipynb)
## HW2-病患資料視覺化
此作業視覺化了包含 150 筆病患紀錄的資料集。專案目標是探索各種健康因素（例如年齡、BMI、疾病、用藥與追蹤等）之間的關聯。
### 程式碼
[程式碼](https://github.com/PhoebeLu1011/1132code/blob/main/HW2.ipynb)
### 數據
[導入的數據](https://github.com/PhoebeLu1011/1132code/blob/main/%E4%BD%9C%E6%A5%AD%E4%BA%8C%20-%20%E5%B7%A5%E4%BD%9C%E8%A1%A81.csv)\
數據包含以下欄位：
- **PatientID**：病患的代碼。
- **Age**：病患的年齡。
- **BMI**：病患的身體質量指數。
- **Disease**：病患的健康狀況（例如糖尿病、高血壓、關節炎等）。
- **Medication**：病患是否在服用藥物（0 代表沒有，1 代表有）。
- **Rehabilitation**：病患是否進行復健治療（0 代表沒有，1 代表有）。
- **FollowUp**：病患是否有追蹤門診（0 代表沒有，1 代表有）
#### 圖表與說明
1. 疾病分布（Bar Chart）
此長條圖顯示了各種疾病在所有病患中的分布情況。
![圖片描述](HW2IMAGE/01.png)
此圖表顯示各疾病類型出現的頻率。可以看出某些疾病如 Diabetes 比較常見 ，顯示在此資料中，患有 Diabetes的人比例較高
3. BMI 與年齡散佈圖
此圖顯示了 **年齡** 與 **BMI** 之間的關係，並且使用顏色區分不同疾病類型。
![圖片描述](HW2IMAGE/02.png)
此圖顯示病患 BMI 分布較分散，並無明顯線性趨勢，但部分慢性病患者的 BMI 明顯偏高，可能與生活型態或年齡相關。
4. 各疾病的用藥與追蹤情況（堆疊長條圖）
此堆疊長條圖顯示了不同疾病病患的 **用藥** 和 **追蹤治療** 情況。
![圖片描述](HW2IMAGE/03.png)
此圖表示不同疾病的用藥與追蹤治療情況。可以看出例如 Arthritis 與 Diabetes 有較高的用藥與追蹤比例，顯示這些病症可能需要長期控制與治療。
5. 不同疾病類型與BMI的箱型圖
此箱型圖展示了 **不同疾病類型（Disease）** 下的 **BMI** 分布情況。
![圖片描述](HW2IMAGE/04.png)
由圖可以看出，高 BMI 與多種慢性疾病（如糖尿病和高血壓）之間有一定的關聯。


## HW3-學生生活習慣與成績分群分析
本作業使用 Python 分析學生的生活習慣，包括睡眠、社群媒體使用、運動頻率、讀書時數與成績等統計指標，利用 KMeans 聚類與 PCA 降維分析分群成三種類型的學生，並使用視覺化工具展示結果。
### 程式碼

