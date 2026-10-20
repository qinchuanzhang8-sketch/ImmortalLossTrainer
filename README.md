================================================
 Immortal Loss · 内置修改器 (ImmortalLossTrainer) v1.2.0
 适配：Immortal Loss Beta 0.60.0（Unity 2022.3）
 基于 BepInEx 5.4.23.2
================================================

【这是什么】
一个解压即用的功能型修改器（BepInEx 插件），进游戏后按 F1 开关菜单。

一、锁血 / 状态
  1. 锁血（只锁血量）：血量持续保持满值、不会掉血；
     被击倒、被抓取等其它机制保持原版行为，只锁血量不动别的。
  2. 锁状态：兴奋、高潮等累积条持续清零，不会被催情或高潮失控
     （挤奶产出不受影响）。
  3. 防止怀孕：常驻避孕药效果，怪物也无法致孕。
  4. 快捷操作：清除负面累积 / 解除拘束起身 / 全恢复（灯点效果）。

二、刷物品
  · 全部 32 种物品，按游戏背包的三个分类（分类名跟随游戏语言）分组显示；
  · 每项支持【+1】【+10】【+99】【清0】，顶部一键全部 +99 / +999 / 全部清0；
  · 沙子（货币）一键 +5 万。

三、遗物（与物品分开，独立分类管理）
  · 全部遗物逐个解锁，或一键全解锁；
  · 乳头环饰物单独一节管理，同样支持逐个解锁；
  · 解锁后到游戏「遗物」菜单中装备生效。

四、功能
  · 攻击倍率 x1 / x5 / x20；
  · 一键全收集（物品/技能/遗物/图鉴/发现/沙子）；
  · 灯点全开、CG 全开。

【安装方法】
  1. 完全退出游戏。
  2. 把压缩包里的全部内容解压到游戏根目录（ImmortalLoss.exe 所在文件夹），
     提示覆盖时选择「全部覆盖」。
  3. 启动游戏 → 进游戏后按 F1 打开 / 关闭修改器菜单。
  （快捷键可在 BepInEx\config\immortalloss.trainer.cfg 修改；
    游戏启动后约 3~5 秒修改器才完全就绪，属正常现象）

【卸载方法】
  删除以下四项即完全还原：
    winhttp.dll、doorstop_config.ini、.doorstop_version、BepInEx 文件夹
  （只关闭修改器：删除 BepInEx\plugins\ImmortalLossTrainer 文件夹）

【注意事项】
  1. 使用前建议手动存档一次；出问题读档或关掉对应开关即恢复原版。
  2. 本修改器不修改游戏本体文件，完全可逆。
  3. 包含 BepInEx 5.4.23.2（LGPL-2.1 许可，见压缩包内 LICENSE-BepInEx.txt）。
  4. 日志：BepInEx\LogOutput.log 与 BepInEx\plugins\ImmortalLossTrainer\diag.log。
  5. 如杀毒软件误报 winhttp.dll，请加白名单（BepInEx 启动组件，必需）。

【下载】
  本仓库内的最新版压缩包（点进去后点 Download 按钮）：
  https://github.com/qinchuanzhang8-sketch/ImmortalLossTrainer/blob/main/ImmortalLossTrainer_v1.2.0.zip

  直链（复制到浏览器地址栏回车即可直接下载）：
  https://raw.githubusercontent.com/qinchuanzhang8-sketch/ImmortalLossTrainer/main/ImmortalLossTrainer_v1.2.0.zip

【作者的其他作品】
· 疯狂岛 Mad Island 模组 MadIslandFreedom —— 物品/刷怪/角色状态/互动解锁：
  https://github.com/qinchuanzhang8-sketch/MadIslandFreedom
· HumanitZ（僵尸生存）内置修改器 HTZ Trainer —— 736种物品/车辆/状态锁定：
  https://github.com/qinchuanzhang8-sketch/HTZTrainer
· 本修改器主页（更新都会在这里发布）：
  https://github.com/qinchuanzhang8-sketch/ImmortalLossTrainer

【支持作者】
如果这个修改器帮到了你，包里有张诚意满满的图——
「支持一下吧，拜托拜托Thanks♪(･ω･)ﾉ」，
微信 / 支付宝扫码请作者喝杯奶茶，感谢支持！

【版本】
v1.2.0（首个公开版）
================================================
