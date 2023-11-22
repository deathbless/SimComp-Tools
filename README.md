# Sim Companies Little Tools
 - 作者：道洛LTS_Kim
 - QQ交流群：926159075 
 - 插件显示的所有数据均为参考，请以实际为准。 如有巨大偏差，请联系开发者并尽可能详细描述
 - 插件主要适配：PC浏览器、油猴插件.（其他环境不代表不能用，但是不保证正常，偶尔做做适配）

# 使用方法 [选其一即可]
- https://greasyfork.org/zh-CN/scripts/475328
- 从代码构建 `yarn run build`

# 肚子饿饿
- https://afdian.net/a/SCT-Editor

# 功能如下
- `仓库单物总价`
  - 在仓库界面鼠标放在物品图标上可以看到成本*数量得到的物品总价值
- `交易所上架、合同交易利润显示`
  - 通过仓库进行交易所上架或者合同交易给其他公司的时候可以显示利润
  - 利润 = 售价x数量 - (成本x数量 + 运输数量x运输单价 + [税费])
- `单个大聊天窗口`
  - 只打开一个大聊天窗口
- `自动关闭弹窗`
  - 定时自动关闭所有弹窗
-  `输入框中英冒号切换`
  - 在聊天界面输入中文冒号后按下任意键（如空格键）、鼠标左键任意位置（非输入法）检测输入框内容
  - 检测后将所有中文冒号替换为英文冒号，直接舒服货物名称即可
- `聊天信息自动查价`
  - 检测聊天记录中游戏官方支持的物资图标的信息
  - 点击文字处会自动尝试获取交易所中相关品质的最低价
- `资料页头像放大`
  - 在公司资料页面，点击头像会放大到300x300 再次点击会恢复
- `零售显示总利润、时利润`
  - 在零售建筑中尝试上架零售物品的时候，会实时计算零售利润和每小时利润
  - 数据均来源于左侧显示数据，可能与实际数据有精度上的偏差
- `标签搜索仅显示在线公司`
  - 在标签搜索公司的界面上方增加一个按钮
  - 点击即可切换仅显示在线玩家
- `当地时间转换为24小时制`
  - 公司资料页面中的 当地时间 自动从12小时制转换为24小时制
- `主界面一键收取所有产出`
  - 在公司地图页面，右上角头像的右边有一个收取按钮，点击即可一键收取全部产出
- `总览与财报界面图表放大`
  - 在总览页面或者财报页面点一下空白处触发检测就会放大图表
  - 灵感来源：Sim Companies Visual Improvements
  - 链接：https://greasyfork.org/en/scripts/432355-sim-companies-visual-improvements
- `公司地图界面隐藏滚动条`
  - 在地图界面点一下空白处即可
- `在交易行使用限定金额进行采购`
  - 交易行多出一排信息，输入采购目标（最低品质要求，最高金额限制）
  - 点击按钮会提示计算结果，点击确定会尝试进行采购
  - 采购金额误差可能有±1%
- `交易行按钮旁高提醒`
  - 交易行旁按钮高提醒，提示当前是R1还是R2
- `自定义背景图片`
  - 在设置界面输入背景图片网址或者在代码中编辑 
  - 请自己注意图片的可访问性
- `建筑生产升级完工提示`
  - 建筑生产完成或者升级完成后会有消息提示，防止你泡在ChatRoom全给忘了。
- `交易行价格监控提示`
  - 交易行低价会有提示，不错过交易行的精彩价格。
- `自定义生产数量按钮`
  - 只想生产24小时？没有问题！只想生产12小时？也没问题！
  - 只要你想 都能自定义填入！
- `随手笔记`
  - 页面左下角增加文本编辑器入口，可以随意填写想要暂时记住的东西
- `接受合同界面自动询价`
  - 在接受合同的页面能自动查询该物品在交易所的价格，并标注mp-的量。
- `合同出售界面显示mp偏移`
  - 在合同出售的时候在价格下方会提示当前物品当前品质的mp-的实时价格。（刷新周期最少十秒钟
- `使用新建标签页打开公司页` [默认不打开]
  - 除了打开自己的公司页面,其他所有玩家的公司页面都会使用新标签页来打开
- `周期经济检测`
  - 每周五晚上十一点前十秒会请求两次旧数据,十一点后五秒会请求一次新数据
  - 通过比对 时产量 来得到新周期的变动
- `待处理信息显示` [默认不打开]
  - 左上角待处理消息强制显示
- `网页全局缩放` 
  - 在基础组件设置里面将网页整体缩放比例.

# 已知不适配 
- [2.0之前]安卓Via浏览器 存在未知问题导致不能正常启动插件，请自行手动修改部分代码。
- [`网页全局缩放`]火狐浏览器全系列不可用