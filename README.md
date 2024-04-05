# level2
股票level2行情接口，实时数据接口，Lv2接口
购买咨询 1107673135
## 逐笔成交
| 字段      | 描述 | 说明     |
| :---:        |    :----:   |          :---: |
| stockCode      | 证券代码       |    |
| time   | 成交时间       | 格式 yyyy-MM-dd HH:mm:ss:SSS      |
| price   | 价格       | 单位：元     |
| volume   | 数量       | 单位：股     |
| channel   | 通道代码       |   |
| index   | 序号       |   |
| buyNo   | 买方序列号       |   |
| sellNo   | 卖方序列号   |   |
| BSFlag   | 委托方向       |  只有上海行情有效：B-外盘，主动买 S-内盘，主动卖 N-未知 |
| execType   | 成交类别       |  只有深圳行情有效：4 撤销 F 成交 |

## 逐笔委托
| 字段      | 描述 | 说明     |
| :---:        |    :----:   |          :---: |
| stockCode      | 证券代码       |    |
| time   | 成交时间       | 格式 yyyy-MM-dd HH:mm:ss:SSS      |
| price   | 价格       | 单位：元     |
| volume   | 数量       | 单位：股     |
| channel   | 通道代码       |   |
| index   | 序号       |   |
| orderDir   | 委托方向       | 1=买 2=卖 G=借入 F=出借  |
| orderNO   | 委托序号   |   |
| orderStatus   | 订单状态       |   |

## 十档
| 字段      | 描述 | 说明     |
| :---:        |    :----:   |          :---: |
| stockCode      | 证券代码       |    |
| time   | 成交时间       | 格式 yyyy-MM-dd HH:mm:ss:SSS      |
| preClosePrice   | 昨收       | 单位：元     |
| openPrice   | 开盘价       |      |
| highPrice   | 最高价       |   |
| lowPrice   | 最低价       |   |
| lastPrice   | 现价       |  |
| totalVolume   | 成交总量   |   |
| totalAmount   | 成交总金额       |   |
| bidPrice1   | 委买价格1       |   |
| bidVolume1   | 委买数量1       |   |
| askPrice1   | 委卖价格1       |   |
| askVolume1   | 委卖数量1       |   |
| bidPrice2   | 委买价格2       |   |
| bidVolume2   | 委买数量2       |   |
| askPrice2   | 委卖价格2       |   |
| askVolume2   | 委卖数量2       |   |
| ...   | ...       |   |
| bidPrice20   | 委买价格20       |   |
| bidVolume20   | 委买数量20       |   |
| askPrice20   | 委卖价格20       |   |
| askVolume20   | 委卖数量20       |   |

## 委托队列
| 字段      | 描述 | 说明     |
| :---:        |    :----:   |          :---: |
| stockCode      | 证券代码       |    |
| time   | 成交时间       | 格式 yyyy-MM-dd HH:mm:ss:SSS      |
| bidPrice1   | 委买价格1       |   |
| bidVolume1   | 委买数量1       |   |
| askPrice1   | 委卖价格1       |   |
| askVolume1   | 委卖数量1       |   |
| bid1Queue   | 买一队列       | 数组  |
| ask1Queue   | 买一队列       |  数组 |
