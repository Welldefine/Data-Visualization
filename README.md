# Data-Visualization

中国人民大学数据可视化课程的期中大作业，由小组四人共同完成。

* Data Set收录了所需要的数据集及其来源;
* Code中收录了数据清洗以及可视化绘图的代码(R语言);
* output_data内为清洗后的数据;
* Final Report中为最终的报告以及PPT.

## Work List

### Topic

北京市空气质量数据可视化

### Data Source - Principal: Tian R.Z

* **Source**:  [北京市环境保护检测中心](http://www.bjmemc.com.cn/) （2013.12.06-2024.11.16）- [王晓磊](https://quotsoft.net/air/)
* **Descripation:**

  > Data Set/北京空气质量中共有11个文件夹，分别为2014年-2024年的北京市空气质量数据。其中每个文件夹里是01月01日-12月31日的全年逐日空气质量数据。由于检测设备的不同，PM2.5、PM10、AQI这三个类空气质量指标保存在“beijing_all_20xxxxxx.csv”中，SO2、NO2、CO、O这四类空气质量指标保存在“beijing_extra_20xxxxxx.csv”中。
  >

  **Data Format**：

  > 北京市数据（CSV格式）
  >
  > 第一行为列名，分别是日期、小时、数据类型、各个监测点名（或城市名、监测点代码）；以下每行为某时刻一种类型的数据。
  >

  ```
  date,     hour, type,      东四, 天坛, 官园, 万寿西宫,...
  20131205, 1,    PM2.5,     93,  93,   63,  79,...
  20131205, 1,    PM2.5_24h, 93,  108,  99,  123,...
  20131205, 1,    PM10,      103, 124,  81,  107,...
  20131205, 1,    PM10_24h,  97,  130,  122, 141,...
  20131205, 1,    AQI,       123, 141,  130, 161,...
  ```

### Data Cleaning - Principal: Tian R.Z.


### Visualization - Principal: Duan S.J. & Kuang Y.Q.

### Report and Document - Principal: Xu B.W.
