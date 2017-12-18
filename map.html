<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="viewport" content="initial-scale=1.0, user-scalable=no" />
<style type="text/css">
body, html,#allmap {width: 100%;height: 100%;overflow: hidden;margin:0;font-family:"微软雅黑";}
</style>
<script type="text/javascript" src="http://api.map.baidu.com/api?v=2.0&ak=OrcM5sfYrl7nBmlghNqz57tBcS5pslyH"></script>
<title>测距小工具：一键回家</title>
</head>
<body>
<div id="allmap"></div>
</body>
</html>
<script type="text/javascript">
    alert('请拖动红色标记，然后单击该红色标记以获取该地到家的路线。') // 百度地图API功能
    var map = new BMap.Map("allmap");
    var point = new BMap.Point(118.9621496201,36.9479883188);
    map.centerAndZoom(point, 15);
    map.enableScrollWheelZoom();    //启用滚轮放大缩小，默认禁用
    map.enableContinuousZoom(); //启用地图惯性拖拽，默认禁用
    var pointA = new BMap.Point(118.9621496201,36.9479883188);  // 创建点坐标A--家
    var marker = new BMap.Marker(point);  // 创建标注
    map.addOverlay(marker);              // 将标注添加到地图中
    marker.setAnimation(BMAP_ANIMATION_BOUNCE); 
    var marker2 = new BMap.Marker(point);  // 创建标注
    map.addOverlay(marker2);              // 将标注添加到地图中
    marker2.enableDragging();  
    marker2.addEventListener("click",getAttr);
    function getAttr(){
        var pointB = marker2.getPosition();       //获取marker的位置
        var output = "从该地到家驾车需要";
        var searchComplete = function (results){
            if (transit.getStatus() != BMAP_STATUS_SUCCESS){
            return ;
            }
            var plan = results.getPlan(0);
            output += plan.getDuration(true) + "\n";                //获取时间
            output += "总路程为：" ;
            output += plan.getDistance(true) + "\n";             //获取距离
            map.removeOverlay(marker);
            map.removeOverlay(marker2);
        }
        var transit = new BMap.DrivingRoute(map, {renderOptions: {map: map},
        onSearchComplete: searchComplete,
        onPolylinesSet: function(){        
            setTimeout(function(){alert(output)},"1000");
        }});
        transit.search(pointB, pointA);
	}
</script>
