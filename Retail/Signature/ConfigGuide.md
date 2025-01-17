---
type: ConfigGuide
project: "签名墙"
title: "配置文档"
---

# 目录
- [1.新增广告](#1%E6%96%B0%E5%A2%9E%E5%B9%BF%E5%91%8A)
  * [1.1新增广告：添加广告资源](#11%E6%96%B0%E5%A2%9E%E5%B9%BF%E5%91%8A%E6%B7%BB%E5%8A%A0%E5%B9%BF%E5%91%8A%E8%B5%84%E6%BA%90)
  * [1.2.新增自定义广告](#12%E6%96%B0%E5%A2%9E%E8%87%AA%E5%AE%9A%E4%B9%89%E5%B9%BF%E5%91%8A)
- [2.上线广告](#2%E4%B8%8A%E7%BA%BF%E5%B9%BF%E5%91%8A)
- [3.创建广告分组](#3%E5%88%9B%E5%BB%BA%E5%B9%BF%E5%91%8A%E5%88%86%E7%BB%84)
  * [3.1创建普通分组](#31%E5%88%9B%E5%BB%BA%E6%99%AE%E9%80%9A%E5%88%86%E7%BB%84)
  * [3.2创建点位广告分组](#32%E5%88%9B%E5%BB%BA%E7%82%B9%E4%BD%8D%E5%B9%BF%E5%91%8A%E5%88%86%E7%BB%84)
- [4.创建节目单](#4%E5%88%9B%E5%BB%BA%E8%8A%82%E7%9B%AE%E5%8D%95)
  * [4.1新建普通节目单](#41%E6%96%B0%E5%BB%BA%E6%99%AE%E9%80%9A%E8%8A%82%E7%9B%AE%E5%8D%95)
  * [4.2新增空闲广告和巡游广告的节目单](#42%E6%96%B0%E5%A2%9E%E7%A9%BA%E9%97%B2%E5%B9%BF%E5%91%8A%E5%92%8C%E5%B7%A1%E6%B8%B8%E5%B9%BF%E5%91%8A%E7%9A%84%E8%8A%82%E7%9B%AE%E5%8D%95)
- [5.新建排程](#5%E6%96%B0%E5%BB%BA%E6%8E%92%E7%A8%8B)
- [6.新建设备](#6%E6%96%B0%E5%BB%BA%E8%AE%BE%E5%A4%87)
- [7.发布排程](#7%E5%8F%91%E5%B8%83%E6%8E%92%E7%A8%8B)
- [8.修改查看排程周期内的播放内容](#8%E4%BF%AE%E6%94%B9%E6%9F%A5%E7%9C%8B%E6%8E%92%E7%A8%8B%E5%91%A8%E6%9C%9F%E5%86%85%E7%9A%84%E6%92%AD%E6%94%BE%E5%86%85%E5%AE%B9) 
- [9.更新apppod资源信息](#9%E6%9B%B4%E6%96%B0apppod%E8%B5%84%E6%BA%90%E4%BF%A1%E6%81%AF)
- [10.设备下有多个排程](#10%E8%AE%BE%E5%A4%87%E4%B8%8B%E6%9C%89%E5%A4%9A%E4%B8%AA%E6%8E%92%E7%A8%8B)
## 1.新增广告
### 1.1新增广告：添加广告资源
字段解析：
| 字段 | 描述                                                                          |
| ---- | ----------------------------------------------------------------------------- |
| 名称 | 广告名称，必填                                                                |
| 标签 | 该条广告的标签,非必填项。例如：夏季新品营销。（具体标签的配置可参考标签管理） |
| 资源 | 广告的资源，可以为图片或者视频等，必填                                        |

注意：图片的分辨率大小建议和显示设备一样大

操作步骤：
选择广告列表→点击新增广告→编辑广告信息（名称、资源等）→点击保存

操作步骤图示：

![输入图片说明](https://images.gitee.com/uploads/images/2021/0423/173153_4efea7a6_8867015.png "屏幕截图.png")


![输入图片说明](https://images.gitee.com/uploads/images/2021/0423/175645_f14d45ab_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/140043_e380b1f8_8867015.png "屏幕截图.png")

广告列表显示：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/140417_a584f08b_8867015.png "屏幕截图.png")

### 1.2.新增自定义广告

<font color="red">warning:当添加了自定义广告，不会播放新增广告时添加的资源，只会播放自定义里的广告</font>

操作步骤：
选择广告列表→点击新增广告/编辑广告信息→勾选自定义内容→点击自定义内容tab→进入画布界面→添加内容→点击保存

操作步骤图示：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0521/110540_556f2a1f_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0521/110745_06a2f2b3_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0521/110813_1803a72b_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0521/111115_63f2d3ca_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0521/111411_c9b5f343_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0521/111538_f227f28e_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0521/111803_f03ced67_8867015.png "屏幕截图.png")

## 2.上线广告
<font color="red">warning：需要使用的广告必须是上线状态</font>

操作步骤：
上线选中：勾选要上线的广告（广告状态是下线）→点击批量操作→选择上线选中→弹出审核发送框→点击发送 
操作步骤图示：                       

1.申请上线
![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/144841_8b944cdf_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/145312_7f86ce40_8867015.png "屏幕截图.png")

## 3.创建广告分组
### 3.1创建普通分组
前提：已经创建广告并显示上线
广告分组:将多个广告存放在一个分组里

操作步骤：
选择广告分组→单击新建分组→输入分组名称、添加广告→点击保存

操作步骤图示：

![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/162141_6797f966_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/165357_c4d44c21_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/165620_7b0824f4_8867015.png "屏幕截图.png")
排序：广告播放顺序

持续时间：广告播放时间

切换动画：切换广告的方式
![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/170154_2d6d2e10_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0425/170239_c2cac9e9_8867015.png "屏幕截图.png")

### 3.2创建点位广告分组
前提：已添加设备路线。一般用于机器人，到达指定地点后播放指定内容。
![输入图片说明](https://images.gitee.com/uploads/images/2021/0719/150225_3108e76f_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0719/150529_ea740652_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0719/150721_198ab19c_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0719/150840_e6295fd9_8867015.png "屏幕截图.png")

## 4.创建节目单
### 4.1新建普通节目单
warning:一个节目单里可以添加多个分组

操作步骤：单击24H节目单→单击新建节目单→编辑完信息后→单击保存


操作步骤图示：
新建节目单
![输入图片说明](https://images.gitee.com/uploads/images/2021/0518/160516_4b2924c4_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0531/104740_b8f1e168_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0518/161947_1e32e2cd_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0531/105102_e110b54a_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0518/163528_90b5ad94_8867015.png "屏幕截图.png")

### 4.2新增空闲广告和巡游广告的节目单
warning:目前用于机器人
![输入图片说明](https://images.gitee.com/uploads/images/2021/0720/100419_6c464ab3_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0720/101023_21a55a6c_8867015.png "屏幕截图.png")

## 5.新建排程
warning：第一次创建排程的时候可以添加节目单，后面若需要修改排程里的节目单，需要将节目单发布到排程
1.有排程，但在当前时间内未设置广告资源，apppod显示“空闲”

2.无可用排程或排程过期，apppod显示“无可用排程”


操作步骤：点击排程下的节目排程→点击创建排程→编辑信息后→点击保存
操作步骤图示：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/141052_6ba73a0c_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/141230_84fae959_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/141308_f2a53edf_8867015.png "屏幕截图.png")
 ## 6.新建设备
 Warning:

1. 设备新增后为下线状态

2. 如需要使用设备，请先上线设备（具体参考设备上线）

3.apppod注册设备密钥，设备运行状态会显示在线

| 参数     | 描述                                       |
| -------- | ------------------------------------------ |
| 名称     | 设备名称，必填                             |
| 设备类型 | 设备类型，必填，信息发布选择触控落地一体机 |
| 系统类型 | 选择windows系统和Android系统，必填         |

操作步骤：单击设备列表→点击新增设备→输入设备信息→点击保存

操作步骤图示：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0512/154509_2a12a351_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0512/154654_1f8e0f53_8867015.png "屏幕截图.png")

## 7.发布排程
前提条件：已创建过设备,排程只能发布到设备

发布类型 描述
追加： 将选择的排程追加到发布对象中，若之前存在，则为更新
更新： 仅发布当前选中的排程，之前发布对象中的排程将被覆盖，只显示当前发布的排程
撤回： 撤回发布对象中的所选的排程，撤回后，发布对象中将无选中的排程
操作步骤：
操作步骤图示
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/155425_065c3821_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/155536_77979bd8_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/155718_05284335_8867015.png "屏幕截图.png")

## 8.修改查看排程周期内的播放内容
排程详情：默认查看近8天的节目单，可以搜索排程范围内的所有节目单，可以对某一天的节目单进行修改
详情
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/141920_f3e7b9f7_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0713/173855_0009803d_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/154159_824afe29_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/155016_3cb01c60_8867015.png "屏幕截图.png")

## 9.更新apppod资源信息
前提：已创建过排程，并将排程发布给设备
warning:若要修改设备下的广告信息，在广告列表修改后，设备里的广告会同步修改，若要修改设备下排程里的广告分组或节目单（需要重新走下流程）

       一：重新添加、删除或修改分组里的广告
       二：在节目单重新添加修改的分组
       三：将修改后的节目单发布到排程，再将排程发布到设备
       四：最后点击设备下的更新资源

warning:将排程发布到设备后我们需要去对应设备下的控制里，点更新资源，apppod会更新数据 
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/172530_7313a308_8867015.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0707/113417_849efb02_8867015.png "屏幕截图.png")

## 10.设备下有多个排程

设备下有多个排程，可以启用或禁用排程
![输入图片说明](https://images.gitee.com/uploads/images/2021/0519/172530_7313a308_8867015.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0909/164833_1cd4b6f7_8867015.png "屏幕截图.png")