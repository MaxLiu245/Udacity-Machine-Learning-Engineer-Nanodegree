# README

This is a supplementary material for Machine Learning Engineer Nanodegree Capstone.

## 开发环境

该项目在Win10家庭中文版（64位）系统的基础上，用Anaconda3（64位）完成。

具体使用的Python为版本2.7，为此创建了环境py2。具体使用的编程库包括`Numpy` ，`Scipy`，`Matplotlib`，`seaborn` ,`Scikit-learn`，`pandas`。代码的呈现使用了`Jupyter Notebook`。

> 注意：在Notebook中的可视化部分，PDF格式图片可能无法预览，只需在新标签页打开链接即可。

## 辅助材料

一个名为`visuals.py`的文件，该文件来源于机器学习项目2——Finding Donors，我对其中的函数做了小小的修改。

## 文件说明

`report.pdf` 最终的报告文件；

`Machine Learning Engineer Nanodegree Capstone.ipynb` 全部Python代码；

`Machine Learning Engineer Nanodegree Capstone.html` 方便Python代码查看，但是未显示PDF图片；

`visuals.py` 提供了部分可视化函数；

`voice.py` Kaggle上下载的数据集；

`README.md` 报告的说明文件；



## 模型训练时间说明

|     Models     | Time cost(Primary Training/ Grid Searching)(s) |
| :------------: | :--------------------------------------: |
| Baseline Model |               None / None                |
|       LR       |          0.0280001163483 / None          |
|      SGD       |         0.00200009346008 / None          |
|      KNC       |         0.00300002098083 / None          |
|      SVC       |      0.197999954224 / 242.392999887      |
|      CART      |     0.0250000953674 / 1.04200005531      |
| Random Forest  |     0.0450000762939 / 47.8340001106      |
| Neural Network |      0.87299990654 / 1114.97600007       |
|    XGBoost     |      0.275000095367 / 181.176000118      |

