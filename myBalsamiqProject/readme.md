# 森林病虫害防治系统规范

---
# 命名规范

## 网页命名
1. 登录界面 login.html
2. 主页面 index.html
3. 资料管理
    - 虫害一览  wormPanel.html
        - 添加新害虫 wormAdd.html
        - 查看详细信息 wormInfo.html
    - 病害一览 diseasePanel.html
	    - 添加新病害 diseaseAdd.html
	    - 查看详细信息 diseaseInfo.html
    - 鼠害一览 mousePanel.html
	    - 添加新鼠害 mouseAdd.html
	    - 查看详细信息 mouseInfo.html
4. 灾情防治
    - 区域一览 areaPanel.html
        - 添加区域 areaAdd.html
    - 小班管理 classPanel.html
        - 添加小班 classAdd.html
        - 查看小班信息 classShow.html
        - 修改小班信息 classUpdate.html
    - 事件记录 thingPanel.html
	    - 添加事件 thingAdd.html
	    - 查看事件信息 thingInfo.html
	    - 申请专家会审 
	    - 修改事件信息 thingUpdate.html
5. 专家会商 
	- 专家一览 proficientPanel.html
		- 添加专家 proficientAdd.html
		- 查看专家信息 proficientShow.html
		- 修改专家信息 proficientUpdate.html
		- 删除灾情  
	- 会商灾情 conferPanel.html
		- 专家会商 conferAdd.html
6. 药剂器械出库管理
	- 药剂管理 drugPanel.html
		- 添加药剂 drugAdd.html
    - 器械管理 apparatusPanel.html
        - 添加器械 apparatusAdd.html
    - 出库管理 outwarehousePanel.html
	    - 添加出库信息 outwarehouseAdd.html
7. 系统信息
	- 用户管理 userPanel.html
		- 添加用户 userAdd.html
		- 删除用户 
		- 修改用户信息 userUpdate.html
	- 日志一览 logs.html
    
## 界面命名 
全部照着pdf上的来

# 其他要求

## html
1. 页面大小
    1. index.html
    2. login.html
    3. 其他网页:
2. 层次结构清楚 关键代码写注释
## 样式 
1. 所有控件不加颜色(白色就可以了) 我们选用最基本的颜色 (低调)
2. 不加背景图片

## 编码
所有文件一律使用 UTF-8 编码
具体设置:

![enter image description here](http://i1167.photobucket.com/albums/q637/CodeAi/2015-09-17_20-34-18_zpstgl16wmd.png)


# 项目结构
![enter image description here](http://i1167.photobucket.com/albums/q637/CodeAi/2015-09-17_20-37-41_zpscwjouog0.png)