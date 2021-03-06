---
title: moment(Object)
version: 2.2.1
signature: |
  moment({unit: value, ...});
---


```javascript
moment({ hour:15, minute:10 });
moment({ y    :2010, M     :3, d   :5, h    :15, m      :10, s      :3, ms          :123});
moment({ year :2010, month :3, day :5, hour :15, minute :10, second :3, millisecond :123});
moment({ years:2010, months:3, days:5, hours:15, minutes:10, seconds:3, milliseconds:123});
moment({ years:2010, months:3, date:5, hours:15, minutes:10, seconds:3, milliseconds:123});
moment({ years:'2010', months:'3', date:'5', hours:'15', minutes:'10', seconds:'3', milliseconds:'123'});  // 从 2.11.0 开始。
```

可以通过指定对象中的某些单位来创建 moment。

省略的单位默认为 0 或当前的日期、月份和年份。

`day` 和 `date` 键均表示月份的某天。

`date` 新增于 **2.8.4**。

从 **2.11.0** 版本开始，支持字符串值（如最后一行示例所示）。

注意，像 `moment(Array)` 和 `new Date(year, month, date)` 一样，月份从 0 开始索引。

