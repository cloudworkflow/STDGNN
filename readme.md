# 👍特性👍
1. 用户友好的数据输入格式： 

   本项目中输入数据格式极其友好 ,图网络因为一些众所周知的原因，对数据格式要求十分严格 
   
   作者在图网络的入门期间，曾经因为数据格式的问题，浪费了大量的时间来统一各个模型（对照模型和baseline）的输入数据格式，所以在本项目中，作者尽可能的做到了数据格式的友好，以便于初学者能够更快的上手图网络

   具体而言有以下几点
   + 本项目需要的数据格式为二维（直接输入一个csv文件or xlsx文件）作为需要预测的时间序列数据，本项目中自带的工具会将其转换成三维的numpy压缩包，并且提供保存选项。保存的数据为经典的**PEMS**系列数据格式，你可以将其轻易的用在任何其他的图网络模型中
   + 内置多种数据清洗方法并提供选择，本项目内置了