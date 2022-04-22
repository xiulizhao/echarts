# echarts
echarts图表元素<br>
用于各种图表的绘制,如折线图,柱状图,饼图,散点图,地图,雷达图,热力图等等<br>
普通属性<br>
data-echartsid	设置元素使用唯一的id号	gg<br>
控制属性<br>
data--echartsoption	后端返回项目数据源:json数组	{"tooltip":{"formatter":"{a} <br></div>{b} : {c}%"},"series":[{"name":"业务指标","type":"gauge","endAngle":-45,"detail":{"formatter":"{value}%"},"data":[{"value":55,"name":"完成率"}],"axisLine":{"lineStyle":{"width":30,"color":[[0.3,"#f9402c"],[0.7,"#edae01"],[1,"#048807"]]}}}]}<br>
输出属性<br>
data-x-paramsname	点击获取当前数据名称<br>
data-x-paramsvalue	点击获取当前数据值<br>
data-x-paramspercent	点击获取当前数据百分比值<br>
