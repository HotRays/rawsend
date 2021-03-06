## 核心需求与背景

+ 直接连接, 1km内全双工通话, 用户节点数>4
+ MESH组网, 拓展传输距离>8km
+ 蓝牙连接手机, 接听电话, 播放音乐

## 对标产品 Cardo, 维脉通

+ 方案: 蓝牙 + PA & LNA
+ 1km直连 + MESH 8节点组网拓展8-15km

## 预研
### 方案1: 蓝牙 + WiFi + PA & LNA
#### <b>优点:
- 带宽大(5-10Mbit/s), 后续能扩展新内容(视频/娱乐)
- 通用器件, 元器件容易购买, 性价比高
#### <b>缺点:
- 功耗大(>2w), 不适合电池供电, 而且难以做到类似蓝牙的节能特性
- 辐射大, 难以通过认证, 如此辐射功率植入头盔, 恐难以被用户认可

### 方案2: 蓝牙 + RF数字收发器(Sub-1G)
#### <b>优点: 
- 带宽中(1-2Mbit/s), 能同时传输<10路音频
- 适用当地ISM频段, 安全合规, 过认证, 销售无法律风险
- 无同类型竞品, 可保证知识产权
#### <b>缺点: 
- 组网协议不够完善, 软件开发工作量比较大
- 尚无同类型产品上市, 研发过程有一定风险

### 方案3: 蓝牙 + PA & LNA
#### <b>优点:
- 同行成熟方案, 研发风险小, 效果可预期
#### <b>缺点:
- 与同行成熟产品相比, 无明显特征