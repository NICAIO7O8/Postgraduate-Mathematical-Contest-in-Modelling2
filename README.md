# 数学建模数据分析代码
本人将不定时分享华为杯数学建模相关算法

能力有限，只上传会的代码

# 目前更新代码
1 2018年C题第一问

      条件：numpy(1.20.1)、panadas(1.4.2)、scikit-learn(0.24.1)、factor_analyzer(2.1.0)和matplotlib(3.3.4)库；
      输入：附件1（无需操作）；
      功能：运用PCA降维和k-means聚类分析把事件分类等级并提取十大恐怖事件；
      输出：降维后各均值变量文件、k-means聚类结果图、案件等级编号文件及危害程度最高的十大恐怖事件。

2 2018年C题第二问

      条件：numpy(1.20.1)、panadas(1.4.2)、scikit-learn(0.24.1)、kmodes(0.12.10))和matplotlib(3.3.4)库；
      输入：附件2和3（无需操作）；
      功能：先用kmodes聚类后得到训练样本，再用该样本对支持向量机、随机森林、决策树训练模型，最后用准确度最高的模型给嫌疑人排序；
      输出：kmodes聚类个数变化图、预测准确度及未知案件嫌疑人排序表格。
      
3 2018年C题第三问

      条件：numpy(1.20.1)、panadas(1.4.2)、scikit-learn(0.24.1)、pmdarima(1.8.5和matplotlib(3.3.4)库；
      输入：问题二输出的文件（无需操作）；
      功能：用pm法预测2018年指标；
      输出：2018年结果图。
      
4 2019年D题第一问

      条件：numpy(1.20.1)、panadas(1.4.2)和scipy(1.6.2)库；
      输入：变量filenumber=1为输入文件1，文件2和3以此类推；
      功能：对时间序列、车速及怠速预处理；
      输出：result.xlsx文件。

5 2019年D题第二问

      条件：panadas(1.4.2)和matplotlib(3.3.4)库；
      输入：变量filenumber=1为输入文件1，文件2和3以此类推(该文件是第一问预处理完的)；
      功能：选取运动学片段；
      输出：运动学片段总数量、result.xlsx文件及某个片段图片。
      
6 2019年D题第三问

      条件：numpy(1.20.1)、panadas(1.4.2)、scikit-learn(0.24.1)和matplotlib(3.3.4)库；
      输入：变量filenumber=1为输入文件1，文件2和3以此类推(该文件是第二问所得运动学片段)；
      功能：运用k-means聚类分析把运动学片段分为三类并拼接成一条工矿曲线图；
      输出：运动学片段的9个指标文件、k-means聚类结果图、运动工矿曲线结果文件及图片和所得工矿曲线误差gap。

7 2020年B题第一问

      条件：numpy(1.20.1)和panadas(1.4.2)；
      输入：无需输入；
      功能：对样本285和313进行预处理；
      输出：285和313号样本预处理后的结果。

8 2020年B题第二问

      条件：numpy(1.24.3)、panadas(1.5.3)、matplotlib(3.7.1)和scikit-learn(0.24.1)；
      输入：无需输入；
      功能：利用主成分分析法降维；
      输出：贡献率图、20个主成分的前五个载荷系数最大的5个操作变量图和降维后的20个主要操作变量及其载荷系数文件。

9 2020年B题第三问

      条件：numpy(1.24.3)、panadas(1.5.3)和scikit-learn(0.24.1)；
      输入：处理后的325个样本文件及第二问降维后的操作变量；
      功能：利用线性回归、决策树、随机森林及SVR回归模型预测；
      输出：无文件，只有预测教好的模型结果。

10 2020年B题第四问

      条件：numpy(1.24.3)、panadas(1.5.3)、scikit-learn(0.24.1)和matplotlib(3.7.1)库；
      输入：已给出，无需操作；
      功能：利用预测模型和遗传算法求解降幅大于30%的操作变量；
      输出：优化后的操作变量.csv、遗传算法每一代的最佳适应度（在线图）、每一代迄今为止的最佳适应度（离线图）。
      
11 2021年B题第一问

      条件：numpy(1.20.1)和panadas(1.4.2)；
      输入：附件1；
      功能：根据题目给出的公式计算AQI；
      输出：8月25日-8月28日的AQI及首要污染物。
      
12 2021年B题第二问

      条件：numpy(1.20.1)、panadas(1.4.2)和scikit-learn(0.24.1)；
      输入：附件1；
      功能：用KNN做数据预处理、用pearson系数分析相关性和用K-means作聚类分析；
      输出：各变量的划分后的类别及其相关性（请自己根据结果分析每一类的特征）。

13 2021年B题第三问

      条件：numpy(1.20.1)、panadas(1.4.2)、scikit-learn(0.24.1)和matplotlib(3.3.4)库；
      输入：附件1和附近2；
      功能：用KNN做数据预处理和用随机森林进行预测；
      输出：预测图及A、B和C的13-15结果。
 
14 2021年B题第四问

      条件：numpy(1.20.1)、panadas(1.4.2)、scikit-learn(0.24.1)和math库；
      输入：附件1和附近3；
      功能：用KNN做数据预处理和用随机森林进行预测；
      输出：A、A1、A2和A3的结果。

15 2021年D题第一问

      条件：numpy(1.20.1)、panadas(1.4.2)、scikit-learn(0.24.1)和matplotlib(3.3.4)库；
      输入：ERα_activity和Molecular_Descriptor文件；
      功能：用3sigmal准则做数据预处理、用随机森林进行特征值分析并取前30个、用pearson计算相关性及剔除10个强相关性变量；
      输出：30个变量的特征图、相关性热力图和相关性文件及其最后的20个结果。
      
16 2021年D题第二问

      条件：numpy(1.20.1)、panadas(1.4.2)、scikit-learn(0.24.1)和matplotlib(3.3.4)库；
      输入：ERα_activity和Molecular_Descriptor文件；
      功能：用KNN插值做、用线性回归、神经网络、随机森林和决策树进行回归预测；
      输出：各个预测拟合图和活性结果。
      
17 2021年D题第三问

      条件：panadas(1.4.2)、scikit-learn(0.24.1)和matplotlib(3.3.4)库；
      输入：ERα_activity和ADMET文件；
      功能：用SVM、随机森林和决策树进行分类预测；
      输出：各个预测ROC图和分类结果文件。
 
18 2021年D题第四问

      条件：numpy(1.20.1)、panadas(1.4.2)和scikit-learn(0.24.1)；
      输入：Molecular_Descriptor、ERα_activity和ADMET文件；
      功能：用遗传算法和随机森林优化范围；
      输出：20个变量的范围及5个ADMET性质。

19 2022年E题第二问

      条件：numpy(1.20.1)、panadas(1.4.2)、keras(2.13.1)和scikit-learn(0.24.1)；
      输入：附近3、附近4和附近8；
      功能：使用LSTM、RNN、RF、ARIMA对时间序列进行预测；
      输出：真实值和预测值的结果对比图、水分和年份图、各土壤湿度表（问题二结果表）及各算法评价指标图。

20 2022年E题第三问

      条件：numpy(1.20.1)、panadas(1.4.2)、keras(2.13.1)、seaborn(0.12.2)、scipy(1.10.1)、matplotlib(3.7.1)和scikit-learn(0.24.1)；
      输入：附近14；
      功能：先进行方差相关性分析，再使用LSTM进行预测；
      输出：箱形图、真实值和预测值的结果对比图、第三问结果。

21 2022年E题第四问

      条件：numpy(1.20.1)、panadas(1.4.2)、seaborn(0.12.2)、matplotlib(3.7.1)和scikit-learn(0.24.1)；
      输入：附近4和附件8；
      功能：用主成分分析分析出主要的变量和权重（自己可根据变量和权重定义公式）
      输出：主成分分析结果表和图

22 2022年E题第五问

      条件：numpy(1.20.1)、panadas(1.4.2)和os库（版本号没搜到）；
      输入：文件夹里所有的附近；
      功能：把植物按功能群取均值后作差，找到年份对应的降水量，得出保留干重最大的放牧量；（不一定对，随便想的方法）
      输出：各年份最适合的放牧量（讲究着用吧）

23 2022年E题第六问

      条件：numpy(1.20.1)、panadas(1.4.2)、seaborn(0.12.2)、matplotlib(3.7.1)、keras(2.13.1)和scikit-learn(0.24.1)；
      输入：文件夹里所有的附近；
      功能：把所有的附近相关月份和相关变量提前用LSTM进行预测
      输出：2023年1-9月土壤性质预测图
      
24 2023年C题第一问


      条件：numpy(1.20.1)和panadas(1.4.2)；
      输入：无
      功能：用NSGA-II优化分配数量
      输出：‘results.xlsx’里面有三个(Sheet)指标：分配表、每个作品专家的评审人数、每个评审人数的作品量及Intersection Counts。

25 2023年C题第二问（未完，后续更新公式2）


      条件：numpy(1.20.1)、panadas(1.4.2)、matplotlib(3.7.1)、scipyscipy(1.10.1)、seaborn(0.12.2)及scikit-learn(0.24.1)；
      输入：数据1文件（无需操作）
      功能：运行main函数，计算了专家专业性指标、标准分及用主成分分析法测算了权重
      输出：打分分布图，偏差图、标准分公式1和指标及新标准分结果.xlsx文件
      
