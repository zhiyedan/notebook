# Jupyter 使用
## 类型
- df['time'] = df.time.astype('int')
- 
## 作图
- 概率图
```
iris.ix[:,:-1].hist()
iris.plot(kind='kde')

from pandas.tools.plotting import radviz
radviz(df, 'col_name')

```
- `plt.legend(loc='best')`用来显示col name 图例；刻印文字
- 

## 行列选择
- df.loc(df['ap_mac'] in ['mac1','mac2']) 出现问题？？？？？？？？？？？？？？？？？？
- df.query()操作很暴力

```
a = "ap_mac in ("+",".join(["'"+x+"'" for x in list1])+")"
filted_df = df.query(a)
```

# 每周工作进展

# 比赛

