# rexxar
小说抓取和阅读程序，仅供私人技术研究，小说存在版权问题请勿用于商业


核心两个模块：

1、rexxar-crawler: 小说爬取和存储模块，核心思想在于无状态设计，能完美多模块分布式部署抓取和处理抓取失败容错，在学习中抓取小说5000+，存储容量50G左右（备注：版权问题，最后全部都删除）


2、reader-web：  小说管理和读取api接口，供app调用
