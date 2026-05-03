包括期末复习笔记（按复习课PPT顺序）和第二章模型总结

如果后面想要继续做通信，尤其是物理层，无线通信这门课非常重要，非常建议选
学过无线在面试中是一个加分项，因为很多学校都不学，很多同学都不选
相比于无线通信，无线通信（双语）这门课更侧重于概念理解，恰好面试只能问概念，非常有优势。而且期末考试也远比不双语的简单，主要考概念，给分高


问到的问题，个人想法，不一定对
1.解释一下多径
整个第三章都是讲的multipath，与path loss和shadowing不同，multipath是小尺度衰落，这意味着他在较小的d内快速变化。
第三章分窄带和宽带进行介绍的，窄带为nonresolvable，宽带resolvable。窄带主要讲了电平通过率（单位时间内信号包络向下穿过电平z的平均次数）和平均信号衰落时长（低于z的时间），信号传输时间约等于平均信号衰落时长 可能错移位，远小于 错多位， 远大于 不错。宽带主要讲了四个参数，power delay profile, coherence bandwidth, doppler power spectrum, channel coherence time，这四个参数可以辅助判断衰落类型（flat fading, frequency selective fading, fast fading, slow fading）
（也有专门问怎么判断窄带和宽带的 可以解释一下那个式子>>和<<的区别）

2.解释一下衰落
衰落指各径上相位的快速变化将造成剧烈的干涉现象，从而使接收信号强度发生快速的变化
四种衰落和判定
标准：中断率、平均错误概率、二者结合（适用条件）
FDMA就是利用的flat fading，所以没有ISI
（其实后面可以不说，但是时间一定，会的说的越多问到不会的题目的概率越小）
（也有问频率选择性衰落什么表现，怎么判定，有什么影响）

3.举一个生活中小尺度衰落的例子
不知道。。。把multipath讲了一遍，遂过

4.你知道哪些调制方法
模拟：调幅、调频、调相
数字：线性：PAM、PSK、QAM
 	   非线性：FSK

5.PAM、PSK、QAM是什么，星座图怎么画
PAM只有幅度携带信息，星座图在一条直线上
PSK只有相位携带信息，星座图在单位圆上，等间隔
QAM幅度和相位都携带信息，星座图意会一下。。

6.无线通信这门课你们讲了什么
第一章绪论，讲了无线与有线的优缺点、无线发展的历史，包括first wireless, first radio, first packet radio，还有常见的频段。第二章讲的大尺度衰落，包括path loss和shadowing, path loss讲了很多模型，包括LOS, two-ray model, ten-ray model, simplified path loss model 和一些经验模型等。第三章是小尺度衰落multipath，详见1。第四章modulation and performance，线性非线性，PAM、PSK、QAM、FSK，详见4、5。第五章讲的分集、交织等概念。第六章讲的duplex, multiple access等。

7.QPSK中Q是什么意思，与BPSK和8PSK相比有什么特征
Q是正交的意思，QPSK有四种相位，BPSK两种，8PSK有八种。QPSK比BPSK传输效率高，比8PSK误码率低。

8.怎么分析无线通信系统，与有线的分析上有什么区别
无线主要考虑path loss, shadowing, multipath，考虑fading，与有线不同