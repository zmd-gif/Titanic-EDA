# Titanic Exploratory Data Analysis (EDA)

## 项目目标
对泰坦尼克号乘客数据集进行探索性数据分析，挖掘影响乘客存活率的关键因素。

## 数据集
- 来源：Kaggle Titanic - Machine Learning from Disaster
- 训练集891条记录，包含12个原始特征

## 分析流程
1. 数据清洗：处理缺失值（Age/Embarked/Cabin）
2. 特征构造：提取头衔、家庭人数、独自出行标识、年龄分箱、票价分箱
3. 可视化分析：从性别、舱位、年龄、家庭等维度揭示生存规律

## 核心结论
- 性别是最重要的生存因素，女性存活率74% vs 男性19%
- 社会经济地位（舱位、票价）与存活率强相关
- 儿童有明显存活优势，独自出行者存活率最低

## 工具
Python (Pandas, NumPy, Matplotlib, Seaborn), Tableau
