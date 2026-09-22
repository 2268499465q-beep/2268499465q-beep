# 蒋明亮｜汽车电子测试与标定

车辆工程本科生（2027 届），面向汽车电子控制器测试、系统测试、台架测试与标定验证岗位。

我在车身舒适域标定项目中独立承担现场执行：基于 INCA + ES582 搭建 XCP 标定链路，完成电动车窗换区自学习、防夹力与电机电流、堵转电流纹波采集、控制器刷写与刷后双版本号校验；独立搭建 9V / 12V / 14V / 16V 多电压工况及常温、高温、低温环境条件，执行防夹功能边界测试；并使用 MDA 与 Excel 整理数据、输出测试报告。目前正在推进车窗升降异常故障链的排查与闭环。

可接受长期驻场、装车测试与冬夏标。

## 作品集

[蒋明亮的汽车电子测试与标定作品集](https://ea6e8con64.feishu.cn/wiki/UrbzwYdsbi2UYGkBkcEczsYcn1d)

| 页面 | 内容 |
| - | - |
| [01｜车窗与座椅标定实习](https://ea6e8con64.feishu.cn/wiki/IbI6wjkqvi2de1kjKoXcBIqvnHe) | 标定链路搭建、多工况执行、防夹边界测试、失效分析与故障链案例复盘 |
| [02｜MiniVCU 扭矩限扭模型](https://ea6e8con64.feishu.cn/wiki/HXntwkbkliT2BBkjHHAcWmZenLe) | Simulink 二维限扭 Map、参数版本管理、五类场景验证 |
| [03｜测试方法训练](https://ea6e8con64.feishu.cn/wiki/GajQwq8URioosvk4lJicH3Ksnad) | 通用测试框架、课程方案、标定与总线方法笔记 |
| [04｜动手经历与学习方式](https://ea6e8con64.feishu.cn/wiki/WF5Yw6ntuiuEC3khFI4cQexmnah) | 竞赛动手工作、实习动手工作与自学方法 |
| [05｜关于我与联系](https://ea6e8con64.feishu.cn/wiki/K0TlwGdTziXj89ky9mAcDLIfnYb) | 岗位定位、能力边界与补强计划 |

## 代码与项目仓库

### [minivcu-torque-control](https://github.com/2268499465q-beep/minivcu-torque-control)

MATLAB/Simulink 扭矩限制逻辑建模与多工况验证。仓库包含可直接打开的模型、标定参数、模型重建与自动验证脚本、场景说明和结果记录；在 R2024b 下可重建模型并复现五个场景，输出全部为 `PASS`。

### [hermes-auto-workflow](https://github.com/2268499465q-beep/hermes-auto-workflow)

用 Python 标准库实现的个人自动化工作流示例：定时触发、任务清单读取、Agent 处理与 Notion 沉淀串成一条可复用闭环。仓库是脱敏重构版本，包含 4 个脚本、4 个通用 Skills、合成示例以及架构与排错文档，并说明了生产配置与公开代码之间的安全边界。

### [accelerated-learning-loop](https://github.com/2268499465q-beep/accelerated-learning-loop)

把陌生工程主题转化为可测试、可实操、可迁移学习闭环的个人方法技能包，仓库内含一个脱敏后的汽车总线学习示例。方法设计由我提出，工程化与表达优化由 AI 辅助完成；不承诺固定的「学习倍速」，只用完成时间、正确率与独立完成度衡量效果。

## 工具与方向

`INCA` `ES582` `MDA` `CANoe` `CAN` `Simulink` `Python` `Excel` `万用表` `示波器` `电流钳`

- 汽车电子控制器测试 / 系统测试 / 标定验证
- 台架链路搭建、线束连接与实车测试
- 测量数据分析、异常排查与测试报告
- 接受长期驻场、装车测试与冬夏标

## 说明

公开仓库与作品集页面中的公司、客户、车型、项目代号和内部参数均已脱敏，参数按区间或通用表达描述，不上传内部截图、原始测量文件、程序与配置资料。
