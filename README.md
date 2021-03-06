zip文件内为外卖小程序源代码，分别为用户端、骑手端和商家端，以及三端合一的代码。

# 小程序简介

## 用户端

###基本功能：

1.首页：显示商家信息&快捷导航栏，支持 **数据库模糊查询** 商品&商家。

2.进入店铺：商家信息与商品详情显示、收藏店铺、自动计算商品数量与金额浮窗，选择地址、送达时间、优惠券、餐具等，生成订单。

3.百宝箱：发布快递代取、顺路捎东西、代买东西订单至骑手端，"我的筋斗云"显示已发布的跑腿订单详情。

4.订单：订单详情显示与管理（取消订单、退款、催单等）

5.我的个人中心：显示与修改用户个人信息、意见反馈信箱、公益记录、红包与收藏夹等

###额外功能：

1.首页：

轮播图广告位招租（各种培训机构或者店面宣传） 用于扩展额外收入

导航栏 **综合评分** 排序显示、 **公益商家** 公益金额排序显示。

**校园专属板块** 无课教室表格、浴池开放时间导入 用于增加小程序流量，提高用户粘性

2.进入店铺：

**预订单** 下单设置与专属板块显示，提早规划好一周菜谱。

3.百宝箱：

小猪下方“环保排行榜”：按照0餐具订单数量排序 用于志愿学时衡量发放

“个人公益捐助排行榜”：按照每月订单抽成入公益基金总金额排序 （用户可以通过 **多下单冲榜** &改昵称进行 **宣传互动** ，比如“祝xxx生日快乐”，“数学院数学嘉年华系列活动将在五四广场举办”）

“商家公益捐助排行榜”：按商家每月公益基金抽成总额排序，用于公益商家宣传



####优势：

专为校区无人驾驶项目定制，细节决定成败。

如：下单时选择收货地址，不是像普通的外卖平台一样用户端输入字符串地址详情（比如输入字符串可能是数学院、数院、数学与统计学院等），而是固定几个外卖柜存放地点让用户选择，从而避免小车定位时还要用NLP处理杂乱语句信息。

加入学生们关心的食堂食品卫生评分问题，共同监督食品安全，提升用户参与度。加入校园无课表等生活信息板块，提升定制化亲切感。

##商家端

### 基本功能：

店铺信息初始化，菜品信息上传，设置平台提成，订单显示与管理（接单、拒单、催单、退款等），个人中心，查看用户评分与评价详情，设置店铺营业/打烊状态，设置自动接单。

###额外功能：

财务管理（当日销售情况统计，经营数据可视化分析）

用户根据出餐速度、食品卫生、美味程度多角度评分参考

订单管理-->预订单专栏 便于提早准备

平台抽成公益基金设置  用于公益商家排行榜宣传店铺

接收广告位：助力经营相关课程推荐，门店推广等

## 骑手端

首页：显示快递代取、购物、捎带物品需求订单详情并接单

订单：订单详情显示与管理（加急订单、已完成订单上传图片证明）

我的：骑手收入统计图表分析（订单量分析、近期订单数据统计等）、评价情况、意见反馈、账号管理

