* 有$o,d,t$看可以根据时间划分为很多段，分段考虑
* 考虑car-sharing
    * 问题变为path cover问题
    * 不存在路径规划问题
    * 仙园的方法
* 考虑ride-sharing
    * 根据O,d分别选择，取交集
    * 将空间划分为网格，预先计算，减小实际运行时的计算量
    * 路径规划，若只考虑两个trip合乘，或者有固定上街的情况，可以暴力搜索
    * 旅行时间的计算很关键，很多地方要用，对精度可能有较大的影响
* 考虑二姐效应，热传导，逐渐扩散
* 不同车型，若考虑不同的容量大小，则可以合乘的数量就会增加，不同车型对尾气的排放的影响不同，
* 车与trip的稳定匹配？分别定义他们的preference?不知道是否可行？
