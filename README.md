# 智能航空预报系统 (SmartAviationForecast)

第六届"中国软件杯"大学生软件设计大赛赛题-B1-基于互联网大数据的事件智能抓取和画像

## 赛题内容

赛题     | 基于互联网大数据的事件智能抓取和画像
------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
赛题介绍   | 随着互联网大数据的发展，各种大数据的分析对各行业都产生了不同程度的影响。网站数据、社交媒体数据等是互联网大数据的重要组成部分。对于民航业领域，社会 事件的发生，会很大程度影响旅客的出行需求变化，从而影响航空公司飞机运力投放、航班编排、票价策略调整等，对互联网事件的准确抓取和分析能够帮助航空公 司更好的服务市场、服务旅客、提升收益。
业务场景   | 对 于航空公司来说，能否预先判断旅客的出行需求，可用于航空公司及行业管理部门决定行业运力投放的合理性，从而提高旅客服务水平、提高航空公司航班收益水 平。目前，仅靠航空公司拥有的数据是远远不够的，从互联网中获取大量的影响民航领域的信息能够帮助航空公司制定销售策略。而互联网事件数据，是其中非常重 要的一种数据来源。通过初步分析，对民航业可能有影响的事件主要可分为如下几类：政治会议（例G20）、展会、体育赛事、演唱会、突发异常天气等。对不同类型的事件分别分析，并建立一个相对统一的模型描述事件，用来分析其对旅客出行的影响。但是互联网上的数据复杂性非常高，一是事件数据来源多；二是各数据源对事件的描述非常复杂，来自不同数据源的同一事件，可能差别较大；三是事件数据一般为非结构化数据，其处理和分析有一定的难度。传统做法需要投入大量人工进行标注。因此要求参赛者具有抓取数据的技术和一定的自然语言处理能力，实现自动化。
功能性需求  | 实现互联网事件天级或更高频次抓取，能够采集政治会议、展会、体育赛事、演唱会、突发异常天气等各类中比较主要的事件，每个类型的事件数据至少来自2个数据源（网站）。 实现事件的去重功能，主要有两个方面，一是不同数据源（网站）的事件去重，二是不同天抓取的事件去重。 事件画像建模，即事件属性自动化提取。属性需包括主办方级别、影响区域范围、影响力度、影响人群等。4.可视化展现，可视化展示事件的影响情况，形式不限。5.加分项：参赛选手可从互联网上自行抓取民航有关的数据，并分析事件对民航相关数据的影响。注：本题"事件"可主要考虑国内事件。
非功能性需求 | 1.事件抓取频率：每天至少一次。2.事件应包括主要的影响力较大的事件，能涵盖指定时间段内主办方选取的事件为优。3.属性提取准确性高为优。4.可视化展现效果好者为优，形式不限。

## 可视化模块说明

此模块搭建了一个网站，采用SpringBoot、MyBatis框架开发。

可视化使用百度的Echarts绘图，主要提供了大屏展示功能，适用实时动态展示，监控状态，整个互联网的事件分布情况表现出来。

## 效果图

![效果图](https://github.com/CHN-Jaylin/SmartAviationForecast/blob/master/img/saf-ui.gif)
