# 融合搜索<a name="ZH-CN_TOPIC_0000001179782481"></a>

### 简介<a name="section104mcpsimp"></a>

融合搜索为开发者提供搜索引擎级的全文搜索能力，本示例为用户演示融合搜索的索引构造、索引数据插入、更新、删除和搜索等常用接口的使用。

### 使用说明<a name="section107mcpsimp"></a>

1.启动应用时连接融合搜索服务。

2.点击“构造定位索引”构造定位信息索引，返回成功后点击“读取索引”，返回构造的定位信息的索引，包括title，tag，bucket\_id，latitude，longitude，device\_id。

3.点击“插入定位数据”插入10条定位信息，返回成功。

4.点击“更新定位数据”来更新位置信息。

5.点击“获取查询索引条数”，假设用户输入是“定位”，要在"title", "tag"这两个域上发起搜索，搜索在bucket\_id和CommonItem.IDENTIFIER在0-5之间，在"tag"或者CommonItem.TITLE上命中"位置"，纬度必须在\[-80.0f, 80.0f\]，经度必须在\[-90.0, 90.0\]进行搜索，先在CommonItem.CATEGORY字段上升序排序，只有在CommonItem.CATEGORY上相同时，才会继续在"tag"上降序排序。此处返回满足查询条件的索引数据的条数。

6.点击“分组搜索”和“分页搜索”分别进行定位索引数据的查询，查询条件同上，这里返回查询到的数据。

7.操作完成可以点击“删除索引数据”或“通过查询语句删除索引数据”来完成删除索引数据。

### 约束与限制<a name="section110mcpsimp"></a>

1.本示例支持在大型设备上运行。

2.验证本示例的系统版本号：2.0.0.202110110309(DEVC00E1R53dexlog) GPU Turbo。

3.验证本示例的HarmonyOS版本：2.0.0 Devloper Beta3。

4.本示例需要使用 DevEco Studio 3.0 Beta3 (Build Version:3.0.0.533,built on September 26,2021) 才可编译。

