# 50ETF期权隐含波动率计算以及曲面构建

数据集：2015-2018年50ETF期权日行情

## 说明

数据位于ETF_data

代码位于code，其中

iv_calculate.ipynb 实现隐含波动率率计算

iv_surface.ipynb 实现三维绘图

## 功能

数据预处理：筛除数据缺失或者异常的条数

隐含波动率计算：通过B-S model计算期权隐含波动率

统计描述：通过在值情况研究50ETF的隐含波动率分布情况

波动率曲面：构建执行价格、隐含波动率、到期日的3维图形

## 参考

数据来源：https://github.com/Jensenberg/volatility-and-option/tree/master/data

隐含波动率计算与画图：https://github.com/caly5144/shu-s-project/tree/master/options