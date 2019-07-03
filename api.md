# 黑白灰控制台API地址

*所有接口都需要带上登录后的cookie值*


## 启用寻路服务器

METHOD:POST

URL：https://d.agrael.cn:8899/console/changeExploreAlgorithmValueEnabled
参数：


  key  | 说明
 ---- | ----- 
 tag  | 战网号，例如：测试战网#1234
 exploreAlgorithmValueEnabled  | 是否开启， 开启true,关闭false
 
 
 ## 私人掉落
 
 METHOD:GET
 
 URL：https://d.agrael.cn:8899/console/getPrivateDropInfo
 
 key  | 说明
 ---- | ----- 
 tag  | 战网号，例如：测试战网#1234
 page  | 页数
 
 
 返回值
 
 ```json
 {
	"updateTime": 1562126237839,
	"items": [{
		"itemBaseType": "0",
		"quality": "9",
		"legendaryQuality": "1",
		"details": {
			"IconUrl": "http://media.blizzard.com/d3/icons/items/large/unique_gem_012_x1_demonhunter_male.png",
			"InternalName": "-243466136",
			"RealName": "贼神的复仇之石",
			"Quality": "9",
			"LegendaryQuality": "1",
			"ActorSnoId": "405801",
			"BaseType": "4",
			"IsAncient": "false",
			"IsPrimalAncient": "false"
		},
		"storedTime": 1562079562000,
		"ancient": false,
		"primalAncient": false
	}],
	"totalPages": 103,
	"totalElements": 2059
}
 ```
 
 
 
